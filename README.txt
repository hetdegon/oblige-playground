This is a playground repository where I play around with OBLIGE, by Andrew Apted, in order to see how further I can push it while playing around.

Features more rooms layouts, prefabs and testing with expanding sizes, heights, in order to make formal modules for more customization and submit them to the master OBLIGE repository when they are properly baked.

Maps generated with massive map module will not run (or so does the BSP generator say) on vanilla Doom.
I might add options to have it cap at the highest safe value if anyone asks.

Most changes are being oriented towards zdoom/gzdoom/zandronum at the moment. Prefabs with png textures for the 3D ports are on the way.

This is not a formal port, however, so expect weird rooms and textures from time to time as changes land in here.

Building process and C part hasn't changed so far, so using the executables from regular OBLIGE will work with the changes here.

The attic/web folders from the official repository have been excised to keep downloads and syncs faster.

Hetdegon -- December 2014


Here is the official OBLIGE readme verbatim for full reference of OBLIGE's doings and operations.


OBLIGE 6.10-RC1
===============

by Andrew Apted.  July 2014


INTRODUCTION

  OBLIGE is a random level generator for various classic FPS
  games, such as DOOM II and QUAKE (with more in development).
  The goal is to produce good levels which are fun to play.

  The planned features are:

    * high quality levels, e.g. outdoor areas and caves!
    * easy to use GUI interface (no messing with command lines)
    * built-in node builder, so the levels are ready to play
    * uses the LUA scripting language for easy customisation
    * DOOM, Heretic, Hexen and Quake support!


  Please visit the web site for complete information:

    http://oblige.sourceforge.net/


WHAT'S NEW?

  See the file CHANGES.txt for the list of changes.


QUICK START GUIDE

  First, unpack the zip somewhere (e.g. My Documents).  Make sure
  it is extracted with folders, and also make sure the OBLIGE.EXE
  file gets extracted too (at least one person had a problem where
  Microsoft Windows would skip the EXE, and he had to change some-
  thing in the control panels to get it extracted properly).

  Double click on the OBLIGE icon to run it.  Select the game in
  the top left panel, and any other options which take your fancy.
  Then click the BUILD button in the bottom left panel, and enter
  an output filename, for example "TEST" (without the quotes).

  OBLIGE will then build all the maps, showing a blueprint of each
  one as it goes, and if everything goes smoothly the output file
  (e.g. "TEST.WAD") will be created at the end.  Then you can play
  it using the normal method for playing mods with that game (e.g.
  for DOOM source ports: dragging-n-dropping the WAD file onto the
  source port's EXE is usually enough).


COPYRIGHT and LICENSE

  OBLIGE Level Maker

  Copyright (C) 2006-2014 Andrew Apted, et al

  OBLIGE is free software; you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published
  by the Free Software Foundation; either version 2 of the License,
  or (at your option) any later version.

  OBLIGE is distributed in the hope that it will be useful, but
  WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this software.  If not, please visit the following
  web page: http://www.gnu.org/licenses/gpl-2.0.txt


CONTACT DETAILS

  Website: http://oblige.sourceforge.net/

  Forum: http://oblige.sourceforge.net/forum/

  Email: <ajapted@users.sf.net>
