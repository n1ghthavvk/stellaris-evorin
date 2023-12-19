Version 1.19.1
* Fixed missing localization for non-english languages.

Version 1.19.0
* Update to game version 3.10.*
* Updated "The Chosen One" Origin, it now adds 5% shroud delve cooldown reduction and its description is using the new localization features.
* Updated "Endeavour to Enlightenment" Origin, it now provides a 20% chance for leaders to retain their level instead of randomly adding common traits (this fires a new custom toast message) and it benefits agendas while leader improvements are removed. Added a 200% cost increase to hire new leaders. Updated its description to also use the new localization features.
* Updated "Eldest Sibling" Origin, ensuring compatibility for all planet classes from Planetary Diversity (up to its release on 10th December 2023).
* Fixed localization bug reported by user "idallo" on GitHub. Thank you!

Version 1.18.0
* Update to game version 3.8.*
* Updated "Eldest Sibling" Origin, it now prefers to spawn primitives on empty habitable world, if any are present.
* Updated "Endeavour to Enlightenment", it now uses the new leader modding interfaces instead of hand-written code and its effects have been improved, to compensate for leaders getting buffed in vanilla.
* Updated "The Chosen One" Origin, it will now prevent the Chosen One from gaining negative traits. The overwritten Utopia event has been updated to the newest version.

Version 1.17.0
* Update to game version 3.7.*
* Updated "Eldest Sibling" Origin, it is now fully compatible with Hive Minds and may spawn them as a random pre ftl empire (10%). Added a small chance for your species to mutate into a hive mind or out of it (10%), as well as a slightly bigger chance (20%) to live above or below ground instead.
* Updated "Eldest Sibling" Origin, ensuring compatibility for all planet classes from Planetary Diversity (up to its release on 15th March 2023)

Version 1.16.1
* Fixed "The Chosen One" Origin, which had still kept the old game version 3.5 logic in the overwritten event (which allowed access to the Shroud earlier than it should've).

Version 1.16.0
* Update to game version 3.6.*
* Updated "Eldest Sibling" Origin, ensuring compatibility for all planet classes from Planetary Diversity (up to its release on 2nd December 2022)

Version 1.15.0
* Update to game version 3.5.*
* Updated "Eldest Sibling" Origin, ensuring compatibility for all planet classes from Planetary Diversity (up to its release on 23th September 2022)

Version 1.14.2
* Updated "Eldest Sibling" Origin, it no longer spawns primitives on planets with an orbital station (starting deposits will no longer be lost in some cases).
* Fixed "Eldest Sibling" Origin, it no longer crashes when choosing primitives of your own species.

Version 1.14.1
* Updated "Endeavour to Enlightenment" Origin, the initial ruler now also gains an additional trait.
* Fixed "Endeavour to Enlightenment" Origin, preventing popups at the start, as well as for leaders in the leader pool.
* Fixed "Out of Sight, Out of Mind" Origin, the used icon was moved due to the new vanilla origin.

Version 1.14.0
* Update to game version 3.4.*

Version 1.13.1
* Fixed "Eldest Sibling" Origin, correcting the "invisible" planet when using the 1+1 option at the start, as well as adding missing compatibility for the Reef planet class.

Version 1.13.0
* Update to game version 3.3.*
* Updated "Endeavour to Enlightenment" Origin, now adds an additional random trait to all starting and recruited leaders
* Fixed Chinese translation by [url=https://github.com/ccinv]ccinv[/url]

Version 1.12.0
* Update to game version 3.2.*
* Added Chinese translation by [url=https://steamcommunity.com/id/RanshenZ]Ranshen[/url]

Version 1.11.3
* Updated Spanish translation by [url=https://steamcommunity.com/profiles/76561198806487951]Alexander[/url]

Version 1.11.2
* Fixed "Back to the Future" Origin, deposit hadn't been updated to 3.1 syntax yet.

Version 1.11.1
* Added Spanish translation by [url=https://steamcommunity.com/profiles/76561198806487951]Alexander[/url]

Version 1.11.0
* Fixed missing thumbnail update

Version 1.11.0
* Update to game version 3.1.*
* Added "Endeavour to Enlightenment" Origin, which allows Leaders to gain more than one trait through leveling up
* Updated "Ecosystem Integration" Origin, now also starts with two factory districts
* Updated "The Chosen One" Origin, now adds a random beneficial ruler trait instead of Erudite and adds +50% Tech Progress to Psionic Theory.
* Updated "Eldest Sibling" Origin, adding compatibility for all new planet classes from Planetary Diversity (up to its release on 18th September 2021), as well as allowing any randomly generated worlds to use the normal and rare planet classes from it (and not just the vanilla ones).
* Fixed "Out of Sight, Out of Mind" Origin, Gestalt Consciousness empires can no longer gain access to the Trade Value result
* Fixed all Origins using the game_start.2 event to instead use an on_game_start effect (improves compatibility)

Version 1.10.0
* Updated "Legacy of Nine Suns" Origin, now other empires can discover the supermassive black hole as they first enter the system and be able to construct a Birch World on it (if Gigastructural Engineering is active and they can claim the system).

Version 1.9.0
* Update to game version 3.0.*
* Fixed "Eldest Siblings" Origin, adding compatibility for all new planet classes from Planetary Diversity (up to its release on 23th April 2021)

Version 1.8.0
* Fixed "Eldest Siblings" Origin, adding compatibility for all new planet classes from Planetary Diversity (up to its releases from 3rd and 9th March 2021 respectively)
* Fixed "Eldest Siblings" Origin, removing reliance on a global event target which prevented it from working in multiple instances

Version 1.7.2
* Migrated to GitHub

Version 1.7.1
* Fixed "Eldest Sibling" Origin, one dead file (ori_eldest_sibling) bloating the mod size has been removed
* Fixed "Legacy of Nine Suns" Origin localisation

Version 1.7.0
* Update to game version 2.8.*

Version 1.6.0
* Update to game version 2.7.2
* Updated "Legacy of Nine Suns" Origin, the supermassive black hole is now a possible candidate for Birch Worlds, if Gigastructural Engineering is enabled
* Updated "Out of Sight, Out of Mind" Origin, it now starts the Subterranean Civilization event chain approximately a month later (this allows players more time to build up science production for the special projects)
* Updated the Steam Workshop Icon, removing the outdated reference to the "Shattered Ring" Origin and replacing it with a picture from the "Legacy of Nine Suns" Origin
* Fixed "Eldest Siblings" Origin, adding compatibility for all new planet classes from Planetary Diversity, as well as improving the code by refactoring 2000 lines into 700
* Fixed "Back to the Future" Origin, relic moons were spawning without their planetary deposits when Planetary Diversity was enabled (thanks to Ragnin for reporting the issue concisely)

Version 1.5.1
* Fixed "Eldest Sibling" Origin compatibility with all planet classes from Planetary Diversity, as well as Planetary Diversity - Exotic Worlds.

Version 1.5.0
* Update to game version 2.6.3
* Fixed the 3 Origins that require solar system initializers to work correctly with the changed mod interface in 2.6.3
* Fixed "Eldest Sibling" Origin, the descriptor was not displaying correctly

Version 1.4.0
* Added "Walking On Eggshells" Origin, a challenging start, which will have a Voidspawn (vanilla event chain) grow inside the player's planet until it cracks the home world open and takes over the system. At the start of the game the player can pick from many options to decide how soon the event happens (between 1 and 100 years).
* Added support for all languages. But for now they'll be displaying english only, because I do not want to use google translate and ruin every second sentence.
* Updated "Eldest Sibling" Origin, it will now let the player choose if they want to spawn primitives of their own species or randomly generated ones, as well as how many and what mix of them if they pick two instead of one. Machine empires are no longer allowed to pick this Origin, but Hive Minds can
* Fixed "Eldest Sibling" Origin, it will now always spawn primitives
* Fixed "Fratricide" Origin, it was impossible to get picked by Fanatic Xenophobes and incorrectly possible to be picked by Fanatic Pacifists
* Fixed "The Chosen One" Origin being able to be picked by Machine Empires

Version 1.3.2
* Updated "Eldest Sibling" Origin, spawning the primitives randomly on any fitting planets and it's now possible to use any system initialiser in addition to the origin.
* Updated "The Chosen One" Origin, allowing the player to research Psionic Theory right from the start and the ruler now starts with the Erudite trait instead of Charismatic.
* Fixed some forgotten defines (thanks to joakim.westergaard for pointing them out)

Version 1.3.1
* Fixed "Eldest Sibling" Origin, now the primitives are of the empire's own species

Version 1.3.0
* Removed DLC requirements from all Origins
* Added "Eldest Sibling" Origin, a start with two Primitives in the home system
* Updated "Fratricide" Origin, adding a Xenophone, Non-Pacifist ethic requirement to it
* Updated Icons and Pictures of all Origins to use more assets already present (but unused) in the vanilla files

Version 1.2.0
* Added "The Chosen One" Origin, where the initial ruler starts at level 10 and has both the Chosen One as well as the Charismatic trait
* Fixed "Back to the Future" spawning Relic Worlds as guaranteed habitable worlds instead of random ones

Version 1.1.0
* Added "Out of Sight, Out of Mind" Origin, with a Subterranean Civilization (vanilla event chain) on the empire's home world
* Added "Legacy of Nine Suns" Origin, an eye-candy start with nine stars

Version 1.0.0
* Update to game version 2.6.0
* Removed all vanilla Origins that have been added in the Federations Update
* Removed "Debris Dwellers" Origin, due to issues getting its Habitable World sprite to work
* Added "Ecosystem Integration" Origin, a Hive World start
* Fixed "Remnants II" -> "Back to the Future" Origin, integrating it with the new Origin system
* Fixed "Fratricide" Origin, integrating it with the new Origin system

Version 0.2.0
* Added "Void Dwellers" Origin, a start on a Habitat
* Updated "Shattered Ring" Origin, adding a planetary deposit for 2 of each rare resource to it, allowing the player to more easily expand into districts that require them as upkeep
* Fixed "Shattered Ring" Origin, now starting with two ruined ring sections instead of colonizable ones

Version 0.1.0
* Added "Fratricide" Origin, a start with an additional, uninhabited Tomb World
* Added "Remnants I" Origin and "Remnants II" Origin, two different Relic World starts
* Added "Resource Consolidation", a Machine World start
* Added "Shattered Ring", a Ringworld start
* Added "Debris Dwellers", an Asteroid start
