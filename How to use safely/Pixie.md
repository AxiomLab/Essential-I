PixieMC(Pixie) is one of the safe methods to use Essential Mod without selling data.

## How to install Pixie
1) You can install Pixie with the installer from https://pixie.rip/install.

2) If you are using Prism Launcher(PolyMC) or/and Modrinth, you need to open Prism Launcher, click Settings, then “Environment Variables” and then click “Add”, then set the name to ESSENTIAL_CM_HOST and the value to wss://connect.pixie.rip/v1.

3) If you are using an OS such as a Linux distribution or various launchers, it depends a lot on the situation. But it basically boils down to one thing: set ESSENTIAL_CM_HOST as wss://connect.pixie.rip/v1 in the list of environment variables. You could try using /etc/profile or setting it to SHELL to log in, but no one knows if your WM/DE of choice will honor that when Minecraft starts. You could also try creating a command that starts your launcher with the added environment variable, or add it to .desktop (if applicable). Again - your installation will largely determine whether your variable will be honored. To see if it will be honored, try copying your terminal emulator and doing various tricks, then echo the environment variable you tested with. If one of your methods works, use it.
