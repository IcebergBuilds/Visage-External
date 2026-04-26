# Visage External
An AI powered, 100% external aimbot for roblox with zero risk of detection.

---

Visage External, unlike most 'external' cheats, is actually 100% external and doesn't modify roblox's code.
It uses live AI tracking to find players and lock your mouse towards them, all powered by your own PC.

### Features
- Live AI tracking with high accuracy
- Settings menu to control things like:
  - Player outlines
  - Smoothness for more human-like movement
  - Velocity predictions
  - Save / load profiles for easy setting swapping
  - Custom FOV
    + more!
- 0% detection risk unlike almost all other cheats

---

## Intallation (For Windows 10 + 11)
First, download the latest release in the [releases tab.](https://github.com/IcebergBuilds/Visage-External/releases/latest)
- make sure you download 'VisageExternal.zip' not source code.

Now that you have VisageExternal.zip on your computer, right click it and press 'Extract all' and then press 'extract'

You should have the VisageExternal folder on your computer. Next we need to install python if you dont have it already.
1. Go to [python.org](https://www.python.org/downloads/) and download the latest version
2. Run the python installer exe, and follow the steps. Make sure that the "Add Python to PATH" box is checked and continue with the installation.

Next, install the dependencies needed for Visage to run. We have included a requirements.txt for easy install.
Just run

```bash
pip install -r requirements.txt
```

and wait for all the packages to install.

And the final step!
Open your terminal and navigate to the folder.
If you do not know how to do this, just ask chatGPT or smth lol
Now run

```bash
python visage_external.py
```

and it should start!
If you have an NVIDIA GPU, the script will configure itself to be more efficient. (takes about 1-2 minutes)

The aimbot menu will now be open!
It should be pretty self explanatory:
click the "Launch" button and open roblox.
Adjust the settings however you want, but I recommend turning off the overlay and aim dot for better performance!

Have fun!