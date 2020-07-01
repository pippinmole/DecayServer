# Decay Server
Report any issues you may have here :)

## How to set up a server
1. Locate the server files (for now, they are located in '[RootGameDir]/server/', or in the 'Host' tab of the main menu).
2. Open the 'Run Server.bat' and change the configuration to your liking.
3. Run the bat file, and wait for the server to start.

## Server .bat ConfigVars

| Command  | Description |
| ------------- | ------------- |
| serverName  | This is the display name of the server, clients connecting will see this.  |
| mapName  | This is for future maps that may come, keep this as 'Game', or the server will not boot.  |
| maxPlayer  | This is the maximum amount of players that can join.  |
| password  | If you want a password, you can add one here. (NOTE: This only works if you have 'passworded' set to true)  |
| passworded  | If true, clients will be required to enter a password.  |

## Console Commands
There are a limited amount of commands, but if you suggest any, I will make sure to add them.

| Command  | Description |
| ------------- | ------------- |
| stop  | Stops the server.  |
| kick [steamId] [reason]  | Disconnects the specific client from the server, the kicked client will see the reason.  |
| ban [steamId] [reason]  | Bans the specific client from the server permenantly. They will not be able to rejoin until you unban them. |
| unban [steamId]  | Removes the specific client from the banlist. They will be able to join immediately after this command is run.  |
| bans  | Lists all current bans on record. If a ban does not show up in this list, they are not banned.  |
| online  | Lists all currently connected clients. (In the format [playerName] [steamId])  |
| setAdmin [steamId] [value]  | Sets their admin priviledge depending on the value passes in, where '[value] = true' sets them as administrator.  |
| save  | Saves all current entities in the world to file.  |
| chat [message]  | Sends a global message to the entire server.  |
| kill [steamId]  | Kills the specific client.  |
| help  | Prints all current commands in the game.  |

## Current workarounds
If you select anywhere inside the console window, it will pause the server. It is a known issue and I am looking for a fix for this.
