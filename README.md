# CS:GO Clarity

Simplifies chat text and friends list statuses for Counter-Strike: Global Offensive.

## Features

* Chat messages for allchat, teamchat, radio, grenade use, and money rewards are much shorter and easier to distinguish.
* Friends list statuses for playing and watching all gamemodes are much shorter and easier to distinguish.
* Updated for **Operation: Wildfire**! This project is kept up to date with every new operation Valve publishes.

## Installation

1. Download the [text file](https://raw.githubusercontent.com/KovuTheHusky/CSGO-Clarity/master/csgo_clarity.txt). You may have to use `File > Save As...` to do so.
2. Place `csgo_clarity.txt` in your `csgo/resource` directory.
3. Right-click 'Counter-Strike: Global Offensive' in Steam and select 'Properties' and then 'Set Launch Options...'
4. Add the launch option `-language clarity` and click 'OK' and then 'Close'.

## Configuration

If you'd like to make any changes, clone this repository and edit the language file. Color codes are listed below for your convienence.

Color | Character | Binary | Description
--- | :-: | :-: | ---
White | SOH |  |
Red | STX |  |
Team | ETX |  | May cause player's color dot before symbol.
Green | EOT |  |
Light Green | ENQ |  |
Green | ACK |  | Color used for monetary awards.
Light Red | BEL |  | Color used for monetary penalties and warnings.
Silver | BS |  |
Gold | HT | 	 |
Light Blue | VT |  |
Blue | FF |  |
Violet | SO |  |
Light Red 2 | SI |  |

## Links

* Website: <http://codeski.com/#csgoclarity>
* Issues: <https://github.com/KovuTheHusky/CSGO-Clarity/issues>
* Source: <https://github.com/KovuTheHusky/CSGO-Clarity>
