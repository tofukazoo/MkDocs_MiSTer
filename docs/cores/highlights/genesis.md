The Genesis core is a port of the [fpgagen](https://github.com/Torlus/fpgagen) core to MiSTer, with significant enhancements and additions.

## Features

* Composite Blending effect (e.g. Sonic Waterfall transparency)
* CPU Turbo option (e.g. Road Rash gameplay speed)
* Increase sprite limit.
* Audio Filtering options for Model 1, Model 2, Minimal, and No Filter
* Switch between YM2612 (Model 1) or YM3438 (Model 2/3) FM Synth
* Multitap: 4-way, Team Player, J-Cart
* SVP Chip (Virtua Racing for Genesis supported)
* Auto-Region header detection using the [new style and the old style combined](https://plutiedev.com/rom-header#region).
* Corrected Aspect Ratio option for 320x224 game resolutions (e.g. Castlevania Moon).

## Region detection

There are two methods of region detection.

1. Header: This method detects a character in the header to determine if the game was intended to be played on a Japanese, European, or American version of the console. This method is default and preferred as it is compatible with the entire commercial lineup. This option uses a region priority setting for multi-region games which had "JUE" in the header. Whatever the first region is, will be the region set on load of a multi-region game.

2. File Ext: This method changes the region according to the filename extension of the rom. BIN = Japanese, GEN = America, MD = Europe.

There is also a re

## Corrected Aspect Ratio
![type:video](videos/genesis-car.mp4)

## Composite video
![type:video](videos/genesis-comp.mp4)

## Turbo CPU
![type:video](videos/genesis-turbo.mp4)






-------------------------------------

Brief overview, similar to the readme on github, use as reference but don't just copy paste

list of features

readme section has to explain header detection first, really important, tons of users have issues with this

add some caveats for known ongoing bugs in some games (micro machines, eeproms, etc...) to alleviate concerns and unnecessary ticket generation, also helps with searches internally and externally.


