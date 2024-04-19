# Official Repository for NoxxLFG
<sup>World of Warcraft: Season of Discovery Addon by Noxxious</sup>

Find NoxxLFG on CurseForge @ https://www.curseforge.com/wow/addons/noxxlfg

**Current Stable Version:** 1.3.21\
*Development Version:* 1.4.0

#### Development Version Updates
**v1.4.0 Updates**
* The LFG Tool (message constructor) is now available. Construct simple LFG requests and post to your set channel (or LookingForGroup by default) every 30 seconds as normal.
* Ragefire Chasm color changed slightly.
* Yell and Say are now valid channels when NoxxLFG parses messages. This is extra and does not need to be added to the settings.
* UI text updates.
* Addition of valid parses for Nightmare Incursions.
* Introduction of a proper debug mode using the "/nlfgdebug" command. Using this command prevents the sending of global messages and instead whispers yourself with your message, as well as displaying various other information.
* Additional checks have been added before posting messages to check that another message is not automatically posting first. LFM/LFG messages will not be able to mix and timers will remain consistent across switching between the two posting methods.
* The Side Window now shows for raids as well as dungeons. This allows you to view extra information that will be added in the future, as well as safely invite, message or "/who" a player.

**TODO/WIP**
* **WIP:** Role filtering in Dungeons/Raids/Events & PvP categories.
* **TODO:** Support the selection/linking of quests in the LFG Tool.
* **TODO:** Ability to shift-click and link quests to your LFG message.

### Unique Features:
* **NoxxLFM/LFG** - *Construct and post messages that dynamically update as you build your group.*
* **Quick-Glance Icons** - *Quickly find what you need by using at-a-glance icons like gold/silver amount for travel or role icons for raid/dungeon finding!*
* **Categories** - *Select the specific category you need to keep the LFG frame light and focused on a specific type of group you're trying to find.*
* **Performance Focused** - *By default, NoxxLFG will not log groups or posts unless you are using it, reserving your memory for more important things. This can be disabled in the settings.*
