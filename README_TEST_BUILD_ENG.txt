CULTURES: 8TH WONDER – RECONSTRUCTION TEST BUILD
=================================================

This is an early test build of the Cultures: 8th Wonder of the World reconstruction project.

This version is being shared for testing purposes only. The reconstruction is still under active development, so many features are unfinished, missing, or may not work correctly yet.

The main purpose of this build is to test the game, find bugs, crashes, incorrect behaviour, and differences compared to the original Cultures: 8th Wonder of the World.

WHAT'S INCLUDED
---------------
  cultures_reconstruction.exe   the game
  libc++.dll                    required runtime file
  libunwind.dll                 required runtime file
  libwinpthread-1.dll           required runtime file
  game.ini                      game configuration

Do not remove the included DLL files or game.ini. They are required for the game to launch correctly.

GAME DATA - REQUIRED
--------------------
This test build does NOT include any original Cultures: 8th Wonder of the World game assets.

You need your own copy of Cultures: 8th Wonder of the World to provide the required game data.

To set it up:

  1. Find the "DataX" folder inside your Cultures installation.

  2. Copy the entire "DataX" folder into this test build folder, next to
     cultures_reconstruction.exe.

     It should look like this:

       <this folder>\cultures_reconstruction.exe
       <this folder>\DataX\Libs\data0001.lib
       <this folder>\DataX\...

  3. Launch cultures_reconstruction.exe.

If your installation contains multiple numbered archives such as:

  data0001.lib
  data0002.lib
  data0003.lib
  ...

copy the entire Libs folder. The reconstruction will automatically detect the available archives.

IMPORTANT
---------
DataX must be a real copy of the folder.

Do not use a shortcut, symlink, or junction. If the game data cannot be loaded correctly, the game may start with a black window instead of reaching the menu.

If you do not want to copy the entire DataX folder, you can open game.ini and configure the path to your existing data0001.lib file using the provided use_data_file_9 option.

If the game starts with a black window or does not reach the menu, check:

  startup.log

The log should contain information about what went wrong during startup.

HOW TO LAUNCH
-------------
Double-click:

  cultures_reconstruction.exe

The easiest and recommended way to launch the test build is directly from its folder.

CURRENT STATE
-------------
This is NOT a finished replacement for the original game.

Some parts of the game already work, while many systems are still being reconstructed and tested.

Currently implemented and manually confirmed areas include:

  - world rendering
  - camera movement
  - object and unit selection
  - in-game interface
  - Human movement
  - several Human jobs and work behaviours
  - House and worker assignment
  - wood gathering

Many other systems are still incomplete or under development, including:

  - building production chains
  - warehouses and logistics
  - hunger and sleep
  - entertainment and religion
  - families
  - schooling
  - construction
  - roads and signposts
  - combat
  - vehicles
  - save/load
  - computer opponents (AI)
  - multiplayer

Because this is an early test build, expect missing features, incorrect behaviour, visual problems, unfinished systems, and crashes.

TESTING
-------
While playing, please pay attention to anything that behaves differently from the original Cultures: 8th Wonder of the World.

Especially report:

  - crashes
  - freezes
  - characters getting stuck
  - jobs not working correctly
  - buildings behaving incorrectly
  - missing animations
  - graphical problems
  - UI problems
  - incorrect sounds
  - objects appearing in the wrong place
  - anything that works differently from the original game

When reporting a problem, please describe what happened and what you were doing before the problem occurred.

Screenshots or videos are very helpful if the bug can be reproduced.

BUG REPORTS
-----------
This is an independent reconstruction project currently being tested.

Please report any bugs, crashes, missing features, or incorrect behaviour directly to the developer who provided you with this test build.

Thank you for helping test the reconstruction!