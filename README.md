![logo](logo.gif "VVVVVV")

Notes on the Wii/GameCube port
------------------------------

This branch contains a port of [VVVVVV](https://github.com/TerryCavanagh/VVVVVV) to the Nintendo Wii and GameCube consoles.

This can be built using [devkitPro](https://devkitpro.org/wiki/Getting_Started), by following these instructions:

    cd desktop_version
    mkdir build && cd build
    cmake -DCMAKE_TOOLCHAIN_FILE="$DEVKITPRO/cmake/Wii.cmake" ..
    mv VVVVVV.elf boot.dol

Then, copy `boot.dol`, `icon.png`, `meta.xml` and the `data.zip` file (which you can get from the [Releases](https://github.com/mardy/VVVVVV/releases) page) to a new `/apps/VVVVVV/` folder in your SD card. Start the Homebrew channel in your console, and enjoy the game. :-)

Original README
---------------

This is the source code to VVVVVV, the 2010 indie game by [Terry Cavanagh](http://distractionware.com/), with music by [Magnus Pålsson](http://souleye.madtracker.net/). You can read the [announcement](http://distractionware.com/blog/2020/01/vvvvvv-is-now-open-source/) of the source code release on Terry's blog!

The source code for the desktop version is in [this folder](desktop_version).

VVVVVV is still commerically available at [thelettervsixtim.es](https://thelettervsixtim.es/) if you'd like to support it, but you are completely free to compile the game for your own personal use. If you're interested in distributing a compiled version of the game, see [LICENSE.md](LICENSE.md) for more information.

Discussion about VVVVVV updates mainly happens on the "unofficial" [VVVVVV discord](https://discord.gg/Zf7Nzea), in the `vvvvvv-code` channel.

Credits
-------
- Created by [Terry Cavanagh](http://distractionware.com/)
- Room Names by [Bennett Foddy](http://www.foddy.net)
- Music by [Magnus Pålsson](https://magnuspalsson.com/)
- Metal Soundtrack by [FamilyJules](https://link.space/@familyjules)
- 2.0 Update (C++ Port) by [Simon Roth](http://www.machinestudios.co.uk)
- 2.2 Update (SDL2/PhysicsFS/Steamworks port) by [Ethan Lee](http://www.flibitijibibo.com/)
- Additional coding by [Misa Kai](https://infoteddy.info/)
- Beta Testing by Sam Kaplan and Pauli Kohberger
- Ending Picture by Pauli Kohberger
- Localisations by [our localisation teams](desktop_version/TRANSLATORS.txt)
- With additional contributions by [many others here on github](desktop_version/CONTRIBUTORS.txt) <3
