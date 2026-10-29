# swes-recompiled
Recompilation project for Star Wars Battlefront Elite Squadron
Running on OpenGL 3.3 and statically recompiled code that has been heavily modified to run on Windows systems. This recompilation aims to bring modern features to Elite Squadron, while preserving the game as the original hardware ages. This project also aims to fully be backwards compatible with original hardware when it comes to network functionality. All changes made to the game that exclude native PSP/PS Vita players will not be implemented unless the offending changes can be avoided by those users. (Such as servers with 32/64 bots, but don't allow original clients such as the PSP to join.)

You will need your own USA (ULUS-10390) copy of Elite Squadron and to extract the PSP_GAME folder to the same directory as the provided executable.
Change your keybindings and other settings inside of the .ini file provided.

# What Works
- Mouse and keyboard input implemented
- Full multiplayer functionality over LAN/OpenSpy
- Unlocked framerate/resolution controls (see the .ini file)
- Support for Xbox 360/One controllers built-in
- Full game should be playable from start to finish but isn't 100% tested. Please report bugs.
- Dedicated server can host one-zone maps such as Bespin Ground, Bespin Space, etc. For ground to space, see below.

# What doesn't work
- Dedicated server cannot host ground to space maps yet, as the logic is broken.
- AdHoc is replaced with LAN, so you will not be able to play via AdHoc with a real PSP/Vita. This functionality will not be implemented.

# Source Code?
Will be provided when core functionality is feature complete. This includes the dedicated server with space to ground maps and full native keyboard integration. I do not want people forking this and building off of incomplete builds.
