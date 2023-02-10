# Gothic2
This repository contains a detailed guide, ressources and tools to get Gothic II up and running quickly.

For optimal experience this game should be played with a ps4 / ps5 controller on a big TV.

## Game Installation
1. Download [Gothic 2 Gold Edition from Steam](https://store.steampowered.com/app/39510/Gothic_II_Gold_Edition/)
2. Download and Install [Spine from Clockwork](https://clockwork-origins.com/spine/)

## Start the Game
Before starting the game ensure that you went throuh the entire installation guide
1. Open Spine
2. Select "Bibliothek"
3. Select "Gothic II"
4. Under "Patches und Tools" locate and check "Systempack", "Texturepack von Merlin"
5. Click "Spiel starten"

Enjoy

## Recommended Mods
1. Open Spine
2. Go to Database
3. Install the following graphic mods

- Texturepack von Merlin
- D3D11 Renderer

## Controller Setup

### Connecting a Controller
The Controller can be connected using either bluetooth or a wired connection.

### Wired Method
Plug your controller into a USB port with a USB-to-micro-USB / USB-to-USB-C cable.

### Bluetooth Method

#### PS4 Controller
With the DualShock 4 turned off (you'll know by the deactivated light bar), press and hold the PlayStation and Share buttons for three seconds until the light bar starts double flashing.

Access the Bluetooth menu on your PC via the system tray.

Click "Add Bluetooth or other device."

Click "Bluetooth."
Select the controller from the list that pops up.

#### PS5 Controller
Enter pairing mode on the PlayStation 5 controller by holding the PlayStation and Share buttons at the same time until the lights around the touchpad turn on.
On your PC, the controller should appear as Wireless controller.
Select it and wait for the connection to finish.

## Setup the Controller

Download and install [Joy2Key](https://joytokey.net/en/download)

Locate the folder where the configuration files are stored: **File > Open config data folder in explorer**
Import the G2_Ps4_Controller_2022.cfg file into the folder that just opened

## Controller Stick Issues
In case the controller ist constantly showing a stick input execute the following
1. Open Joy2Key
2. Click "Settings" 
3. Click "Configure Joysticks"
4. Navigate to "2. Advanced setting for each device"
5. Configure Axis mapping for analog sticks
6. Stick 1: Horizontal X-axis, Vertical Y-axis
7. Stick 2: Horizontal Z-axis, Vertical RZ-axis

## Ini Changes
These changes to the .ini file are recommended to avoid the Dragon self healing ability to get way too powerfull.<br>
locate and open the configuration file under **path/to/gothicII/system/Gothic.INI**
Find "ZMAXFPS=0" and replace with "ZMAXFPS=60"

In case of Night of the Raven you could avoid this by using the [dragon patch](https://www.worldofgothic.de/dl/download_703.htm) (untested)

## Display Setup and Possible Problems
Multiple screens can cause Problems. To eliminate these set the Resolution to the same value on all Displays<br>
If this does not work switch the Windows Display settings to **only show on Second Screen** - this can be done quickly by repeately pressing the **win + p** keys

Nvidia game experience can also cause problems, check that G-SYNC is disabled and the in game overlay (Shadow Play) are Disabled. 

144hz can cause problems.
