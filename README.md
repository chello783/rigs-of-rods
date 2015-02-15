# Rigs of Rods

Copyright (c) 2005-2013 Pierre-Michel Ricordel  
Copyright (c) 2007-2013 Thomas Fischer  
Copyright (c) 2013-2015 Petr Ohlidal  

This is Rigs of Rods, an open source vehicle simulator focussed on simulating vehicle physics.
For a simple overview of the features Rigs of Rods provides please refer to ``` doc/Things you can do in Rigs of Rods.pdf ```

#### Trailer:

[![Rigs of Rods Trailer](http://img.youtube.com/vi/3A6OHnAD_Pc/0.jpg)](http://www.youtube.com/watch?v=3A6OHnAD_Pc)

## Supported platforms:
* Windows
* Linux
* OS X


## Further documentation
* Website: http://www.rigsofrods.com/
* Wiki: http://www.rigsofrods.com/wiki/
* Developer wiki: http://www.rigsofrods.com/wiki/pages/Developer_Wiki_Portal
* Forum: http://www.rigsofrods.com/forum/
* Mod Repository: http://www.rigsofrods.com/repository/
* Github: https://github.com/RigsOfRods/rigs-of-rods
* doc/ directory of source distribution


## Paths
$bin  - Compiled binaries  
$res  - Resources for the game  
$user - User-created modifiable data  

Windows:  
$bin   = source\bin  
$res   = source\bin\resources  
$user  = MyDocuments\Rigs of Rods  

Linux:  
$bin    = source/bin  
$res    = source/bin/resources  
$user   = ~/.rigsofrods  

OS X:  
$bin    = ?  
$res    = ?  
$user  = ? 


## Controls
Depending on the vehicle there are a lot of commands. For a graphical overview refer to ``` doc/keysheet.pdf ```  
For an indepth view refer to ``` $user/.rigsofrods/config/input.map ```  
Please note that certain vehicles come with their own specific commands not represented in the above sources. In this case see the vehicles documentation or use 'T' key ingame for a list of commands.

##### Basic commands:  

| key                            | effect                                               |
|--------------------------------|------------------------------------------------------|
| arrow keys                     | move, steer, accelerate, decelarate                  |
| mouse+rightclick               | rotate camera                                        |
| mousewheel+rightclick          | camera zoom                                          |
| C                              | change camera perspective                            |
| T                              | display vehicle stats + specific commands            |
| BACKSPACE                      | reset vehicle at current location                    |
| I                              | reset vehicle to spawnpoint                          |
| TAB                            | show minimap                                         |
| ESC                            | show menu                                            |
| A/Z                            | trucks: shift up/down                                |
| CTRL+HOME                      | aircrafts: start engine                              |
| Page Up/Down                   | aircrafts: increase/decrease throttle                |
| F1/F2                          | helicopters: lift up/down                            |
 
 
## Mods
Rigs of Rods comes only with a very small selection of vehicles and terrains. For the best experience download additional mods from http://www.rigsofrods.com/repository/  
If you want to get going quickly have a look at modpacks that can be found in the repository as well.


## Configuration files
- Default location:  
    $user/config/*
- They are created by RoRConfig on first use


## Command-line options

* -map \<mapname\>
    * loads the map on startup. Example:
        * ``` RoR.exe -map aspen ```
    * note: do not add the .terrn extension
* -truck \<truckfile\>
    * loads a truck on startup. For example: 
        * ``` RoR.exe -map oahu -truck semi.truck ```
        * ``` RoR.exe -map oahu -truck an-12.airplane ```
* -enter
    * Enter selected truck by -truck on startup
* -setup 
    * this shows the Ogre Settings Dialog instead of loading the settings from ogre.cfg 
* -help
    * shows a command line argument help

	
## Compiling
For instructions refer to BUILDING.md
	

## License of Rigs of Rods

Rigs of Rods is licensed under GPLv3 or later:
```
Rigs of Rods is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License version 3, as 
published by the Free Software Foundation.

Rigs of Rods is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Rigs of Rods. If not, see <http://www.gnu.org/licenses/>.
```

For licenses of used libraries see DEPENDENCIES.md
