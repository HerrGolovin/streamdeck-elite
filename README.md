# streamdeck-elite
Elgato Stream Deck toggle-button plugin for Elite Dangerous

This plugin connects to Elite Dangerous, to get the on/off status for 12 different toggle-buttons.
If you press the relevant button on your keyboard or hotas, then the image on the stream deck will change correctly.
When a button has no effect (e.g. when docked) then the image won't change.
(normal buttons don't need any plugin, they simply simulate a keypress)

The supported toggle-buttons are:
- Cargo Scoop
- Landing Gear
- Flight Assist
- Lights
- Night Vision
- Analysis Mode
- Hardpoints
- Supercruise
- Silent Running
- SRV Turret
- SRV Drive Assist
- SRV Handbrake

The plugin looks for a file StartPreset.start in this Elite Dangerous key bindings directory :

`C:\Users\{UserName}\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings\`

That .start file should contain the exact name of the key binding file, with the extension .binds

To install the plugin, double click the file com.mhwlng.elite.streamDeckPlugin
which should install the plugin (only if it's not already installed)

This .streamDeckPlugin file is a zip file and the contents are simply copied to :

`C:\Users\{UserName}\AppData\Roaming\Elgato\StreamDeck\Plugins\com.mhwlng.elite.sdPlugin`

To uninstall, stop the Stream Deck application 

`c:\Program Files\Elgato\StreamDeck\StreamDeck.exe`

and delete the com.mhwlng.elite.sdPlugin directory

Some example button images can be found in the source code images directory


Thanks to :

https://github.com/BarRaider/streamdeck-tools
https://github.com/EliteAPI/EliteAPI
https://github.com/ishaaniMittal/inputsimulator
https://nerdordie.com/product/stream-deck-key-icons/