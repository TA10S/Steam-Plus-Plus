# Steam-Plus-Plus
(Completely unrelated to [Seishun's SteamPP C++ Library](https://github.com/seishun/SteamPP))
### How to Install

Go to the folder that matches your hardware (32/64)
Then, go to the folder that matches your GPU (Intel/NVidia/AMD)

Run Steam++.exe. Syscoms.bat is scanned by Steam++ to find commands, therefore echoing the batch commands themselves.

### How to uninstall

Run the batch file alone, not the exe. 
A file called 3 will be generated. You will have to manually delete it. (ugh, i know right?)
(Deleting "3" will clear Steam's interface cache, thus resetting to default files)

### Description

This app runs hardware level syscom commands that are injected in the bat file. 
The only visible code is the echoes which are the commands themselves. No further actions are required.


### Features

+ Everything run as one program instead of multiple, thus the entire proccess of Steam runs faster. (At the compromise of slight instability)

+ Improves the overlay performance by rendering all the modules(friends panel, community hub, etc.)
  at once instead of each other. See above. (Tested with PUBG, GMod, Paladins, HL2, Portal 2...)

+ Graphic patches, games that run on the HL2 engine now look better, due to making the GPU run HL2's graphic engine with less compression on the textures. (Doesn't affect the games directly, no need to worry about VAC-Bans)


###Still working as of 4/3/19
