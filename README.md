Antigravitaattori
=================

Multiplayer flying saucer racing game.

This version of the game is a fork of a fork -- in addition to the following changes, it has been modified to be built with MINGW on Windows.

 - translated to English
 - ported to libpng 1.6
 - ported to SDL 2.0
 - dropped autotools, simplified build system
 - support for game controllers (tested with wireless XBOX 360 controller)

## Requirements
 - SDL2 (mingw-w64-x86\_64-SDL2)
 - libpng (mingw-w64-x86\_64-libpng)
 - freealut (https://github.com/vancegroup/freealut)
 - libopenal (mingw-w64-x86\_64-openal)

## Building
Use `make` to build. Copy the data folder to the directory you have antigrav.exe in, and copy any necessary .dlls from your mingw installation into the directory as well. I.e. in addition to the libraries above, you will need the following for mingw:
 - libgcc
 - libstdc++
 - libwinpthread

The resulting application is portable.

## Binary
A hopefully working build of the program is available [here](https://adamfontenot.com/files/antigrav.tar.gz).
