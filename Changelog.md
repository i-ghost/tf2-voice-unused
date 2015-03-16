This is a history of all public releases.


---

#### 0.8\_FINAL `07/04/2011` ####
  * Fan O'War now shares kill responses with the Holy Mackerel

  * Fixed unwanted behaviour relating to Medic's combat ubercharge responses playing when he deploys an ubercharge.

  * Removed applycontexttoworld for Sniper's Shiv kill response; stops him from saying it more than once within ten seconds (for real)

  * Tweaked responses in Engineer.txt so that they correctly apply contexts, so that lines do not overlap etc. This seems to be a mistake on valve's part.
  * Tweaked Engineer's multi-kill responses so that they can play after any type of kill, used to be restricted to primary weapon.

  * Recompiled scenes.image and updated game\_sounds\_vo\_handmade.txt to fix an issue with one of Medic's melee dare lines not playing
  * Allowed Medic's multi-kill responses to play regardless of weapon
  * Tweaked responses in Medic.txt so that they correctly apply contexts, so that lines do not overlap etc. This seems to be a mistake on valve's part.

  * Fixed temporary entry in Medic.txt
  * Rebuilt scenes.image to remove superfluous temporary debugging choreography file.

  * Tweaked Gunslinger responses so that they do not interrupt domination/kill lines, removed superfluous EngineerNotKillSpeechmelee

  * Reworked rule EngyCritsReady to actually check for a mini sentry kill in the past 15 seconds, used to simply check if the Engineer had a kill in the past 20 seconds.

  * Added Jarate responses for Engineer
  * Reworked some rules in Heavy.txt so they actually set contexts properly
  * Fixed Heavy's Dispenser destruction response
  * Tweaked punching responses so they cannot interrupt melee kill responses or domination responses, this also reduces Heavy's chattiness somewhat which is a good thing
  * Included a new rule that has Heavy say his new weapon responses when he winds his minigun, 10 percent chance of occurring every 30 seconds - these responses are still on the 'Battle Cry' voice menu option

  * Removed a response from the melee dare group (it's now a Jarate response and fits better there)

  * Included normal Sentrygun in EngyCritsReady responses
  * Added two new responses to EngyCritsReady response group

  * Tweaked responses in Scout.txt to apply contexts correctly

  * Added Achievement responses for Soldier

  * Tweaked rules in Soldier.txt so they apply contexts correctly

  * Tweaked rules to apply contexts correctly in Sniper.txt, Pyro.txt and Spy.txt

  * Moved rules around for better viewing

  * Tweaked rules to apply contexts correctly in Demoman.txt and Medic.txt

  * Removed a notice

---

#### 0.75/RC2 `19.03.2011` ####
  * Moved a line to Medic's auto/manual assist lines group from the Kritz activation group

  * Updated Heavy's fist swinging lines so that they cannot interrupt his melee dares
  * Removed a duplicate entry in Scout.txt
  * Removed a duplicate entry in Sniper.txt
  * Made Sniper's 'new weapon' lines not interfere with his melee dares
  * Removed Spy's Sniper kill lines, as they are already used elsewhere (as a Sniper domination) and I used a wrong line anyway (used an Engineer related lined, derp)

  * Updated to match internal name change of Soldier's Sashimono/The Concheror (please make up your mind, valve)

  * Updated how the PlayerTaunts responses work across all classes, should hear them more often now without the need to spam the 'positive' voice command
  * Fixed a bug relating to Medic's domination responses

  * Added Jarate/Milk responses for Sniper
  * Added Jarate/Milk responses for Scout
  * Re-prioritised a response in rule KilledPlayerMeleeDisguisedSpy in Spy.txt

---

#### 0.7/RC1 `12.03.2011` ####
  * Added Sniper fight on cap entries to game\_sounds\_vo\_handmade.txt, so you can actually hear the lines now.

  * Added bases Spy.txt for diff purposes

  * Updated Spy's multi-kill responses to actually work now, was incorrectly set by valve

  * Added unused lines for getting a kill while disguised as a Spy

  * Added spooky whistle to positive voice menu for Spy
  * Attached unused PlayerTaunts to positive voice menu for Spy
  * Added unused lines for when you kill an Engineer as a Spy after he removes your Sapper (formerly unused as PlayerDisguisedTauntsSpy)
  * Added unused line for stab/sap and sap/stab as Spy
  * Added unused revenge lines for Spy
  * Added some more lines to revenge group for Spy
  * Added melee dares for Spy
  * Added ubercharge responses for Spy
  * Added unused lines for when you get a kill while disguised as a Spy
  * Added an unused line for killing a Sniper as a Spy
  * Added an unused line for dominating a Sniper as a Spy

  * ~ Included content in response\_rules.txt from the latest release version
  * Updated Scout ubercharge lines to be more appropriate

  * ~ Included content in tf.txt from the latest release version

  * Added automatic and manual assist lines for Medic
  * Modified responses to that killstreak and domination lines have a chance of playing on a normal kill as a Medic
  * Added responses for deploying Kritzkrieg ubercharge
  * Added melee dares for Medic
  * Updated ubercharge responses for Medic to be more appropriate

  * Moved Scout's fightoncap lines to their own response group for when you fire your weapon on a cappable control point

  * Finished what valve started by giving the Katana the Eyelander/Direct Hit taunt for Demoman/Soldier respectively; this was their original intention
  * Katana shares the Eyelander kill responses for Demoman

---

#### 0.6 `06.02.2011` ####
  * Updated Heavy's 'all of you are babies' etc response to only play if you are not using a melee weapon, so it doesn't mix with his melee dares. Use 'Battle Cry' voice command on anybody but a Heavy whilst holding a non-melee weapon to hear.

  * Added base Sniper.txt for diff purposes

  * Added a criterion to check if Sniper is unscoped
  * Added all Sniper payload responses to game\_sounds\_vo\_handmade.txt
  * Added all Sniper payload responses for Sniper, different versions of the same lines depending if you are scoped or not.

  * "Time to inform your next of kin" added back to getting >3 kills with Rocket Launcher, was removed by valve

  * Toned down Heavy melee swing responses to 50PercentChance (was 75PercentChance)

  * Added unused Domination and Revenge lines for Sniper to game\_sounds\_vo\_handmade.txt
  * Added unused generic Domination lines for Sniper when scoped (whispers), 75% chance
  * Added unused Revenge lines for Sniper, against certain classes. Lowered generic revenge lines to 30% chance
  * Made the above uninterruptible
  * Added a line for when you get an SMG kill, 30% chance
  * - Removed a previously added but unused criterion from response\_rules.txt
  * Made achievement responses uninterruptible for Heavy and Scout
  * Added a melee dare for Soldier

  * Added 3 lines for when you throw Mad Milk as Scout

  * Made regular domination lines uninterruptible for Sniper

  * Fixed Engineer's auto assist response
  * Fixed Engineer's Teleporter thanks response so it actually works now
  * Added achievement responses for Sniper, cannot be interrupted by pain
  * Added melee dare responses for Sniper
  * Added manual and auto assist responses for Sniper

  * Moved entries around in game\_sounds\_vo\_handmade.txt and added unused special weapon lines to it
  * Added special weapon lines for Sniper, use 'Battle Cry' voice command when holding a non-stock weapon
  * Added ubercharge response lines for Sniper
  * Added lines for when Sniper is scoped in and looking at an enemy ("Steady, steady..." etc)
  * Modified the Soldier and Spy kill responses to be split between normal shots and headshots, whispers only play on headshots, updated the Spy normal kills lines to play regardless of weapon and added a line to the Soldier headshot one
  * Added whisper revenge unused lines, for getting a scoped revenge kill as Sniper
  * Added unused lines to standard revenge response group for Sniper
  * Added a line for getting a kill with the Tribalman's Shiv
  * Added a normal and headshot line for killing a Heavy
  * Huntsman can now play killing spree lines and any normal, unscoped and non-headshot rifle kill lines
  * Made normal unused domination lines uninterruptible for Sniper
  * Updated the Scout double jump response to have a 10% chance of firing only after having fired a weapon, to help ninja Scouts, updated tf.txt to make this work
  * Added a bunch of criterions to help distinguish between Scout melees
  * Split up bat kill lines so that only the Bat and Sandman play bat related lines on kill, Basher, Candy Cane, Sun-on-a-Stick and Mackerel now have their own kill lines. All Scout melees use a generic, non-bat related kill response group, though.

  * Added vocal to Huntsman taunt (taunt04.vcd)
  * Added new vocal variant to Kukri taunt (taunt03\_v4.vcd)
  * Updated tf.txt to allow this
  * Rebuild scenes.image to allow this

  * Attached the unused PlayerTaunts responses to the positive voice menu option for Sniper


---

#### 0.5 `05.02.2011` ####
  * Added base Pyro.txt for diff purposes

  * Added criterion IsNotDominating
  * Used above criterion to make domination and revenge lines uninterruptible by pain/fire for Demoman, Engineer, Heavy, Pyro, Medic, Scout and Soldier
  * Updated EngyCritsReady to check for a recent kill
  * Added unused Pyro lines (only 4 :( )
  * Recycled Pyro lines for invulnerable response and melee dares
  * Attached the unused PlayerTaunts responses to the positive voice menu option for Pyro
  * Added automatic and manual assist response for Pyro

---

#### 0.4 `04.02.2011` ####
  * Modified the invulnerability responses to be more appropriate for Demoman
  * Added melee dare lines for Demoman
  * Attached the unused PlayerTaunts responses to the positive voice menu option for Demoman
  * Added kill responses for Demoman against Soldier (intentionally does not play if kill was with a sword [WeaponClassIsNotAxe](WeaponClassIsNotAxe.md), we'll assume he is sober when wielding a sword)
  * Added drunk line responses for when you swing your bottle after taking a drink from it (excluded the Frying Pan from this using a new WeaponIsNotFryingPan criterion)

  * Attached the unused PlayerTaunts responses to the positive voice menu option for Medic, Scout and Soldier

  * Added base Engineer.txt for diff purposes

  * Added automatic and manual assist lines for Engineer
  * Added melee dare lines for Engineer
  * Added a response for when you are holding your Frontier Justice and your mini sentry is killed for Engineer
  * Added Gunslinger punch and combo lines for Engineer
  * Added invulnerable responses for Engineer
  * Added unused revenge line for Engineer
  * Gunslinger now builds, moves and re-deploys much quieter than before (plays PlayerTaunts)
  * Attached the unused PlayerTaunts responses to the positive voice menu option for Engineer
  * Added a few criterion in response\_rules.txt to make all this happen
  * Added unused DefendOnThePoint line (well it's used, but inconsistently)

---

#### 0.3 `03.02.2011` ####
  * Removed superfluous/duplicate responses in Demoman.txt and Heavy.txt (Fists of Steel kill response now shares with base melee kill response, Bottle shares with Frying Pan, Pain Train with Frying Pan. Note: the responses work exactly the same as before, this is just cleaning up the code)
  * Fixed Frying Pan using the Bottle's response group
  * Scout now responds when invulnerable regardless of weapon fired
  * Added WeaponIsNotPainTrain criterion
  * Excluded Pain Train from Bottle taunt using above criterion
  * Modified Caber response to only fire on a kill (not 100% tied to a kill, but whatever)
  * Discovered 'damagecritical' context, applied to IsCritical criterion. Possibly related to critical hits, but seems to be related to any critical amount of damage

  * Added voice line to Equalizer taunt
  * Added voice line to Ubersawy taunt
  * Added voice line to Kritzkrieg taunt
  * Rebuilt scenes.image to allow for the above.

  * Added base Soldier.txt for diff purposes

  * Modified auto assist responses to 20PercentChance (was 10PercentChance)
  * Added Medic follow lines to Soldier
  * Added responses for when you are on a killing spree as a pocket Soldier (i.e. you're being healed by a Medic and you're on a killing spree)
  * Added ubercharge response lines for Soldier
  * Added melee dare lines for Soldier
  * Added manual and automatic assist line for Soldier
  * Added hat over heart lines for when you kill a Demoman as a Soldier

  * Added unused Direct Hit taunt vocals to melee kill response for Soldier.

  * Moved vocal Minigun firing responses into Heavy.txt
  * Fixed vocal Minigun firing responses to actually work
  * Added unused 'fight on point' lines to a new response rule for Heavy (PlayerGetOnPointHeavy); fire a weapon while on a cappable control point to hear.

  * Added 3 new criterion for detecting if player is not using vanilla weapons.
  * Added 'new weapon' lines for Heavy (4 lines for killing an enemy with a new Minigun, 4 lines for doing a 'Battle Cry' voice command while holding a new Minigun)

  * Added lines for killing an Engineer as a Heavy
  * Added same lines for doing a 'Battle Cry' on an enemy Engineer
  * Added BONK! not ready (invincible not ready) lines for Scout, (< or = 80 health, getting shot at while holding BONK!)
  * Added 2 more lines to Scout's melee dare response group
  * Added Bat domination lines for the Scout
  * Added a response for killing a Scout as a Scout
  * Added a response for killing a Pyro as a Scout
  * Added a criterion LoadoutIsDrink
  * Excluded Crit-a-Cola from playing any BONK! related lines.
  * Added lines for firing while under the effects of Crit-a-Cola
  * Added PostTired vocals for Crit-a-Cola
  * ~ Discovered a hard limit of rules/responses per file. Any higher than this will cause the game to crash.

  * - Removed critical hit criterion IsCritical as it is not related to actual critical hits
  * - Removed in-progress response from Soldier.txt based on above criterion
  * Fixed a typo in Scout.txt

  * Updated the Pyro and Scout kill responses for Scout

  * Undo a previous change that removed IsCritical criterion, as it is used for Caber explosion rule detection.
  * Added Sentry and Dispenser destroyed lines for Heavy

  * Added unused melee lines for Heavy, spoken in sequence
  * Added unused left/right melee lines to left/right voice command as there is no way to differentiate between the two in-game

  * Added criterion IsNotOnHeavy
  * Added 3 'unknown condition' lines to the battle cry when facing anybody but a Heavy.
  * Added 2 of those lines to KilledPlayerManyHeavy and KilledPlayerVeryManyHeavy, 1 each

  * Added the unused PlayerTaunts for Heavy
  * Added the final unused vocal line to the primary and secondary taunt for Heavy
  * Rebuilt scenes.image to accommodate the the vcd changes
  * Updated the Buffalo Steak Sandvich response to check for weapon mode instead of weapon class

  * Added base game\_sounds\_vo\_handmade.txt for diff purposes

  * -> Moved game\_sounds\_vo\_handmade.txt to correct directory

  * Added unused singing line to Payload offense response group
  * Added unused singing line to Payload defence response group
  * Added ?? ???????? (dasvidania) back to Heavy's "Thanks" voice command, was missing since beta
  * Updated game\_sounds\_vo\_handmade.txt.txt to allow for this
  * Rebuilt scenes.image to accommodate new vcd (Thanks04.vcd)

---

#### 0.2 `(02.25.2011)` ####
  * Added 1 unused domination line for scout (need to build vcds for other 2)
  * Added melee dare responses for Scout. Point at enemy with a melee weapon, do battle cry voice command to use.
  * Added prototype assist kill response system for Scout (kill >1 players, say voice command "Thanks", 50 percent chance of occurring)
  * Added double jump apex responses for Scout
  * Added a Criterion in response\_rules.txt to make it only fire when he's in the air, not when he's on the ground.
  * Excluded Skullcutter from the eyelander taunt
  * Fixed Frying Pan criterion to use correct name.
  * Frying Pan now has its own kill response rule - no more "bottle o' scrumpy" line.
  * Removed superfluous criterion in Demoman.txt melee kill rules

  * Modified Scout kill assist rule to be less prone to spamming. Can only be fired 1 in 20 seconds (in time with recent kill ticker) after a kill. This may need further tweaking.
  * Fixed the criterion WeaponIsScattergunDouble - somehow broken in previous revision.
  * Moved rules around to more appropriate areas within Scout.txt
  * Added achievement responses for Scout.
  * Added criterion for the Ullapool Caber
  * Added rule for a Caber explosion
  * Added some documentation to Demoman.txt
  * Added unused Bottle taunt to Caber
  * Added two voice lines to new Caber taunt

  * Added recompiled scenes.image to allow for taunt04\_v1.vcd and taunt04\_v2.vcd to work. Server admins: You will somehow need to force this file upon your clients for the new taunts to work. (You don't need to worry about the vcd files, just the scenes.image)
  * Added assist lines for Demoman. Say thanks after a kill.

  * Added a new criterion to response\_rules.txt "IsBeingHealed"
  * Added scout assist speech for when you get a kill while being healed. 10 percent chance, shares context with the manual assist speech (thanks after a kill). Has a delay of 2.5 seconds after the kill.
  * Removed superfluous IsDemoman/IsScout criteria on assist rules.
  * Added auto assist rule for Demoman, same as one in Scout.txt
  * Added base Heavy.txt for diff purposes.
  * Added responses for when you kill an enemy Medic whilst being healed by your own as a Heavy
  * Added achievement responses for Heavy
  * Added manual and automatic assist lines for Heavy
  * Added melee dare responses for Heavy
  * Added new criterion for Fists of Steel
  * Added vocal line relating to steel fists for when you get a Fists of Steel kill, shares context with normal melee kills.

---

#### 0.1 `(02.11.2011)` ####
  * Added ubercharge responses for Demoman, Scout and Medic
  * All Swords now use Eyelander taunt.
  * Swords play voice lines (special version for Demoman victim)

  * Heavy no longer speaks Sandvich lines when eating Dalokohs or Steak
  * Allowed for addition of separate responses for Steak/Dalokohs when eating
  * Added two voice lines to the Dalokohs as an example of above.

##### Undocumented in svn: #####
  * Added unused Ubercharge ready line for Medic.

MD5 checksum: 162ddf081de10dd229734bba83cce24a