# Compiling on Windows 7

* Install Visual Studio 2010
* Install DirectX SDK June 2010
* Run VS in administrator mode. If you don't do this then it'll fail to find the DX includes.
* Open the project solution found in the neo directory.
* Build solution.

# Running the Game

* Download the game assets. Note the path to the parent directory that contains `base/`
* Run the game exe from a console like so: `./Doom3BFG.exe +set fs_basepath "<PATH TO ASSETS>" +set r_fullscreen 0`
* Or run the game from Visual Studio by changing the startup project to `Doom3BFG` with the command line args from above.
