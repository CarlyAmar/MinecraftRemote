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

For online patching I am using a script created by the minecraftforums user Beefive, all credit for the lwjglOnline script go to him.}
Link to Original Script: http://www.minecraftforum.net/topic/134703-linux-stuck-keys-solution/page__st__20

I also plan on adding a limited Mod support, such as an ASCII gui for adding and removing mods from a mods folder.

Contact me via github (www.github.com/ZackAlfakir/Cheapshades97sMinecraftTool) if you have any problems!

Jar Install means that the script will take a zip file, install it into a copy of your minecraft.jar, rename the old minecraft.jar to minecraftBackup.jar and copy the modded minecraft.jar to your Mods folder calling in minecraft$Mod.jar
Modding is still experimental and I am not responsible for any damage caused by this script. Backup your files!!!!!

Downloading mods from this script seems to be harder than I thought, you may have to download manually, but until I decide, I will keep the Mods file

Have a nice day :)
