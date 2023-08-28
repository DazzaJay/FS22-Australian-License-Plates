For Adding these plates to your custom map:

The instructions may differ depending on the directory layout of your map.
1. Extract the licensePlates folder into your custom world's maps folder. 
For example, Southern Cross Station would be: FS22_SouthernCrossStation.zip\maps
so you will end up with: FS22_SouthernCrossStation.zip\maps\licensePlates

NOTE: If your map files are not in a /maps/ subfolder, you will still need to put the licensePlates folder inside a /maps/ folder.

2. Edit your map.xml so that then license plates line points to the correct location: 
Here is the one that works here:

<licensePlates filename="maps/licensePlates/licensePlatesUS.xml"/>

3. Edit your trafficSystem.xml so that the license plates line points to the correct location:
For example:

<trafficSystem licensePlates="maps/licensePlates/aiLicensePlatesUS.i3d">

NOTE: If your trafficSystem.XML is in a different folder to your map.xml then you must put the AI Licence Plates in a subfolder of the folder your trafficSystem.XML is in.

For example: the Western Australia map does not have a maps folder, and the trafficsystem.xml file is in a different subfolder. 

So you would have to put the aiLicensePlatesUS.i3d & aiLicensePlatesUS.i3d.shapes files in the following directory: 
FS22_WesternAustralia.zip\xml\maps\licensePlates

And the licensePlatesUS_diffuse.dds & licensePlatesUS_normal.dds files in the following directory: 
FS22_WesternAustralia.zip\xml\maps\licensePlates\Textures

NOTE: If no traffic cars spawn, your files are in the incorrect directory and more experimentation will be needed to fix it.

- If you know how to make the paths simpler to use and implement, please drop the information on: https://github.com/DazzaJay/FS22-Australian-License-Plates/discussions


This contains 3 Types of plates:
Modern: Y 2 Letters - 2 Numbers, 1 Letter: YAA-11A
Classic: Y 2 Letters - 3 Numbers: YAA-111
Custom: 6 Character AlphaNumeric. (Realistic)


Also contain 20 NPC Traffic license plates.
10x ACT YAA-11A
5X  ACT YAA-111
5x  Personalised Plates.



-Daniel "DazzaJay" Fitzgerald
