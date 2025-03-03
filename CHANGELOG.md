# Upcoming

# Added
- Added a EX setting 2 config to draw pet HP bars on screen.
- Added a EX setting 2 config to auto hide extra UI elements.
- Added a "fontWSHPad." for fonts that looks weird when not in 1:2 ratio

# Changed
- F1 saving now has a 0.3 second pause.
- Extra UI elements (skill tracker / DPS meter / HP bar) now hides if player is too close.

# Fixed
- Player's magic style not shown when casting or using touch skills.
- [Opening mysterious envelope] + [Auto-drop chest] dropping the wrong item.
- Replaced some CJK glyphs from english text.

# 2.21.1.1

## Fixed
- Ported all bug-fixes from Elona+ 2.21fix2.
  - Error 23 crash when weapon dice is 0.
  - Bamboo spirit spawning outside of the Minefield Quest. (Level 70 monster in puppy cave)
- Monster Ball (Bamboo spirit) giving player level 70 monster at very low level.
- Error 23 crash when weapon dice is 0.
- Playing TCG during party time causing you to enter 'overtime'

# 2.21.1.0

## Added
- Ported all changes from Elona+ 2.21.
- Added npc dialog (machine) translation.
- Added a Tweak that allows you to turn-in growing phase child for quests.
- Added a Tweak to have gold drop and openable containers in showrooms (only when visited using Moongate/Runes).

## Fixed
- Jumping drop / Diving drill bug when in a tag-team.
- Chain attack display overlap issue.
- Opening some containers when there's too many item on the map corrupts inventory.
- Tileset errors caused by ocean-tiles in old showroom maps (e.g. the Larnoel ones)
- Elea-leaving event triggered twice caused by the tweak allowing you to nuke beginner cave.

# 2.20.1.1

## Added
- Added a tweak to draw Day/Night cycles indoors.
- Added a tweak to sort spells by type.
- Added a tweak to increase Dojo EXP gain.

## Fixed
- Master/Servant status not increased when interrupting their eat, thanks to @CFWMagic
- Fear and Confuse using wrong resist because I mixed up values during porting.
- Some quest rewards spawing at wrong location due to Auto-Handin tweak having the wrong `cc` value.
- Show NPC name tweak causing spell routing to fail due to using the same global variable.
- TCG bug fixes.

# 2.20.1.0

## Added
- Ported all changes from Elona+ 2.20.
- Added (machine) Translation to new cutscenes, items, and characters.

## Fixed
- Ano hotfixed the bugs in 2.20fix1

# 2.19R.2.1

## Changed
- Auto Hand-in quests is now a tweak.
- Added rewards for TCG
  + You need 80 interest to initiate duel, and 5 minute will pass after duel.
  + You get a impression bonus if you win, this can be used during party time to satisfy guests.
  + You get opponent-level / consecutive-win based music ticket reward.
  + You get 1 card pack for every 5 win against unique NPCs
- Some TCG balance and AI change.
- Added TCG rules to the 'Card Game Manual' Red Book.

## Fixed
- Auto Hand-in quest causing NPC using shadow step attack on others.
- Splitting creatures not dropping items.
- Manuscript/Published-Book item name display error.

# 2.19R.2.0

## Added
- Added TCG functionality.
  + Talk to Miches to get a deck and 20 card packs after you completed her quest.
  + Assemble your deck of 30-60 card, and 'i'nteract and duel with people.
  + Different race have different decks, some NPCs in Vernis have customized deck.
  + Some decks may be underwhelming, some may be gamebreaking, feedback is appreciated.
- Challenge Tweaks
  + Always Etherwind.
  + Double Tax each month.
  + Slower Travel / Hunger doesn't slow in World Map.
  + Allow you to Nuke your home (not really a challenge but still)
- Tweak to revert 2.17 cooking changes.
- Tweak to disable 2.17 boss out-of-sight healing.

## Changed
- Loyter now hate bards again. 
- Slave sprite shown at Slave Trader.
- Zeome AI Tweak are harder to cheese.
- Auto-hand-in harvest/hunt/trap/party/panic/challenge quests.
- Card pack image error, and Card pack generation (may become a tweak if you don't like them)
- Removed Custom-G Nefia gold buff.

## Fixed
- Tileset error in Noyel caused by Custom Nefia.

# 2.19R.1.1

## Added
- Added (machine) translations for some cards, items.

## Fixed
- Some unnecessary changes that causes crash or confusion.
- Custom AI teach page overflow problem.
- Necromancy mobs evolved by evolution tweak.
- Plantinum count not refreshed after training.

# 2.19R.1.0

## Added
- Ported all changes from Elona+ 2.19R.
- Added a UI tweak to display stamina bar instead of stamina number.

## Changed
- Added (machine) translations for some items. 
- Added missing actions to Custom AI teaching menu.

# 2.19.1.0

## Added
- Ported all changes from Elona+ 2.19.

## Changed
- Swapped the description text for Disciple/Master heart-lock relation.
- Fusion: Debuff potions now requires debuff potions instead of poisons.
- Added (machine) translations for some items. 

# 2.18R.1.2

## Added
- Tweak that allow random enemy mob to evolve.
- Tweak that allow faster fishing animation.
- Tweak that allow you to hand in Craft Repair Kits and Material Kits instead of Socks in Urcaguary Quest.

## Changed
- Custom AI supports remote blow. (If distance > 1 and action is set to Melee Attack)
- Pot of Fusion Page is now remembered.
- Devil fragments are split when used in fusion.
- Item weight is shown when you walk on them.
- More status information is displayed when you (l)ook at people.
- Added a temporary world event filter so world event won't overwhelm slow/new characters.
- Removed the growth value 1/4 display change because it confuses people.
- Adjusted the CNPC summon screen and and added some balancing.
- Allow leashing temporary allies.

## Fixed
- Thread of innervation does knockout animation.
- Wrong creature filter causing some NPC spawning at wrong places.
- Some dialog pop-up / npc name display issue.
- Optimized some performance issues caused by DamageMeter/ShowNPCName/DamagePopup.
  + The DamageMeter and ShowNPCName will be disabled by default in the config.txt

# 2.18R.1.1

## Added
- Added Tweak to make necromancy minions actively seek out enemies like pets, Thanks to @air1068

## Fixed
- Some visual issues.
- Custom Harvest Quests too hard for new characters.
- Big Daddy spawning causing DESTINY item spawn at coordinate (0,0)

Thanks to @air1068 for contributing.

# 2.18R.1.0

## Added
- Ported all changes from Elona+ 2.18R.
- Added damage meter, the Bar color is decided by the character's real class.
  + <span style="color:#C79C6E">warrior</span>
  + <span style="color:#FFF569">thief</span>
  + <span style="color:#69CCF0">wizard</span>
  + <span style="color:#00FF96">farmer</span>
  + <span style="color:#FF7D0A">predator</span>
  + <span style="color:#ABD473">archer</span>
  + <span style="color:#A330C9">warmage</span>
  + <span style="color:#F58CBA">pianist</span>
  + <span style="color:#C41F3B">gunner</span>
  + <span style="color:#0070DE">priest</span>
  + <span style="color:#FFFFFF">claymore</span>
  + <span style="color:#D0D0D0">tourist</span>
  + <span style="color:#4DD827">no class</span>

## Changed
  - Added trainer to 'more hireable servant' tweak.

## Fixed
- NPC name/chat showing above quest/god UI
- Added (machine) translations for some item and characters.


# 2.18.1.0

## Added
- Ported all changes from Elona+ 2.18.
- Added chat pop ups.
- Added a tweak option to disable "exp modifier based on Main Quest Progress".

## Fixed
- Fixed following bug from original 2.18
  + Shadow hop summoning hostile shades that drops loot.
  + Using return/escape/aurtehom underwater stuck you inside another continent.
  + Jukebox missing several music.
  + Title plays World map music due to a mistake in settings.

# 2.17.1.1

## Added
- Added "Percent Chance" condition for Custom AI.
- Added Import/Export/Reset utility for Custom AI, added hint for swap rows.
- Added a tweak option to "enable CNPC summoning using a summoning crystal and disable random CNPC spawn".

## Changed
- Custom Nefia Layouts: Reduced monsters in some map layouts.
- Custom Pet Configuration: Raised "eat from your bag" hunger criteria to 10000, added options for drink and chat.

## Fixed
- Fixed a bug where uninitiated ammoproc causing the normal attack animation to be skipped.
- Fixed a bug where NumLock button get spammed when the game starts in background.
- Fixed a bug where "autodestroy_sound." config overwrites "sound." config.
- "BARREL!" support for english speaking alchemists.

# 2.17.1.0

## Added
- Added a tweak for enabling different reward mechanic in quests.
  + Delivery quests now require the exact item they give you to be delivered, but rewards more platinum coins.
  + Harvest quests now give rewards based on how many crops you delivered. Added chances to spawn heavier crops in higher levels.
  + Conquer quest boss now uses breath attacks.
  + Exterminate quests spawn the enemies together instead.
  + Civilians now appear in Conquer/Exterminate quests.
  + People throw more music tickets during Party Time Quests
- Added a tweak for custom animations for Dart/Bolt/Ball spells. Credit:
  + [さく](https://www.pixiv.net/en/users/5877877)
  + [craftpix](https://craftpix.net/)
  + [unTied Games](https://untiedgames.com/)

## Changed
- QoL changes to job quests.
  + Show the remaining time if you are in a quest map, and there's a time limit.
  + Quest emotes are now shown immediately when you enter a map.
  + If you have the item a Fetch Quest need, it will be marked in quest board.

# 2.17

## Added
- Ported all changes from Elona+ 2.16 and Elona+ 2.17.

# 2.15R.1.0

## Added
- Ported all changes from Elona+ 2.15R.
- Added a tweak to disable urination from fear-related effects.
- Added a tweak to add a chance of generating new experimental Nefia layouts, courtesy of @JianmengYu.
- Added "Use Shift Core" custom AI action.
- Added a "Custom AI" option to the wizard menu.

## Changed
- Custom AI can now be used by non-ally NPCs.
- Custom AI will now be saved to pet arena teams in `.pet` files and applied when the team is loaded for battling.
- Blending will now inform the player if their inventory is full when a stacked ingredient is about to be separated.

## Fixed
- Fixed asking for potion plugs bringing up the wrong menu.
- Fixed Hydro Fang being missing from the Custom AI skill list.

# 2.14.1.0

## Added
- Ported all changes from Elona+ 2.14.
- Added English translations for some item descriptions (potions, drinks, music disc).
- Added a message displaying how much gold pets receive when they enact prostitution.
- Added a new console command for taking a screenshot of the entire map (`save_map_image`).
- Added a tweak to revert changes to the experience formula after Elona+ 2.13.
  + Addresses "increased experience multipliers when defeating enemies above the player character's (PC) level".
  + Toggling this also reverts the change to taxation coming into effect after New Year's.
- Ported omake's autopickup feature.
  + Enable this feature in the `EX Setting 1` subsection of the settings menu.
  + Press <kbd>Shift</kbd>+<kbd>Backspace</kbd> while in-game to create or reload the current autopickup settings file.
  + Press <kbd>Ctrl</kbd>+<kbd>Backspace</kbd> to open the currently loaded autopickup settings file in your text editor.
  + Press <kbd>Alt</kbd>+<kbd>Backspace</kbd> to quickly toggle autopickup on and off.
  + A detailed tutorial is included in the autogenerated settings file.

## Fixed
- Fixed the incorrect sprite being used for the laser bazooka attack animation.
- Fixed the effect of Element Eyes not being applied to Variable Breath when it was used by custom AI.
- Fixed crashes with high-quality item shadows and DPI scaling. Be sure to copy the included `elona.dll` to your install directory to apply the fix, overwriting the existing file.
- Fixed the NPC name changes for pet evolution and the werewolf game for some character types.

Thanks to @Regaccio and @JianmengYu for contributing.

# 2.13.1.0

## Added
- Ported all changes from Elona+ 2.13.

## Fixed
- Fixed being unable to execute undead fusion.

# 2.12.1.1

## Added
- Added translations for the rest of Act 3's story cutscenes. (#100)

## Changed
- Reworked parts of the story cutscenes to follow the Japanese translation more closely. (#100)

## Fixed
- Fixed the SP cost of Cooking and Fishing. (#106)
- Fixed a crash caused by urination from fear. (#102, #105)
- Fixed the display of spell power in menus. (#87, #99)

Thanks to @AHairyGameDev and @air1068 for contributing.

# 2.12.1.0

## Added
- Ported all changes from Elona+ 2.12.

# 2.11.1.0

## Added
- Ported all changes from Elona+ 2.11.
- Added a tweak for increasing the maximum number of arena attempts per day. (#89)
- Added a tweak for disabling the spell overcast warning. (#89)
- Added a tweak for increasing the variety of hireable home servants. (#92)
- Added a tweak for increasing the drinking/brawling chance during Party Time! quests. (#96)
- Added a tweak for disabling stamina loss when melee attacking or casting spells.

## Changed
- Allow spawning Little Sisters by killing Big Daddies with Empathy/persuasion skills. (#88)

## Fixed
- Fixed cargo food items not applying thirst reduction.

Thanks to @EnragedWaters for contributing.

# 2.10.1.1

Thanks to DiscoWitch for fixing these issues.

## Fixed
- Fixed status effects not applying.
- Fixed a crash that occurs when fishing.
- Fixed the display of the Super Accel buff in the profile.

# 2.10.1.0

## Added
- Ported all changes from Elona+ 2.10.
- Added a tweak that makes summoned monsters give skill/spell experience. (#66)
- Added a tweak for skipping the confirmation when spending platinum on skill training.
- Added a tweak for auto-dropping empty chests after opening them. (#50)
- Added a tweak for using stairs in your home without depleting stamina. (#43)

## Changed
- Make Oblivion Palace a returnable location in wizard mode. (#40)

## Fixed
- Fixed analysis gauge logic applying to the player. (#53)
- Fixed the behavior of the "Prevent home stayers from moving" tweak. (#52)
- Fixed some incorrect results of using crop management tools. (#67)
- Fixed some incorrect pronouns/grammar being displayed in the feats and buffs menus. (#64)
- Fixed enchantment magnitude being displayed in the feats menu details. (#65)
- Fixed shop names being incorrectly displayed when changing shop types. (#40)
- Fixed a few typos and translation errors. (#40)
- Fixed a crash when trying to move a hostile creature in your home. (#40)

# 2.09.1.0

## Added
- Ported all changes from Elona+ 2.09.

## Fixed
- Fixed elemental damage causing no status effects. (#78)

# 2.08.2.0

# Added
- Added a new "Do Nothing" custom AI action. (#68)

# Changed
- Hydro Fang now causes wet. (#69)
- Remove the release-build dependency on `hsplua.dll`. It can be enabled again with a compiler define.

# Fixed
- Fixed the subject for the "bored" town citizen dialog lines being incorrect. (#60)
- Fixed the displayed level of duel opponents being incorrect. (#55)
- Fixed some elemental damage not causing status effects. (#63)
- Fixed a couple of AI action lists for some characters being incorrect. (#76)
- Fixed NPC actions interrupting the player's actions. (#76)
- Fixed some minor typos. (#73, #74)
- Fixed crashing when anorexia status becomes too high. (#72)
- Fixed enchantment level not displaying for the enchantments added in 2.08. (#70)
- Fixed the enchantments addable to living weapons being different from stock Plus. (#62)

# 2.08.1.0

## Added
- Ported all changes from Elona+ 2.08.
- You can now see tiles that are cut off at the top of the screen due to the selected screen resolution. Please set the `showTopTileCutoff.` option to `"1"` in `config.txt` to enable this feature.

## Changed
- The "Show enchant strength" tweak can now optionally be used to display the enchant power of all enchantments, not just those with a declared power level in the vanilla UI. This is helpful for artifact fusion. (#46)
- Allow the "Display Pickpocket shortcut" tweak to work inside Party Time! quests. (#57)

## Fixed
- Fixed the town travelling message being displayed in English when the language is Japanese. (#49)
- Fixed the DESTINY conditions not being tracked if the "Disable DESTINY" tweak is active. (#44)
- Fixed the hit chance displayed by the Data Scan buff always showing 0 if the language is English. (#54)
- Fixed the "flying bane" enchantment being generated on gloves instead of ranged weapons. (#59)

# 2.07.2.0

## Added
- You can now rename the gender you select during character creation.

## Changed
- Display the actual danger level for Fort of Chaos nefia.
- Summon Spirit now scales with the spell's level and spawns neutral creatures that attack enemies.
- Revert the translations for the extra genders to that of stock Plus.
- The `sex` wish now allows you to choose your new gender from the list available during character creation.

## Fixed
- Fixed the limits on speed bonuses from Leold during the main story not being correct.
- Fixed a few details of certain blending recipes, and reverted Custom-G's changes to them.
- Applied the change to the shortcut text display for the inventory window from Elona+ 1.995.
- Fixed not being able to sound the horn when driving a truck.
- Fixed roads being removed when building something over them using a deed.
- Fixed spell bonuses being incorrectly labeled as skill bonuses in the journal.
- Fixed the layout of the journal records so they don't overflow the page.
- Fixed player skill bonuses on level up not being tracked in the journal.
- Fixed Big Brushes and Nyoi Mimikaki being randomly generated.
- Fixed a crash when offering livestock with Impress greater than 150 to your god.
- Fixed auto aim cheetahs not having their special ammo action.
- Fixed the random generation of items added in later Plus versions.
- Fixed more crashes due to OS-level DPI scaling.

# 2.07.1.2

## Changed
- Limit the combinations of resolution and DPI scaling in the options menu so that fullscreen always works.
- Prevent crashes from invalid resolutions by checking if the maximum display size is exceeded on startup.

# 2.07.1.1

## Changed
- Don't show damage popups for passive stamina regeneration from thirst.

## Fixed
- Fixed a crash when talking to a bartender with thirst enabled.
- Fixed a rendering glitch with the Nefia Fever clock.
- Fixed more issues with screen resolutions and fullscreen/crashing.
- Fixed certain world map area entrances being generated with grass instead of snow. To apply the fix to existing saves, open the console with F12 and type the command `cgx207mapfix`.
- Fixed maps with multiple door types changing doors to the wrong tile when opening/closing them.
- Fixed a small typo in the Japanese language after travelling between towns.

# 2.07.1.0

## Added
- Ported all changes from Elona+ 2.07.
- Added new custom tweaks to disable several changes from Custom-G: thirst, Curtain Call, chain attacks, and sleep prevention from coffee/tobacco.
- Added an option in `config.txt` for showing the FPS (`showFps.`).

## Changed
- Existing CGX saves will now have the previously mentioned Custom-G changes disabled by default. Please use the Tweaks menu from the in-game Escape menu to enable them again.
- Don't disable scrolling if the player has a tag team partner.
- Retrieve the list of valid screen resolutions from the OS instead of hardcoding them.
- Limit the DPI scaling option to increments of 0.5 only.

## Fixed
- Fixed collect yield option in farms not resetting plant status. (Thanks, @Mirarara!)
- Fixed a crash when claiming YacaPoint rewards.
- Fixed various incorrect item descriptions in Japanese.
- Fixed various issues when trying to use screen resolutions that are not a multiple of 4 and esoteric DPI scaling amounts.

# 2.06fix.2.0

## Added
- Translated all untranslated text except cutscenes, and improved upon Custom-G's machine translations.
- Restored all of Elona's original network code that was removed in Elona+.
- Added marriage chat messages from the work-in-progress Elona source code.
- Added back the option to vote on an alias when using the voting box.
- Added HiDPI scaling and smoothing options, accessible from the Screen & Sound section of the options menu.
- Added a patched version of `elochat.exe` that can be configured to use a different server.
- Added an option to show the actual numbers for class/race stats during character creation (`charamake_preciseStats.`).
- Added a tweak for quickly reloading the last save upon death.
- Added a tweak to revert changes to the experience formula after Elona+ 1.90.
- Added a tweak to disable study day bonus skill experience.
- Added a tweak to disable the DESTINY feature and restore the chances of finding godly equipment.

## Changed
- Enable the use of network features by default.
- Use `elochat.yeek.agency` as the default chat server.
- Make the codebase compatible with HSP 3.6. (Thanks, @Mirarara!)
- Show the Life, Mana and Speed, and body parts of classes/races during character creation.
- Don't apply "Prevent home stayers from moving" to special NPCs like Lomias and Larnneire.

## Fixed
- Fixed Yacatect's Bank not working on use. (Thanks, @Mirarara!)
- Fixed Memory Converters not working on use.
- Fixed potion puddles not spawning when throwing potions.

# 2.06fix.1.0

## Added
- Ported all changes from Elona+ 2.06fix.

# 2.06.1.0

## Added
- Ported all changes from Elona+ 2.06.
- Added "Disable cicada noises" custom tweak.

## Fixed
- Fixed tables not having the manuscript writing item effect.
- Fixed spell stock conversion by using tables causing spells to be casted instead.
- Fixed planted seeds not showing the correct text when walked over.
- Fixed a crash caused by casting Meteor.
- Fixed oblivion rude beasts being unable to cast Summon Chaos (as stated in the Elona+ changelog).

# 2.05.1.1

## Added
- Added back the "special drink" dialog option for bartenders.

## Fixed
- Corrected the buff duration of Killing Dance to be 13 turns instead of 44.
- Fixed character images not being set on cards spawned by opening card packs.
- Fixed a crash that occurred when using the deck.
- Fixed a bug causing PCC eyes to be set incorrectly.
- Fixed an issue causing the Japanese description for Harvest Time quests to become blank.
- Fixed the popup for expiring buffs not appearing or being incorrect.
- Fixed the pet arena win count not incrementing.

# 2.05.1.0

## Added
- Ported all changes from Elona+ 2.05, using Elona+ Custom-G 1.90.2.4 as a base.
- Ported omake overhaul modify's damage popup feature, configurable in the options menu.
- Added "Allow running in world map" custom tweak.
- Added a limited Lua console for debugging purposes.

## Changed
- Uncap the screen resolution limit.
- Center the text that's shown during cutscenes.
- Allow usage of Suspicious Hand if the target is sandbagged and "Sandbag Training" is enabled.

## Removed
- Removed the 100 skill point/platinum cap.
- Removed the NPC/card/item externalize feature.

## Fixed
- Fixed a bug causing Jaldabaoth's wing animation to glitch.
- Fixed a bug causing certain portraits to be cut off when running at 800x600 resolution.
