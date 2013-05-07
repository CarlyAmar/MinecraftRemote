MinecraftLaunchSelector
=======================

I short Linux script to select from a list of Minecraft launchers.

The setup file needs to have sudo powers. This Script assumes that all of your launchers are in the same place.
It will work best if the launchers are the only thing in that folder.

To setup this script, just type
sudo ./Setup
It will ask for path to launchers and for lwjgl (optional)
from then on, you should be able to type Minecraft in any location to access this script, but only after you close and reopen Terminal. You can also type ./Minecraft to launch this script if you are in the current directory. 
If you get a permission denied during setup, make sure you are using sudo privelages. If it happens while running the Minecraft script, try chmod 755 the scripts in the the directory.

I plan on getting permission for a script to better update from an online source and use that instead, but for now you will have to use a quick one I wrote.

I also plan on adding a limited Mod support, such as an ASCII gui for adding and removing mods from a mods folder.

Contact me via github (www.github.com/ZackAlfakir/MinecraftLaunchSelector) if you have any problems!

Have a nice day :)
