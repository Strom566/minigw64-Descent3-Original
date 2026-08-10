Note this is the base Descent 3 source, v1.6 with no frills, no add ons, it has OSIRIS scripting properly bound, so its backwards compatable with all mods/missions from the last 27+ years since 1999 when Descent 3 was released.  This is a modernized 64-bit base on which to build.  The build uses scons.

https://scons.org/

to build

from msys2 console type:

scons -j$(nproc) build=release static=1

You need to copy over the files from the builds directory over your Descent 3 installation so be sure you make a backup of Descent 3, and copy it to another directory before you start copying over files from the base game.

For release
Drive letter:\working directory\Descent3-main\builds\mingw\release\stage

For debug

Drive letter:\working directory\Descent3-main\builds\mingw\debug\stage


A full zip, create a working directory, then just unzip.  If you don't have msys2, minigw64 installed you can find them here:

https://www.msys2.org/
