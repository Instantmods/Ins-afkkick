This AFK Kick script for FiveM automatically kicks players who remain idle for an extended period, ensuring active participation on the server. This script monitors player activity and checks if any player has been inactive for longer than the specified AFK time limit. If a player exceeds this limit, they are kicked from the server with a message indicating they were removed for being AFK too long.

Features
1. Configurable AFK Time Limit: Set the maximum allowed idle time before a player is kicked.
2. Periodic Activity Check: Regularly checks player activity to determine AFK status.
3. Automatic Player Kick: Kicks players who exceed the AFK time limit.
4. Server and Client Integration: Utilizes server and client scripts to monitor and manage player activity efficiently.

Installation
1. Place the Ins_afkkick folder in your resources directory.
2. Add start Ins_afkkick to your server.cfg file. 

Configuration:
Adjust the afkTimeLimit variable in server.lua to set the desired AFK time limit (default is 600 seconds or 10 minutes).
Optionally, change the checkInterval variable to modify how often the script checks for AFK players (default is 60 seconds).
