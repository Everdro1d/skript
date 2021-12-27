# Dro1d's Skript Projects
This is a collection of my skript projects mostly for archiving purposes but feel free to download and use whatever you find here for yourself.

## Resources


### Day Counter

A script that keeps track of what day it is in game and allows for timers.
#### Features:
* Allows the player to check what day it is with
* Allows players to set and delete timers for `x` number of days as well as allows for custom timer names (i.e. exampleTimer for 10 days)
* List the player's active timers
* Check how many days remain on an active timer

#### Dependencies
The day counter skript requires skript-reflect, which can be found here: [Download](https://github.com/TPGamesNL/skript-reflect/releases)

---
### Join Message
A simple script that sends a custom join message.
#### Features:
* When a player joins the server sends a message, `[+] PlayerName`
* When a player leaves the server it shows `[-] PlayerName`

---
### Marriage Counter
Initially started out as a kiss counter but then evolved with a burst of 3am inspiration.
#### Features:
* Keeps track of the number of kisses the player has given to their partner(s)
* The amount of times a player has gotten married or divorced
* Adds commands to check how many times the above have happened

#### Dependencies
Made to be used with MarriageMaster plugin. [Download](https://github.com/GeorgH93/MarriageMaster/releases)

---
### Map Command
A simple /map command that sends the link to your server's map.
#### Features:
* The link can be easily changed
* No more ugly links in chat!
* Makes the message stand out?

---
### Player List
Creates a simple list of players, both online and offline.
#### Features:
* List of online players
* List of offline players (Any player who has ever joined)
* Commands to view online players and offline players

---
### Playtime
Shows the playtime of the player.
#### Features:
* Simple command to get the playtime of a player `/playtime`
* Players with the permission `playtime.other` can view the playtime of other online players by adding the player's name
#### Planned:
* Get the playtime of an offline player

---
### Queued Commands
Queue a command to execute when a player joins
#### Features:
* Set commands to execute on the player joining the server
* Allows commands to be executed both by console or by the player themselves (still requires permissions)
* Can queue commands to execute for offline players
* Show a list of commands that have been queued for a player
* Cancel a queued command with the ID
* Permissions to allow queuing commands
#### Dependencies:
[Optional]
* Player List script (Offline player functionality)
* Tab completer script (Allows auto-completing where applicable)

---
### Restart Timer
A restart timer.
Note: the code for this one is a mess look at it after preparing for physical pain
#### Features:
* Sends a message to all players at 30, 15, 10, 5, 1 minutes away
* Countdown in the chat at 10 seconds
* Timer is set in minutes
* Ability to cancel scheduled restarts

---
### Speed Warp
This one is a WIP but is meant to allow for quicker usage of the /home command.
#### Planned Features
* Allow binding homes to an ID number (i.e. `/home storage` would become `/sw 1`)
* Tab complete for applicable options

---
### Tab Completer
Exactly as the name implies, this script allows for auto-completion of applicable commands from my scripts above.

#### Dependencies
[REQUIRED]
* SkBee: [Download](https://github.com/ShaneBeee/SkBee/releases)
