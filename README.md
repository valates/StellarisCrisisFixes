# Installing this mod manually

Download the zip containing these files. You should get a folder name something like "blahblah-master." Inside that folder is a .mod file which can be opened with notepad and a folder containing other files. Copy and paste the .mod file and the folder to "C:\Users\<USERNAME>\Documents\Paradox Interactive\Stellaris\mod." After that, this mod should show up as a selectable mod in your mod list on startup.

You don't need the README.md file.


# I want everything. Just give me a Steam download link

http://steamcommunity.com/sharedfiles/filedetails/?id=910137601


# Changelog
## Crises

### General
-Enabled multiple crises to occur. Multiple instances of the same crisis are still disabled.

### Prethoryn Swarm
-Removed 25% chance of swarm not spawning.

-Rescaled crisis start time from 10/20/30/15% for 170/200/250/300 years to 15/25/35/20/5% for 170/200/250/300/350 years.


## Fallen Empires
# Fleets
-Removed requirement that Fallen Empire not be at war to create a new fleet

-Increased time to create a new fleet from 1 month to 360 months. 

Note: new fleets still only spawn if total fleet power < 5000.


# War in Heaven
-Increased chance of Awakened Empire having War in Heaven with rival ethos Fallen Empire from 40% to 55%.

-Increased chance of Awakened Empire having War in Heaven with random Fallen Empire from 20% to 35%.

-Reduced chance of no War in Heaven post-Awakened Empire from 40% to 10%.




# Disabling changes

## Vanilla Swarm Spawn Probabilities/Allow chance of No Swarm Spawn
Delete game_start.txt


## Set own Swarm spawn timers/probabilities
Line 255 of game_start.txt. For a probability of no swarm spawn, make one entry x = {} where x is a number, the probability of no spawn happening.


## Vanilla Unbidden Jump Drive Risk
Change line 55 and line 60 of crisis_events_2.txt to "factor = 0.8"


## No Fallen Empire Fleet Respawn
Delete fallen_empire_events.txt


## No War In Heaven Changes
Delete fallen_empire_awakening_events.txt




