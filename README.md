![Aussie Plates Header Image.](_Development_Files/Images/Aussie-Plates-Header.png)

# FS22 Australian License Plates
Australian Number Plates for Farming Simulator 22 Map Makers to use in their custom maps


Feel free to use these in any custom map you make for FS22.
You don't need to credit me.

NOTE: Only ONE set of state plates can be in a map at once. you can't have multiple sets. or, at least, i've not been able to find a way.
Also, It doesn't seem like you can make a license plate mod as a standalone mod. they seem to only work INSIDE a map file.


# TODO:
- [ ] **1. IN PROGRESS: Take New Screenshots.**
- Textures have been adjusted since last set of screenshots. Take new screenshots.

# KNOWN ISSUES:
- If you apply a set of plates with less style variations than the map already had, you may find the style box is blank - This is a game issue, not an issue with the mod.
     To fix this, simply purchase a vehile with whatever plate you're given, then close and reopen the store, and all the plate styles will now be there and be functioning properly.

- NPC Traffic Plates only work if your map was originally based on MapUS. For example; If replacing plates on a map based on MapFR or MapAlpine, Player owned vehicle plates will be the Australian style, NPC Traffic will not.
     No known solution at this time.

- Directory Structure for AI Traffic Vehicle License Plates is a bit wonky. Read the instructions carefully below.

# Download The Prefab Package:
![Prefab Icon](https://github.com/DazzaJay/FS22-Australian-License-Plates/blob/main/_Development_Files/Images/icon_prefab.png?raw=true)
- ℹ️ Download the prefab directly from Giants ModHub: 
- **➡️ [https://www.farming-simulator.com/mod.php?mod_id=276164](https://www.farming-simulator.com/mod.php?mod_id=276164) ⬅️** 
- or look for it in the Giants Editor Prefab Browser. 

# Manual Install Instructions (Not Prefab):
- ℹ️ The instructions may differ depending on the directory layout of your map.

- 1. Extract the licensePlates folder into your custom world's maps folder. 
For example, Southern Cross Station would be: FS22_SouthernCrossStation.zip\maps
so you will end up with: FS22_SouthernCrossStation.zip\maps\licensePlates

ℹ️ NOTE: If your map files are not in a /maps/ subfolder, you will still need to put the licensePlates folder inside a /maps/ folder.

- 2. Edit your map.xml so that then license plates line points to the correct location:
Here is the one that works here:

```<licensePlates filename="maps/licensePlates/licensePlatesUS.xml"/>```

- 3. Edit your trafficSystem.xml so that the license plates line points to the correct location:
For example: 

```<trafficSystem licensePlates="maps/licensePlates/aiLicensePlatesUS.i3d">```

ℹ️ NOTE: If your trafficSystem.XML is in a different folder to your map.xml then you must put the AI Licence Plates in a subfolder of the folder your trafficSystem.XML is in.

For example: the Western Australia map does not have a maps folder, and the trafficsystem.xml file is in a different subfolder. 

So you would have to put the aiLicensePlatesUS.i3d & aiLicensePlatesUS.i3d.shapes files in the following directory:
FS22_WesternAustralia.zip\xml\maps\licensePlates

And the licensePlatesUS_diffuse.dds & licensePlatesUS_normal.dds files in the following directory:
FS22_WesternAustralia.zip\xml\maps\licensePlates\Textures

ℹ️ NOTE: If no traffic cars spawn, your files are in the incorrect directory and more experimentation will be needed to fix it.

### - ⚠️ If you know how to make the paths simpler to use and implement, please drop the information on: https://github.com/DazzaJay/FS22-Australian-License-Plates/discussions


# DONE:
This order could change, depending on requests.
- [x] **1. DONE: New South Wales.**


- NSW Plates Styles:
      ![NSW Plates Image.](_Development_Files/Screenshots/New%20South%20Wales/Plate-Shots.png)
- [x] **2. DONE: Western Australia**

- WA Plates Styles:
      ![WA Plates Image.](_Development_Files/Screenshots/Western%20Australia/Plate-Shots.png)
- [x] **3. DONE: Victoria**

- Vic Plates Styles:
      ![Vic Plates Image.](_Development_Files/Screenshots/Victoria/Plate-Shots.png)
- [x] **4. DONE: South Australia**

- SA Plates Styles:
      ![SA Plates Image.](_Development_Files/Screenshots/South%20Australia/Plate-Shots.png)
- [x] **5. DONE: Queensland**

- QLD Plates Styles:
      ![QLD Plates Image.](_Development_Files/Screenshots/Queensland/Plate-Shots.png)
- [x] **6. DONE: Northern Territory**

- NT Plates Styles:
      ![NT Plates Image.](_Development_Files/Screenshots/Northern%20Territory/Plate-Shots.png)
- [x] **7. DONE: Tasmania**

- Tas Plates Styles:
      ![Tas Plates Image.](_Development_Files/Screenshots/Tasmania/Plate-Shots.png)
- [x] **8. DONE: Australian Capital Territory**

- ACT Plates Styles:
      ![ACT Plates Image.](_Development_Files/Screenshots/Australian%20Capital%20Territory/Plate-Shots.png)
- [x] **9. DONE: Adjust Colours of plate text to better match background colours.**
- Apparently the colour calculator here [https://assets.mantrid.net/colour/](https://assets.mantrid.net/colour/) is (at a guess 20%) too dark. (SA / NSW Unaffected, as they both use Black)

- [x] **10. DONE: Create a Prefab.**
- Prefab has been created, tested with TestRunner, and has been uploaded to ModHub. **➡️ [https://www.farming-simulator.com/mod.php?mod_id=276164](https://www.farming-simulator.com/mod.php?mod_id=276164) ⬅️**  - You should see it in Giants Editor soon!

## Credits:
- Daniel "DazzaJay" Fitzgerald
- https://wwwPotholeStudios.com
