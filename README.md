# MonoScreen Theme for GarlicOS

Theme for GarlicOS (version 1.3.2) inspired by Nintendo DS interface elements. Now with a variant dark theme.

![screenshot](/Screenshots/light_and_dark.png)

# How to Install

Download the theme of choice (MonoScreen Light or MonoScreen Dark) from the [latest release](/releases), then, in the main SD card where GarlicOS is installed, replace the `boot_logo.bmp.gz` in the "MISC" partition, and the `CFW` folder in the "ROMS" partition.

## Retroarch Theme

A theme for retroarch is also included, but it doesn't apply by default, to enable it open Retroarch (the gear icon) and go to "Settings>User Interface>Appearance" and set "Menu Color Theme" to "Custom" and "Custom Menu Theme Preset" to "retroarch".

Switching from the Light to Dark theme should update the theme files so you only need to set it up once.

## Box Art

The themes expect Box art in the left 1/3 of the screen but you have to set up the boxart for yourself, Retro Game Corps has a [easy guide](https://retrogamecorps.com/2023/01/03/anbernic-rg35xx-starter-guide/#Boxart) on how to do it. The only difference is instead of the code provided, use the code below instead

```magick mogrify -resize 220x350 -extent 640x480 -gravity West -background none *```

But with the extra space, it should be readable without it.

# Limitations

Given the font choice, this theme do not support some languages. The included languages are:

- Catalan
- Dutch
- English
- Filipino
- French
- German
- Indonesian
- Italian
- Brazilian Portuguese
- European Portuguese
- Spanish

The included languages from the default GarlicOS installation will still work but won't align perfetly, also some words in french and german are too long and wont fit in the screen properly.
