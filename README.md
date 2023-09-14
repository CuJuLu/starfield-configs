# Starfield Custom Configs
These are simply .ini and .txt files for my custom play setup.

Installation:
1. Place SysRootStarReborn.txt in the Starfield folder, the same folder that Starfield.exe is located in. The directory is typically steamapps/common/Starfield. Do not place the .txt's inside of your Data folder.

2. Use the StarfieldCustom.ini provided and place the values inside of your own StarfieldCustom.ini, which should be in your documents folder. The director is typically Documents/My Games/Starfield. If you've already been modding Starfield, then you'll most likely have a mod-ready StarfieldCustom.ini file. However, if not, do the following:

3. Make sure that:

```
    ﻿[Archive]
    bInvalidateOlderFiles=1
    sResourceDataDirsFinal=
```

is present at the top of your StarfieldCustom.ini. If you do not have StarfieldCustom.ini, simply create one and open it with any text editor and do as previously mentioned. Make sure there are no duplicates of those or any other commands. After that, simply throw in the starting commands under the general section of the file.

Your StarfieldCustom.ini would look something like this:

```
    ﻿[Archive]
    ﻿bInvalidateOlderFiles=1
    ﻿sResourceDataDirsFinal=
﻿
    [General]
    sStartingConsoleCommand=bat SysRootStarReborn;
```

If you already have a bat file active you can list additional ones on the same line separated by a semicolon, Like the below example.

```
    ﻿[General]
    sStartingConsoleCommand=bat fileONE.txt; fileTWO.txt; fileTHREE.txt
```
