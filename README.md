# Cube 2: Sauerbraten

## Links

First of all, welcome to Cube 2: Sauerbraten! To start off, if you are looking for help with the game itself, refer to the [**Documentation**](#documentation) below. Here are some places of interest on the internet, which are related to _Cube / Cube 2: Sauerbraten_.

*   [Cube and Cube 2 Engines](http://cubeengine.com/): Start Page for the Cube Engine series.
*   [Cube 2: Sauerbraten](http://sauerbraten.org/): The Sauerbraten FPS (First Person Shooter) Homepage.
*   [Quadropolis](http://quadropolis.us/): Online Cube Engine community, with user made maps, mods, and scripts.
*   [Sauerbraten IRC Channel](irc://irc.quakenet.org/sauerbraten): Online public chat with Cube developers, supporters and fans, via the [QuakeNet IRC Network](http://www.quakenet.org/).
*   [Cube Forums](http://cubeengine.com/forum.php): If after reading the documentation and wiki you still have any questions, you can try _searching_ the forums. If your question isn't answered there, you can try posting to a relevant thread, or creating your own, being sure to supply a good description of your problem, and your operating system/hardware/software setup, while refraining from wild accusations.

## Documentation

Cube 2: Sauerbraten is a multiplayer/singleplayer FPS freeware game project. The source code for the engine used in these games is Open Source (ZLIB licence, read the "License" section below carefully before starting ANY kind of project based on this engine).

You will want to read (roughly this order):

*   [Game](docs/game.html): Information on gameplay.
*   [Config](docs/config.html): How to run the game, configure it for your machine, and extend it with scripts.
*   [Editing Tutorial](docs/editing.html): A guide to making maps.
*   [Editing Reference](docs/editref.html): Map making reference.
*   [Models](docs/models.html): How to put models into the game.
*   [History](docs/history.html): For seeing latest changes.
*   [Example RPG Game Information](docs/rpg.html): Information on running, building, or scripting the example RPG game.

## The Wiki

In addition to the documentation provided, the wiki has a lot of useful information for working with the game and engine, contributed by the community which elaborates and breaks alot of the information down into more digestable chunks. This is just provided a short rundown of the most useful topics to new players, and those looking for quick readable information. For more go visit the [Cube Wiki](http://cubeengine.com/wiki/).

*   [Beginners Guide](http://cubeengine.com/wiki/Beginners_Guide): Go through the steps to get up and running.
*   [Frequently Asked Questions](http://cubeengine.com/wiki/FAQ): Get the answers to some commonly asked questions, like; "_The game runs very slowly, how can I fix it?_", "_Why is the game behaving strangely?_", and "_How do I fix the 'Hall of Mirrors' effect?_".
*   [Performance Guide](http://cubeengine.com/wiki/Performance_Guide): Things you can try to make the game either run faster or look better on your machine.
*   [Older Stuff](http://quadropolis.us/taxonomy/term/21): From Quadropolis.
*   Some [old](docs/dev/wikistuff.html) random documentation bits from our previous wiki that don't have a place yet.

## Current Features

Cube 2: Sauerbraten is an open source project, and maintains constant development, yet it is very feature-rich and playable as a game. What follows is a list of the most prominent features.

### Game Features

*   Oldskool fast & intense gameplay (read: similar to Doom 2 / Quake 1).
*   Many multiplayer gameplay modes, most in teamplay variants as well: deathmatch, instagib, efficiency, tactics, capture (domination/battlefield style), CTF (capture the flag), coop edit (!).
*   Masterserver & ingame server browser.
*   Lag-free gameplay experience.
*   Two singleplayer modes: DMSP (fight a monster invasion on any DM map), classic SP (progression driven SP like other games)
*   7 weapons tuned for maximum satisfaction: double barrelled shogun, rocket launcher, machine gun, rifle, grenade launcher, pistol, fist.

### Engine Features

*   6 directional heightfield in octree world structure allowing for instant easy in-game geometry editing (even in multiplayer, coop edit).
*   Rendering engine optimized for high geometry throughput, supporting hardware occlusion culling and software precomputed conservative PVS with occluder fusion.
*   Lightmap based lighting with accurate shadows from everything including mapmodels, smooth lighting for faceted geometry, and fast compiles. Soft shadowmap based shadows for dynamic entities.
*   Pixel and vertex shader support, each model and world texture can have its own shader assigned. Supports normal and parallax mapping, specular and dynamic lighting with bloom and glow, environment-mapped and planar reflections/refractions, and post-process effects.
*   Robust physics written specifically for this world structure.
*   Loading of md2/md3/md5/obj/smd/iqm models for skeletal and vertex animated characters, weapons, items, and world objects. Supports animation blending, procedural pitch animation, and ragdoll physics for skeletally-animated characters.
*   Network library designed for high speed games, client/server network system.
*   Small but complete configuration/scripting language.
*   Simple stereo positional sound system.
*   Particle engine, supporting text particles, volumetric explosions, soft particles, and decals.
*   3d menu/gui system, for in-world representation of choices.

## Credits / Authors

<div class="credits">Programming</div>

*   _Wouter "Aardappel" van Oortmerssen_: A lot of the general code, and the original concept and design. ([website](http://strlen.com/))
*   _Lee "eihrul" Salzman_: ENet networking library, *nix ports, and a lot of the general code, especially rendering/lightmaps/physics related. ([website](http://sauerbraten.org/lee/))
*   _Mike "Gilt" Dysart_: General programming, especially editing/physics related.
*   _Robert "baby-rabbit" Pointon_: GUI, particle rendering, and movie recording code, MacOSX porting. ([website](http://www.fernlightning.com/))
*   _Quinton "quin" Reeves_: Bots/AI code. Asissts with community management, documentation/wiki, and development. ([website](http://www.redeclipse.net/))

<div class="credits">Additional Code</div>

*   _Julian Mayer_: MacOSX ports.
*   _Adrian "driAn" Henke_: MD3 code.
*   _Jerry Siebe_: Geometry rendering optimisations.

<div class="credits">Level Design</div>

*   _Kurt "kdoom" Kessler_: A bunch of DM/capture maps, k_rpg1.
*   _Shane Nieb_: academy, authentic, autumn, bt_falls, c_valley, complex, curvy_castle, flagstone, garden, hallo, hashi, island, justice, nevil_c, nmp4, nmp8, nmp9, ot, park, shipwreck, turbine
*   _John "metlslime" fitzgibbons_: metl* maps.
*   MitaMan: singleplayer episodes
*   With additional maps by: Aardappel, driAn, Gilt, voot, Bryan "KillHour" Shalke, staffy, sparr, JCDPC, ZappaZ, RatBoy, Fanatic, rocknrol, KaiserTodretter, BlikjeBier, wurfel, aftasardem, Lazy [HUN], Gregor Koch, Junebug, Gabriele "Blindabuser" Magurno, PainKillAH, MeatROme, TUX, Mayhem, mIscreant, schmutzwurst, Kal, DairyKing, Hero, WahnFred, jonlimle, t-chen, viruz, Snowy, 4t3one, sinsch, Meister, Fatum, RaZgRiZ, SirAlex, Chris_0076, HeWho, Majikal, Suicizer, Ardelico, Cooper, Zeronic, Skur, flubz0r, SomeDude, Redon, MisanthropiX, Doko, Destroyer, TomekGNO, Kretren, Drakker, KI113R, rabe, SuperMan, Crap_I'm_Dead, b4lkLu, Windecker, Justin, and others.

<div class="credits">Art / Content</div>

*   _John "Geartrooper" Siar_: Mr. Fixit, Ironsnout, RPG characters, monsters, new hudguns and vweps.
*   _Gabriele "Blindabuser" Magurno_: Logos, loading screen, announcer voices.
*   _MakkE_: Mapmodels, old hudguns, items.
*   _Dietmar "dcp" Pier_: Mapmodels, old hudguns.
*   _DarthVim_: Old hudguns.
*   _Shane Nieb_: Textures, Mapmodels, Skyboxes.
*   _Sock_: The egyptian & tech texture sets ([website](http://www.planetquake.com/simland)).
*   _Iikka "Fingers" Keranen_: The ikbase ik2k texture sets ([website](http://www.digital-eel.com/surface)).
*   _Lunaran, Gibbie, Gregor Koch, Jésus "aftasardem" Maia, MitaMan, and philipk_: Normalmapped texture sets.
*   _SkiingPenguins_: Skyboxes.
*   Additional art by: metlslime (textures), Than (textures), Remedy Entertainment Ltd (textures), Seth & Ulrich Galbraith (GPL models), Brian "EvilBastard" Collins, Conrad, Magarnigal, Psionic, James Green, Andreas Möller, Ryan Butts & Jeramy Cooke (md2 models), KaiserTodretter (items), Tentus (mapmodels), Kurt Kessler (mapmodels), Philip Klevestav (textures), leileilol/OpenArena (GPL bullet hole decal).

<div class="credits">Sound / Music</div>

*   _Marc "Fanatic" A. Pullen_: Soundtrack.

<div class="credits">Other</div>

*   _Kristian "sleepwalkr" Duske_: website / messageboard, hosting, master server.
*   _Pushplay_: Documentation help.
*   _The SDL team_: For their libraries ([website](http://www.libsdl.org/)).

## License

The game is freeware, you may freely distribute the archive and/or installer _unmodified_ on any media. You may re-compress using different archival formats suitable for your OS (i.e. zip/tgz/rpm/deb/dmg), any changes beyond that require explicit permission from the developers.

You may play Cube 2: Sauerbraten for any purpose as long as you don't blame the authors for any damages incurred.

If you want to produce new content with the Cube 2 Engine, you have to be aware that the source code may be Open Source, but the game and the media it consist of have their individual licenses and copyrights. This means that you have roughly 3 options:

*   You may produce new content for the "Sauerbraten" game, for example as a _custom map_ (.ogz/.cfg/textures etc). Contributing _content_ to the original game is most welcome, and the most productive way of working with the community.
*   If you want to create your own gameplay beyond what you can do with a map, the best way to do this is as a "mod" (same as above, but with new executable that incorporates your gameplay), that _requires an existing install_, and _installs only the new files_ you created in parallel to the existing files.
*   If you insist on making a standalone game based on Cube 2, do realize that _only the sourcecode_ is yours to use freely (if you abide by the ZLIB license, see below), while the media is _not_. You can't simply redistribute the entire package with your modified files, as the majority of game media is not yours to use freely (it is made by many authors with a variety of licences and copyright restrictions). Unless you have explicit permission from the authors, or the readme says explicitly "may be used for any purpose" or similar language, it will be illegal to include in your standalone game based on the engine (you may not assume that just because a file has no explicit license, that it is free of copyright). Therefore, if you wish to produce a standalone game, be prepared to make many of the maps, models, textures, sounds etc from scratch yourself.

In this sense Cube 2: Sauerbraten is similar to games like Quake (its code is Open Source, but its media is not), it is a game that is meant to be added to, not copied and used as a template. Sauerbraten is not meant to be a quick game creation kit, it is a game.

If you wish to use the source code (ZLIB license) in any way, read the src/readme_source.txt file carefully.
