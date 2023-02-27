# Muchi Muchi Pork MAME Layout file

- Original art by CAVE Interactive Co., Ltd.
- Design by baf
- Huge thanks to Olifante for creating the Pink Sweets overlay. This is based on that, memory locations updated for MMP and found via the MAME debugger. 

# Version 0.02

- Artwork is total placeholder and is just ripped off from the Pink Sweets overlay
- Score display works
- Rank display works
- Input display works, although the button labels are wrong
- Lard meter works
- Boss HP works, mostly (boss 2 and stage 4 midboss 1 have some weirdness)
- Boss timers **DO NOT WORK**
- Character graphics and names **DO NOT WORK**

# How to use
1. Create an `mmpork` directory in the `mame/artwork` directory. For example, if you installed mame in `C:\mame`, place the file at `C:\mame\artwork\mmpork`
2. Copy all these files into that `mmpork` directory.
3. Enable the Layout helper plugin in mame under "Configure Options" > "Plugins".
4. Start playing Muchi Muchi Pork with the `mmpork.zip` romset as usual.

For command line users, start `mame` like this:

``` sh
./mame mmpork -plugin layout 
```
