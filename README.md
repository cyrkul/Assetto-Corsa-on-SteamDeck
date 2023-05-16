# Assetto-Corsa-on-SteamDeck
Assetto Corsa on the SteamDeck is working once again, as you've probably noticed none of the online guides are working, so here is one that works.

This is tested with an up to date SteamOS, and no major modifications - I have installed CryoUtilities without root permissions, default settings.


Assetto Corsa on the SteamDeck

Working as of Tuesday, May 16, 2023, up-to-date Deck

1. You do not need to set your deck to writable (there are lots of guides online for that if you need it, it involves setting a password for your deck)

2. Install Assetto Corsa normally via Steam

3. Go into desktop mode and run the game, to set up the file structure, the game will crash, let it do so naturally, the setup process will take around 30 minutes from here till the game works

4. Install ProtonUp-QT from Discover store, select "Install for: Steam" from dropdown list and then install GE-Proton8-3. You can select Assetto Corsa to use it in ProtonUp-Qt but I did it in Steam. For that you need to restart Steam (still in Desktop mode) and then go To Assetto Corsa settings Compatibility tab and select ProtonGE 8.3 from list.

5. From my experience you do not have to remove compatibility settings, which are located in directory: Home/deck/.local/share/steam/steamapps/compatdata/244210/pfx

6. Let the game start, it will chug along for 10 minutes or so, as it is installing dependencies, it will crash naturally. 

7. This step is NOT MANDATORY, and only if you are curious about what is going on, set a tail to the winecfg file to see what dependencies are being installed, or you can use System Monitor application to view background tasks. 

8. Once the game has crashed, run it again, this time it will run for 10 minutes and then the game will open, OR the game might crash again, do not panic, simply let the game run till it crashes then try again.

9. Go ahead and close the game, and run the game for a third (or final) time, this time the game will install the final batch of dependencies and be ready to play

10. I didn't need to turn on 32-bit in the settings, but in the past the game did not work without that.

11. Select best matching controller layout to match yor needs, if you want to use gyroscope I suggest using Community layout "SteamDeck with Gyro" and import SteamDeckGyro.ini config file that I created (available as a part of this repository).

12. I was able to install Content Manager and Mods without any issue adapting ContentManager section from this guide: https://gamepretty.com/assetto-corsa-how-to-play-on-linux-proton-steam-deck/

13. Enjoy the best racing sim on the market, once again playable on Deck
