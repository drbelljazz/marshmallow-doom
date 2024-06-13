![Icon](http://marshmallowdoom.com/images/newlogo-halfsize.jpg)

# It's Done.

This repository is now archived and marked as read-only.  Marshmallow Doom is as "done" as it is going to get.  Luckily it runs consistently stable and the bots are fun as hell, so it is in the perfect state to just leave it be.  It was a fun adventure into programming but the code is amateurish and would likely make any real programmer sick just by looking at it.  Do not bother trying to compile this project as I guarantee that it will be a frustrating waste of your valuable time.  

My primary discipline is and always has been music, so check out my YouTube channel where I produce unique remixes of classic PC game music: https://www.youtube.com/channel/UCt5q-mzscR6w1q9Tm7y_oKQ

Thanks to anyone who contributed feedback or bug reports.  There will be no more updates or code merges but you can still download and play it at http://www.marshmallowdoom.com

## Synopsis

Marshmallow Doom is a source port which lightly sweetens classic Doom gameplay with new additions such as dynamic gameplay-driven music, cooperative bot players, persistent player stats, enhanced blood and gore, treasure items, new difficulty levels, customizable sandbox battles, a much-improved multiplayer experience, and more.

Marshmallow Doom is a fork of the Crispy Doom source port. Itself being a fork of Chocolate Doom, Crispy Doom adds features such as 640x400 resolution, colored HUD text, removal of static engine limits, translucency, free vertical looking, jumping, and other modern improvements.  Marshmallow Doom greatly expands on this same ethos of a lightly-sweetened-yet-still-classic Doom gameplay experience.

## Features

Here is a partial list of Marshmallow Doom's new features:

- Dynamic music soundtrack that morphs based on the player’s in-game experience, taking Bobby Prince’s original soundtrack to a whole new level
    
- Re-balanced multiplayer experience adding modern features such as progressive weapon loadout, dropping ammo for squad mates, conserved item pickups, weapons stay, friendly fire on/off, and more
    
- Bots available for cooperative or deathmatch games
    
- Treasure mode helps give Doom an even more classic vibe like that of Commander Keen or Wolfenstein 3D
    
- Sandbox mode allows the player (or multiple players in a network game) to build their own custom battles in any map
    
- Monster upgrades can give any old map a new challenge, even repopulating Doom maps with Doom II monsters
    
- New skill levels Ultra Violence 2.0 and Nightmare 2.0 utilize monster upgrading to create an entirely new standard for Doom’s difficulty
    
- Inventory system allows the player to store items for future use, such as radsuits, invisibility, portable medkit, and more
    
- Both Doom and Doom II IWADs can be combined so that music, sound, and graphics from both games can be used
    
- Enhanced blood, gore, and epic boss deaths
    
- The invisibility powerup now makes the player truly invisible to enemies, introducing a stealth tactic to help the player better survive any Doom level
    
-  Overplayed songs such as those from MAP01, E1M1, and intermission songs can be blacklisted, where an alternate song is randomly selected in its place
    
- Player stats such as total kills and accuracy are tracked by the player profile
    
- Various monster and weapon mutators
    
- Most new options are quickly accessible via the player’s HUD datapad, without having to tediously dig into Doom’s options menus
    
- All preferences are saved to disk for future sessions, and a separate server.cfg configuration file is available for multiplayer-specific game settings
    
For the full documentation, see the [wiki](https://www.chocolate-doom.org/wiki/index.php/Marshmallow_Doom).  (Alternate link [here](https://doomwiki.org/wiki/Marshmallow_Doom))

## Download

Download the latest Windows binary at http://www.marshmallowdoom.com/downloads/marshmallow79.zip


## News Archive

### Feb 21, 2021

The project has come a long way in one year!  

Special thanks to everyone on the Doomworld forums who tested the game and presented bugs and feature requests!  

If you would like to test the latest Windows build, you may refer to this forum thread for links as well as discussion:

https://www.doomworld.com/forum/topic/119898-who-wants-to-test-the-latest-build-of-marshmallow-doom/

You may also try compiling this source code for your own operating system, such as Linux.  If you do give this a try, 
let us know in the discussion how it goes! 

Happy fragging! 

### May 5, 2020

We now have about 98% of the project re-implemented in this new project.  Only a few features have been omitted as they were previously very poorly implemented into the Doom code.  These features that were skipped are:

- Sprint
- Extra text output line
- Flashlight
- Skill cheat (now using Crispy's version)

Now it is time for testing, testing, and more testing before any releases.  

### April 30, 2020

Up until now Marshmallow Doom has been written and compiled in Microsoft Visual Studio 2012.  This was not ideal as this has made it nearly impossible to port the code to other platforms.  

Finally, the code has been moved into a new project that compiles with MinGW, and is also properly tracked using Git.  

As of now, only about one-third of Marshmallow Doom's features have been re-implemented in the new project, but forward progress is being made every day.  You can check each commit comment to see what has been implemented.

Stay tuned!

## Documentation

 * **[Website](http://www.marshmallowdoom.com)**
 * **[Wiki](https://www.chocolate-doom.org/wiki/index.php/Marshmallow_Doom)**
 * **[Wiki (alternate)](https://doomwiki.org/wiki/Marshmallow_Doom)**
 * **[FAQ](http://marshmallowdoom.com/marshmallow-wp/faq/)**

## Versioning

In true Doom fashion, the first release was version 0.666, and they have progressed from there.  Now that the project is being developed in a more organized fashion, version numbers will likely be given more thought.

The upcoming version release (which will be the first public build of this new project) will have the letter "M" which stands for MinGW, the new compiler used from here on out.

## Contact

Marshmallow Doom is maintained by [Douglas R. Bell](http://douglasbellmusic.com). (aka JT_Marshmallow)  Contact email address: [drbelljazz@gmail.com](mailto:drbelljazz@gmail.com)

Please report any bugs, glitches or crashes that you encounter to the GitHub [Issue Tracker](https://github.com/drbelljazz/marshmallow-doom/issues).

## Legalese

Doom is © 1993-1996 Id Software, Inc.; 
Boom 2.02 is © 1999 id Software, Chi Hoang, Lee Killough, Jim Flynn, Rand Phares, Ty Halderman;
PrBoom+ is © 1999 id Software, Chi Hoang, Lee Killough, Jim Flynn, Rand Phares, Ty Halderman,
© 1999-2000 Jess Haas, Nicolas Kalkhof, Colin Phipps, Florian Schulze,
© 2005-2006 Florian Schulze, Colin Phipps, Neil Stevens, Andrey Budko;
Chocolate Doom is © 1993-1996 Id Software, Inc., © 2005 Simon Howard; 
Chocolate Hexen is © 1993-1996 Id Software, Inc., © 1993-2008 Raven Software, © 2008 Simon Howard;
Strawberry Doom is © 1993-1996 Id Software, Inc., © 2005 Simon Howard, © 2008-2010 GhostlyDeath; 
Crispy Doom is additionally © 2014-2019 Fabian Greffrath;
all of the above are released under the [GPL-2+](https://www.gnu.org/licenses/gpl-2.0.html).

SDL 2.0, SDL_mixer 2.0 and SDL_net 2.0 are © 1997-2016 Sam Lantinga and are released under the [zlib license](http://www.gzip.org/zlib/zlib_license.html).

Secret Rabbit Code (libsamplerate) is © 2002-2011 Erik de Castro Lopo and is released under the [GPL-2+](http://www.gnu.org/licenses/gpl-2.0.html).
Libpng is © 1998-2014 Glenn Randers-Pehrson, © 1996-1997 Andreas Dilger, © 1995-1996 Guy Eric Schalnat, Group 42, Inc. and is released under the [libpng license](http://www.libpng.org/pub/png/src/libpng-LICENSE.txt).
Zlib is © 1995-2013 Jean-loup Gailly and Mark Adler and is released under the [zlib license](http://www.zlib.net/zlib_license.html).
