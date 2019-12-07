=========SegaCD Mini THEME=========
=			  	  =
=           Version 2.0           =
=       Created by Arcanthur      =
=				  =
===================================

---------------------------------
Changelog - v 2.0 -             -
---------------------------------

- Added support for Detailed, and Video view types
- Added Sega Arcade Classics
- Added Mega-CD (Japan)
- Added Sega Genesis Mini Playlist support
- Redesigned system and settings menu
- Redesigned Game Gear section
- Cleaned up several graphical assets
- Further optimized the XML
- Added custom navigation helper icons
- Full support for Favorites, Last Played, and All Games auto playlists

- Change these settings for the optimal experience
	- UI Settings > Carousel Transitions > Off
	- On Screen Help > Off

- Posters will show in the Detailed view
- Screenshots will show in the Video view if you have them scraped as <marquee>

---------------------------------
To install run this command:    -
---------------------------------

sudo mkdir -p "/etc/emulationstation/themes/Neo Geo Classic/" && sudo git clone https://github.com/Arcanthur/es-theme-NeoGeoClassic.git "/etc/emulationstation/themes/Neo Geo Classic/" --branch master --depth=1

----------------------------------
----------------------------------

To use this theme, it is highly recommended you install the emulationstation-dev branch.  The dev branch has better support for the grid view.

---------------------------------
-  To install the dev branch    -
---------------------------------

Settings > Retropie setup > Manage Packages > Manage Experimental Packages

Scroll down and install Emulationstation-Dev from source.  Once the application has compiled you will need to reboot your system, and you should now be running the correct version.  You can verify by pressing start on your controller and checking the version # that displays at the bottom of the screen.

Next change the view type to Grid, then select the SegaCD Mini theme.

---------------------------------
- Systems currently supported   -
---------------------------------

Sega SG-1000
Sega Master System
Sega Genesis
Sega Mega Drive (Europe)
Sega Mega Drive (Japan)
Sega CD
Mega CD (Japan)
Sega 32X
Sega Game Gear
Sega Arcade Classics
Genesis Mini (Playlist)

If assets don't load for your system check the folder name of your system and verify if matches the theme.

---------------------------------
- Background Music	        -
---------------------------------

I wrote some music to go along with the theme that you can use for a background theme.  The download for that is included with the box art pack below.
I've tried several methods to add background music to RetroPie and this is the one that I recommend:

https://github.com/Naprosnia/RetroPie_BGM_Player

---------------------------------
- Box Art		        -
---------------------------------

Due to memory retrictions on the Pi, box art will need to be optimized and shrunk down to run properly.  Max recommended image size is 242 x 340.  If you run less systems, and have small gamelists larger resolutions may be possible.

I have created box art packs to help get you started, but your roms will need to have the same names as mine.  I will include gamelist.xml's and a custom es_systems.cfg as well to make things easier.

Download these here:

https://drive.google.com/open?id=1Kw5XMNTz0hGp9zgSBFcpTevjYp0whJ3C


----------------------------------
Like my work?                    -
----------------------------------

Want to say thanks, or buy me a beer?
https://paypal.me/pools/c/8kA8RB42Ue
