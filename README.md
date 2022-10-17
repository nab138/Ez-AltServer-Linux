# Ez-AltServer-Linux
I tried to install and use Altserver linux and while it was cool, it was a huge pain. This is an application designed to make usage easy.

This is also a project I'm using to get more comfortable with python. I barely did anything here, all credit goes to NyaMisty for making AltServer-Linux. I just made a simple python script to make it easier to use.

The Install AltStore feature is untested, but feel free to try it. If you do, open an issue to let me know how it goes even if it was successful

If there's enough intrest, I will polish and package this to make it even easier to use.

You can contact me on discord or open a github issue if you have any problems: `nab138#2035`
# Install Instructions
1. Clone this repo

2. Download the latest binary of [Altserver-Linux](https://github.com/NyaMisty/AltServer-Linux/releases) for your platform and place it here named `AltServer` (no file extension) (tested with v0.0.5 if you run into issues)

3. Download the latest binary of [Anisette-server](https://github.com/Dadoum/Provision/releases) for your platform and place it here named `anisette_server` (no file extension) (You don't need libprovision, only anisette_server)

4. Ensure both binaries from step two and three are executable `chmod +x AltServer` `chmod +x anisette_server`

5. Download the Apple Music APK and extract it. Place the lib directory in the same directory as the rest of the files. You can delete every folder except your architecture and every file in that folder except libstoreservicescore.so and libCoreADI.so. For more info, check out [Provision](https://github.com/Dadoum/Provision).

6. Use pip to install the requirments from requirements.txt `pip install -r requirements.txt`

7. As long as you have python 3.8 and tkinter, you can just run main.py. If you have issues with the device UDID, use the -u flag to specify it manually.

# Usage
When the program is running, so is altserver-linux and anisette server. Install altstore does as it says, but requires the program to be run via terminal to input the 2fa code (may be fixed later if enough interest for this repo is found)

Closing the window will minimize it to tray, where it can be quit or maximized. It does NOT kill altserver or anisette.
# Screenshots

![AltServer GUI](https://nab138.tixte.co/r/altserver.png)
