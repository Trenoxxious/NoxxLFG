# Official Repository for NoxxLFG
<sup>World of Warcraft: Season of Discovery Addon by Noxxious</sup>

Find NoxxLFG on CurseForge @ https://www.curseforge.com/wow/addons/noxxlfg

**Current Stable Version:** 1.3.21
*Development Version:* 1.4.0

#### Development Version Updates
**Upcoming v1.4.0 Updates (Ready for Release)**
* The LFG Tool (message constructor) is now available. Construct simple LFG requests and post to your set channel (or LookingForGroup by default) every 30 seconds as normal.
* Ragefire Chasm color changed slightly.
* Blackrock Depths color changed slightly.
* Blackrock Spire color changed slightly.
* Yell and Say are now valid channels when NoxxLFG parses messages. This is extra and does not need to be added to the settings. This is a new-ish feature and will need some proper testing.
* Various UI text updates for clarity.
* Addition of valid parses for Nightmare Incursions.
* Introduction of a proper debug mode using the "/nlfgdebug" command. Using this command prevents the sending of global messages and instead whispers yourself with your message, as well as displaying various other information.
* The "Repeat Post" button now changes to "Cancel" instead of "Reminding in 30s" to make it clear that it can be canceled with the same button.
* The Side Window now shows for raids as well as dungeons. This allows you to view extra information that will be added in the future, as well as safely invite, message or "/who" a player.
* Global Funcs added to support the increasing local variables being created in the main file. Functions will be slowly moved over to Global Funcs over time.
* As a first step toward providing more information in the side window of Dungeons and Raids, they have been given locations and level ranges appropriate for the activity. These will be added to the side window interface in the future.

**TODO/WIP**
* **WIP:** Role filtering in Dungeons has been enabled as a test feature and the update will roll out for raids and events when ready.
* **TODO:** Support the selection/linking of quests in the LFG Tool.
* **TODO:** More information in the "side window" for dungeons and raids when a player left-clicks a post.
* **TODO:** Ability to shift-click and link quests to your LFG message.

### Unique Features:
* **NoxxLFM/LFG** - *Construct and post messages that dynamically update as you build your group.*
* **Quick-Glance Icons** - *Quickly find what you need by using at-a-glance icons like gold/silver amount for travel or role icons for raid/dungeon finding!*
* **Categories** - *Select the specific category you need to keep the LFG frame light and focused on a specific type of group you're trying to find.*
* **Performance Focused** - *By default, NoxxLFG will not log groups or posts unless you are using it, reserving your memory for more important things. This can be disabled in the settings.*
