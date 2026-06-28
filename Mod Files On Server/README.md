Step 1 – Download BepInEx



Download the BepInExPack for Valheim from here to make sure it matches the version on the server



Click Manual Download.



Step 2 – Extract the ZIP



Extract the downloaded ZIP file.



Inside you'll see files similar to:



BepInEx

doorstop\_libs

winhttp.dll

start\_game\_bepinex.sh

...

Step 3 – Find Your Valheim Installation



For Steam, the default location is usually:



C:\\Program Files (x86)\\Steam\\steamapps\\common\\Valheim



If you've installed Steam elsewhere:



Open Steam

Right-click Valheim

Manage

Browse Local Files



This will open the correct folder.



Step 4 – Copy the Files



Copy everything from the extracted ZIP into your Valheim folder.



Do not place the files inside another folder.



Your Valheim directory should now look something like:



Valheim

│

├── BepInEx

├── doorstop\_libs

├── valheim.exe

├── winhttp.dll

├── ...

Step 5 – Run Valheim Once



Launch Valheim through Steam.



BepInEx will create the folders it needs.



Close the game again.



Step 6 – Install the Server Devcommands Plugin



Download the Server Devcommands mod DLL.



(Your server owner will provide the correct version if needed.)



Step 7 – Copy the DLL



Navigate to:



Valheim

└── BepInEx

&#x20;   └── plugins



Copy:



ServerDevcommands.dll



into the plugins folder.



It should look like:



Valheim

└── BepInEx

&#x20;   └── plugins

&#x20;       └── ServerDevcommands.dll

Step 8 – Start the Game



Launch Valheim normally through Steam.



Join the server.



If your Steam ID has been added to the server's adminlist.txt, you can now use:



/ devcommands



(or simply devcommands, depending on the plugin version)



You should receive a message confirming that developer commands have been enabled.

