# Stats merger for minecraft beta 1.7.3

## What is this?

This small script answers this specific problem: you want to combine the stats and achievements from two minecraft b1.7.3 installations.

This adds every field of both stat files and calculates the new checksum.

This program doubles as a checksum fixer for your stats file, if you want to edit them manually. See [list of stat ids](https://www.minecraftforum.net/forums/minecraft-java-edition/survival-mode/221881-list-of-statistics-and-achievements-spoiler-alert#c2) to edit your stats manually. In this case just choose one file in this script and ignore the second prompt.

This program is made for minecraft b1.7.3.

## Disclaimer

I am in no way responsible if you lose any file, make a backup of your stats file, because if minecraft doesn't like the new file it will erase the stats.

This is made for beta 1.7.3 and I don't know if it will work on other versions.

## How to use

Get the stats files from both installations. They can be found under .minecraft/stats and end with .dat. Start the script, select file a, select file b, and then save the new file. Make a backup before permanently replacing a file.

If in minecraft all your stats are reset, then this didn't work (probably because of the checksum, see "CHECKSUM MISMATCH" message in minecraft's logs).

If you just want to fix the checksum of your stats file (if you edited your stats manually) just don't choose file b.
