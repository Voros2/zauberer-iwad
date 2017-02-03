# Zauberer

This is the repository where the Zauberer IWAD is managed.
Maintained using Deutex, a command-line wad composer for DOS.

## Basic Guidelines
* Ensure that your work is not derived from commercial 
  sources, such as Doom sprites.
* If you are submitting someone else's work, ensure that it
  complies to Zauberer's license (see LICENSE for more details).
* By submitting your work, you will have agreed to license
  your work under the BSD-3 license, which allows others to
  distribute your work for free or for profit.
* Please keep your filenames in lowercase letters.

## File Specifications

### LEVELS
* WAD format only.
* Seperate file of each map.
* Naming format: map## (where ## replaces a number in the range
  01 to 41).
  
### MUSIC
* MUS or MID format only.
* Naming format: d_map## (where ## replaces a number in the 
  range 01 to 41).
  
### SOUNDS
* WAV format only.
* Naming format specified in zbuild.txt, under [sounds] section.

### SPRITES
* BMP format only.
* Background color: cyan (RGB: 0, 255, 255).
* Naming format specified in zbuild.txt, under [sprites] section.

### PATCHES
* BMP format only.
* Background color: cyan (RGB: 0, 255, 255).
* Naming format specified in zbuild.txt, under [patches] section.

### FLATS
* BMP format only.
* Background color: cyan (RGB: 0, 255, 255).
* Naming format specified in zbuild.txt, under [flats] section.

### LUMPS
* LMP format only.
* Naming format specified in zbuild.txt, under [lumps] section.
