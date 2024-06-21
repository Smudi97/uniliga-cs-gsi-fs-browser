## This app is supposed to be used in conjunction with the Uniliga CG Overlays App and its Overlays.
The zip found in the [releases tab](https://github.com/Smudi97/Uniliga-CS-GSI-Websocket/releases) holds three files:
- a "GSI Websocket.exe"
- a "gamestate_integration_uniligacg.cfg"
- and a "uniliga-hud.cfg"

Before you can use any of it, you should unzip the file into a folder of your choice.

Both of the .cfg files should be placed inside the cfg folder in your Counter-Strike Global Offensive\game\csgo folder, usually found at \*YourSteamLibraryHere\*\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg

Alternatively for advanced users, the options inside the hud.cfg can be added to the launch Options of your Counter-Strike app.

You can start the GSI Websocket.exe at anytime and from anywhere on your system. As soon as the GSI Websocket.exe is started, it will try to send any information received from CS2 to the ingame overlay.
The cmd window of the GSI Websocket.exe has to remain open for the duration of your use. If you close it, communication between the game and the overlay stops.

Once you've loaded up the game, you also have to execute the uniliga-hud.cfg by opening the ingame console and typing in "exec uniliga-hud.cfg". This will configure the ingame hud so that only the necessary ingame elements remain visible.

That's it.
