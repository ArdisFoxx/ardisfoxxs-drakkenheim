As a GM I've run Dungeons of Drakkenheim in 5e, PF2e and Daggerheart, including paid games for Startplaying.games. I wanted to share my PF2e conversions with other GMs. This module is the culmination of my continued efforts in making Drakkenheim in PF2e and Daggerheart the easy and fun as possible.

The module includes Actors and Items for playing Drakkenheim campaigns in PF2e and Daggerheart (in development), as well as Scenes, Journals, Macros, Rolltables, Playlists and Sound Effects to enhance your Drakkenheim campaign into a premium experience. In order to publish this as a module I had to move the scene and actor images into new folders, which broke everything, so I've pretty much had to create the entire adventure from scratch. So the module is a work in progress, but I hope that the bones of what I've been able to put into this module help you get your campaign started.

---------------

# Important Note Before Installing

This module relies on certain premium Drakkenheim content from Ghostfire Gaming and 3rd party content from Epic Isometric to fully function. Email me at ardisfoxxart@gmail.com with your purchase receipt of the Drakkenheim PDF and the Epic Isometric Patreon and I can supply you with a MEGA folder containing the additional assets required for this Foundry module. 

For full functionality I also recommend picking up the Simple Quest and Macro Wheel modules from TheRipper93's Patreon - just subscribe for a month then download the modules you want and cancel your sub if you don't want to continue supporting. I promise that those modules are worth it.


https://ghostfiregaming.com/product/dd-dk-pdf-and-maps/

https://www.patreon.com/c/epicisometric/

https://theripper93.com/module/simple-quest 

https://theripper93.com/module/macro-wheel

![The Landing Page](https://github.com/ArdisFoxx/ardisfoxxs-drakkenheim/blob/main/assets/UI/Landing%20Page/Drakkenheim%20Landing%20Page%20Blank.jpg?raw=true)

![Emberwood](https://github.com/ArdisFoxx/ardisfoxxs-drakkenheim/blob/main/assets/UI/Landing%20Page/Emberwood%20Isometric%20by%20side_way.jpg?raw=true)

-----------------

# Installation Instructions

Go to your compendiums and search for "AFD". Import the Landing Page scene folder, as well as all Journals, Macros and Roll Tables. The remaining Actors, Items, and Scenes, you can just leave in the compendiums and import them individually as needed (the less you import, the smoother your Foundry will run). If you want to utilize the included Playlists, import them too.

If the actor images and the scenes all appear broken, then you haven't emailed me your proof of purchase of the Drakkenheim book as outlined above. Do that.

_Video tutorial for setting up the module:_
[![Configuring ArdisFoxx's Drakkenheim](https://raw.githubusercontent.com/ArdisFoxx/ardisfoxxs-drakkenheim/40e2816f084d44c3bcc8ffac2fd50c7bf9e36206/assets/UI/Landing%20Page/AFD_YT_TUTORIAL.png)](https://www.youtube.com/watch?v=e_ep9VeGOE4)

-----------------

# Customize It For Your Campaign

## The Landing Page Background

The Landing Page scene is a jpeg, but in the folder "ardisfoxxs-drakkenheim/assets/UI/Landing Page" I've included the .psd file for it, so you can edit the playing cards with images of your own adventuring party. Just open the PSD file in Clipstudio Paint, Photoshop or whatever PSD editor you have access to (I recommend https://www.photopea.com/ its a free open source online PSD editor that doesn't require installation). Once you've made your edits, export the file in JPEG format and save it in the "ardisfoxxs-drakkenheim/assets/UI/Landing Page" folder, then edit the Landing Page scene and set your new scene background image.

## Making the Landing Page Items Clickable

The Landing Page scene has a bunch of invisible tiles on it which trigger certain functions using Monk's Active Tile Triggers:

* Clicking the gold bag opens the party loot vault
* Clicking the candle opens the Sacred Flame lore page
* Clicking the player cards open the player's personal journals
* Clicking the astrolabe opens lore about delerium and the haze. These feature homebrew changes to contamination that make contamination usable in both PF2e and 5e
* Clicking the maps opens them in an image view
* The faction reputation sliders are all tiles that can be moved around, showing the PCs reputation with factions from nemesis > enemy > neutral > ally > champion
* Diablo II sound effects on all the tile triggers

Unfortunately when you import this module's content, the journals, scenes and macros may get new document IDs, which will cause the Landing Page tile triggers to break. Meaning you'll click them and nothing will happen. To fix that, select the Tile layer on the Foundry sidebar, then double click the invisible image tile you want to edit. Go to the Triggers tab and examine what the Action is that the token trigger is trying to do. Usually it will be running a Macro or opening a Journal which has a different ID than the one in your world - pointing it to the correct one in your world will fix it.

Journals PSA: **DO NOT** give your players Ownership permission to the Quest or Lore journals, as this will give them access to view the ones you've marked as purple/hidden - they'll see all your spoilers!

-----------------

# Delerium Rules in PF2e

_Note that the module includes macros to make these checks easy to do in game._

## Search for Delerium (Outer City)
You use the Search exploration activity to look for delerium deposits against a normal leveled DC. Each additional person using Search can Aid your check.
Success: You find 3d6 delerium chips and 1d6 delerium fragments which you may attempt to harvest.
Critical Success: You find double the chips and fragments, and 1 delerium shard.

## Search for Delerium (Inner City)
You use the Search exploration activity to look for delerium deposits against a normal leveled DC. Each additional person using Search can Aid your check.
Success: You find 3d6 delerium chips, 2d6 delerium fragments and 1d6 delerium shards which you may attempt to harvest.
Critical Success: You find double the chips, fragments and shards, and 1 delerium crystal. 

![Delerium in PF2e](https://github.com/ArdisFoxx/ardisfoxxs-drakkenheim/blob/main/assets/UI/Harvesting%20Delerium.jpg?raw=true)

-----------------

# Drakkenheim House Rules
I've used the following house rules in all six Drakkenheim PF2e campaigns that I have run, and they have been very well received by players and GM's alike.

## Addition: Random Encounter Checks

_Note that the module includes a macro to make these checks easy to do in game._

**Sense Direction:** When traveling within Drakkenheim city, one party member must succeed on a Sense Direction check at the normal leveled DC. Failure adds one complication to the Random Encounter Check. If no one attempts it, it counts as a fail.

**Random Encounter Check:** Each player rolls a die. The base die is a d10 for Outer City travel and a d6 for Inner City travel. The GM secretly rolls two of the same dice.

**Complication:** The first GM die sets the target number for complications—these could be encounters, skill challenges, or travel difficulties. If any player’s roll matches this number, a complication occurs. Multiple hits escalate the severity.

**Good Fortune:** The second GM die sets the target number for good fortune—an ally, treasure, delerium, or opportunity. This can happen alongside complications.

**Frequency:** The party rolls once per travel segment through the city—typically when entering, traveling inside, and leaving.

**Stealth and Speed Modifiers:**  
- Using stealth aids or magic (e.g., Vanishing Tracks, Invisibility) **increases** the encounter die size by one step (e.g., Outer City d10 → d12, Inner City d6 → d8).  
- Traveling at full speed **decreases** the die size by one step (e.g., Outer City d10 → d8, Inner City d6 → d4).
These modifiers adjust the likelihood of encounters accordingly.

NB: The reason the "fail" and "win" target numbers for the roll are randomized by the GM is that it increases tension among the players; they don't know whether those three 4's they just rolled meant nothing special or a super bad result. If no encounter triggers, the GM should still describe their journey in detail and describe situations that sound like something terrible is about to befall them, but they sneak around it or duck into an empty manor house while the haze hulk or elite garmyr patrol stalks by.

## Change: Resting
The rules below replace or amend the default rules for resting. Note that long rests cannot be completed within the contaminating eldritch haze that permeates the city of Drakkenheim and extends out to 2 miles around it.

**Rest.** Completing a long rest takes 24 hours. A long rest can only be completed in an area of safety such as a secure encampment, an inn or a tavern; a place where you can eat well, rest and recover.

**Bath Houses**. The most luxurious inns in the world are often appointed with a bath house. Spending 1 hour of bliss in a bath house reduces the required length of your next rest down to 8 hours. Some bath houses even have magic waters, enchanted by the Amethyst Academy to invigorate the muscles and sooth the spirit.

NB: These rules support the Diablo style gameplay Drakkenheim is suited for, and it encourages the PCs to stay in Emberwood for longer periods in between their trips to the city. Even the most fervent min-maxer will be encouraged to relax at the Red Lion Inn or the attached Bath House for *longer* than RAW minimum 8 hours of complete bed rest, so your PCs will have a chance to get to know your NPCs and each other.

-----------------
_Note that the Landing Page module previously required Lock View version 1.5.5 and Isometric Perspective module, but the latest versions of Landing Page use Foundry v13 and these other modules are not compatible, so the updated scenes have been configured not to use them._

_Also note that the "ardisfoxxs-drakkenheim/assets/UI" folder also includes "Old" assets used in my previous module "Drakkenheim Landing Menu". I've left these in there in case they might be useful for you - some of them are used for this new module._
