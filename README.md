Note this is the base Descent 3 source, v1.6 with no frills, no add ons, it has OSIRIS scripting properly bound, so its backwards compatable with all mods/missions from the last 27+ years since 1999 when Descent 3 was released.  This is a modernized 64-bit base on which to build.  The build uses scons.

https://scons.org/

to build

from msys2 console type:

scons -j$(nproc) build=release static=1


A full zip, create a working directory, then just unzip.  If you don't have msys2, minigw64 installed you can find them here:

https://www.msys2.org/
