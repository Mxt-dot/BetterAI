<h2>Europa Universalis 4, current version 1.30.X</h2>

<h2>DISCLAIMER</h2>

**This mod is work in progress. You are free to use any content from it aslong as you reference this project. I try my best to maintain this project and keep all functionality of the mod up-to-date, though of course some things are bound to break eventually. If you like to contribute or help, contact me or open up some issues/pull requests.**
<h2>What is this mod?</h2>
This mod is an enhancement of existing  AI tweaking mods. Thanks to all already existing AI mods for inspiration.

**PLAY THIS GAME ON HARD.**
<h1> So... what's the actual content?</h1>
<h3>Difficulty</h3>
 I tweaked the bonuses for the difficulty. Currently only Hard is modded. "Hard" provides -1 unrest for AI and 10%/25%/50% forcelimit for AI for age of reformation/absolutism/revolution
This mod is supposed to enhance the behavior of the AI to actually invest in Missionaries, to build more buildings and to wage more wars with the goal of blobbing like a player would. 
<h3>Buildings</h3>
Still, a nation is nothing without proper building structure. Therefore the building importance got tweaked a bit to prefer manufactories, workshops, etc. and to give less importance to docks and similar.
<h3>Debt spiral fix!</h3>
Ahh the famous debt spiral we got used to from the 1.30.X patch. This mod will mostly fix it! For real. Due to nations' focus on debt payback and overall creating a vastly more robust nation you will see the AI bouncing back from various situations or just being able to support insane amounts of troops. Example: Average ottomans supporting 300k+ troops with 250+ income in 1600. Without Quantity ideas picked. Yes.
Additional fancy bonus is the AI declaring bankruptcy (if necessary) right after a hefty war in a safely manner to prevent paying back debt endlessly. Not my implementation, but it is more pronounced due to this mod!
<h3>Fort upgrades</h3>
With this mod, the AI is capable of upgrading their forts more consistently when higher military techs are reached. No more level 2 forts in 1700 russia. Of course the AI pays for it aswell, just like the player does.
<h3>AI mana spending!</h3>
This current revision also contains improvements to AI mana spending, meaning it will not waste mana when reaching cap but instead try to invest into provinces. This functionality should be in the basegame!.
<h3>Devpushing Institutions</h3>
The AI now is also capable of devpushing institutions in the best provinces it can find, meaning either capital, gold provinces or just provinces with good trade goods. Of course the AI can't do it for free, meaning it spends 2k mana like the player does.
<h3>Estates behavior</h3>
The AI will resort to selling land to estates more often as it is just such a nice income source. Also they will not be super cautious and instead actually USE their estates for points etc. and amass up to 4 privileges at the same time per estate. Fancy and helpful. AI still gathers more crown land when absolutism+ hits. (Though let's be honest, the AI has no idea on how to increase absolutism. Not before, not now.)

**This mod will not do miracles. It will just try to use the tools we have on our disposale.**
<h1>Just now, I'm working on...</h1>
- evaluating new AI peak performance from 1.30.X
- creating meta heuristics which AI should follow later on
- implementing new very-hard mode with harsher scaling of Troop limit (instead of 10/25/50) it will be (50/75/100) with -2 unrest
<h2>CURRENTLY ON TODO-LIST (recommendations welcome)</h2>

* War logic

  * properly assigning edicts at war
  * AI is not ruthless enough is hunting down enemy armies and does not lock down a region as desired
  * AI should avoid attrition (ever seen a 1.3m forcelimit ottomans navigating? With this mod you will)
  * make england/GB and naval invasions overall useful again

* Infrastructure logic
-

* Overall
  * AI alliance evaluation is not satisfying enough
  * properly calculate dev cost. Currently it's just an estimate based on the amount of base_tax/production/manpower the province has, meaning base-to-dev * 10 is the cost.
  * push natives to complete their religion minigame before they get slaughtered
  * push AI to end disasters when there is an easy fix (looking at you denmark. You could have just stabbed up twice and everything would have been fine.)

<h1>ISSUES</h1>
- AI is now capable of supporting so many troops that they sometimes don't know how to correctly position a strategic frontline and instead just wander off with massive 20 x 30units blobs. Still entertaining though.
- AI building a bit too few barracks for my taste.
-

__________________________________________________________________
SOME OF THESE THINGS WON'T HAVE A FIX AT ALL, BUT I TRY! :) 