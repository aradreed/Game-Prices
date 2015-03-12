# Game-Prices v0.7
## Description
Grabs the recent price from http://pricecharting.com for video games. Pass it a game name, and it will display the loose price, complete price (only for results with one match), and new price for the game. If the search has only one match, it will list that one. Otherwise, all the search results will be listed. Search for a game on a specific platform by using the -p switch. More info on usage can be seen below.

## Usage
Normal usage

```
./gamePrices super mario bros
```

Search with a specific platform. The quotes only need to be included if the platform has a space in the name. The script supports all platforms currently on pricecharting. These are:

amiibo, atari 2600, atari 400, atari 5200, atari 7800, cd-i, gameboy, gameboy advance, gameboy color, gamecube, macintosh, nes, nintendo 3ds, nintendo 64, nintendo ds, pc games, sega genesis, super nintendo, virtual boy, wii, wii u

```
./gamePrices -p "super nintendo" mario
```