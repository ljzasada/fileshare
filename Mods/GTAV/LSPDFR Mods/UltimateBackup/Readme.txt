=======================================================
GTA V - LSPDFR - Ultimate Backup
Version 1.5.6.0 | Developed by BejoIjo Productions
Copyright (c) 2019 All Rights Reserved
=======================================================

PREREQUISITES:
--------------
1. Rage Plugin Hook v0.57 alpha
2. LSPD First Response v0.4 by G17
3. Rage Native UI v1.6.3.0 by alexguirre
4. Traffic Policer v6.13.7.0 by Albo1125 (required by traffic stop observation)
5. Police SmartRadio v1.1.1.1 by Albo1125 (required to request backup using Police SmartRadio)
6. VocalDispatch v1.6.0.0 by turbofandude (optional if you want voice command to call backups)
7. Stop The Ped v4.2.9.1 by BejoIjo


OVERVIEW:
---------
I created this plugin to replace the default LSPDFR Police Backup menu and combine the power of my previous three backup plugins to assist the player during traffic stop, pursuit, and on scene situations.
More over, you can also customize the police units components, properties, and weapons based on regions and zones in LSPDFR.

!!ATTENTION!! 
- You will no longger need "Traffic Stop Backup", "On Scene Backup", and "Spike trips Backup" plugins, since they are already built in to the Ultimate Backup plugin. 
- You may remove them safely.
- I recommend you to use "Ultimate Backup" instead of those 3 plugins above, because they have been discontinued. I'll no longer support those plugins.


INSTALLATION:
-------------
- Copy the contents of "Plugins\LSPDFR" in this package to: "GTA V directory\plugins\LSPDFR"
- If you haven't had "RageNativeUI.dll" in your "main GTA V folder", don't forget to copy the file from this package
- If you already have newer "RageNativeUI.dll", please keep using it. No need to overwrite the file
- Please open and edit "UltimateBackup.ini" file, if you want to replace the keyboard key or controller button bindings and any other plugin parameters


HOW TO USE:
-----------
- To toggle "Ultimate Backup" menu, press "B" key. If you have keybind collision, you may change the key in the .ini file or change the LSPDFR Backup keybind
- You can also customize the toggle menu key or button in the UltimateBackup.ini file
- If you have PoliceSmartRadio or VocalDispatch, this plugin will automatically detect and integrate their funtionalities with Ultimate Backup
- You may dismiss all backups by HOLDING "ENTER" key.
- You may also customize the backup unit by editing the "DefaultRegions.xml", "CustomRegions.xml", and "SpecialUnits.xml" files inside "UltimateBackup" folder


XML FILES:
----------
- "DefaultRegions.xml": This file contains default LSPDFR regions which will be used as fallback when your location is not found in the "CustomRegions.xml"
- "CustomRegions.xml": This file contains user defined regions which will override the definition in the "DefaultRegions.xml" for the designated zones
- "SpecialUnits.xml": This file contains additional "Special Units" that will be added into the Ultimate Backup Menu (orange color)


FEATURES:
---------
- Very easy to navigate and request backups using "RageNativeUI" menu system

- Very easy to customize the backup unit using XML file format similar with the default LSPFR backup.xml file
  # You can assign vehicle attributes to the backup unit (color, livery, extras, no of passengers, and chance of passengers)
  # You can assign components and properties of the police buddy (including hats, glasses, earpieces, and watches)
  # You can assign weapons to the police buddy, which is divided into 3 groups (non-lethal, handguns, and long-guns)
  # You can set any weapon component (e.g. weapon flashlight, clips, scope, grip) up to 6 components
  # You can define the probability (chance) of each "VehicleSets", "Vehicles", "Peds", "HandGuns", and "LongGuns"
  # You may have your own "Special Unit" and add it into the menu by editing "SpecialUnits.xml" file
  # You may also choose and customize the dog model and textures for your K9 unit

- Using PoliceSmartRadio, you can call: ("Local Patrol" only)
  # Traffic Stop Backup
  # Felony Stop Backup
  # K9 Unit Backup
  # Spike Strips Backup
  # Roadblock Backup
  # Female Backup (to assist you with female suspect)

- Using VocalDispatch, you can call: ("Local Patrol" only)
  # Code 2 Backup
  # Code 3 Backup
  # Pursuit Backup
  # Traffic Stop Backup
  # Felony Stop Backup
  # K9 Unit Backup
  # Spike Strips Backup
  # Roadblock Backup
  # Female Backup

- Using the Ultimate Backup Menu, you can call all kind of backups including "State Patrol", "SWAT Backups", "Air Units", "Ambulance", and "Fire Department"

- You can convert any "Police Buddy" to become your "Partner". The partner will follow and support you wherever you go on foot or when driving with vehicle.
  To convert a partner, simply call any cop backup units. When the buddy is in standby position, stand face-to-face and press "Enter" key.

- Ambulance unit will tend to the bodies and try to perform CPR

- Fire Department will find any fire sources and try to stop them. They can also tend to the bodies and perform CPR

- Code 2 backup will arrive with their gun holstered. Meanwhile, the Code 3 backup units will always have their gun drawn

- The Backup units (except pursuit backup) will stay and stand by for you until you dismiss them or leave them away

- If a unit consists of several cops (e.g. SWAT), you can just dismiss the group leader or driver (with the biggest blue blip) to dismiss them all

- The Spike Strips Backup in this plugin will automatically detect target vehicle during the pursuit

- There's a new "Panic Button" for PoliceSmartRadio by this plugin, where you can customize the units being dispatched in the UltimateBackup.ini file 

- You can customize the "Special Unit" backup and assign a specific role to them. Available roles are "cop", "medic", and "fireman"

- You can also assign a helicopter as a vehicle for your "Air Unit". Because the ped will get out with rappel animation, the helicopter model should have rappel device support. You can see example of this unit on "Air Ambulance" and "Air SWAT Backup"

- You can customize Police Transport and Coroner ped and vehicle models in "DefaultRegions.xml". Please take a note that you need "Stop The Ped" to call those units

- Ultimate Backup also supports the multiplayer freemode ped models (MP_M_FREEMODE_01 and MP_F_FREEMODE_01). 
  You can customize the components and props the same way as the vanilla (preset) GTA characters. You can find example on "DefaultRegions.xml" of Los Santos City local patrol.
  Since the vanilla GTA V MP freemode only support outfits for LSPD, you will need EUP pack to use other agency's outfit (e.g. LSSD) and customize it by yourself.

TIPS: To help you customizing the peds, make sure to use GTA V Simple Trainer (TrainerV) to observe and get the number or index from each components and props.


TRAFFIC STOP BACKUP
--------------------
- Perform a traffic stop and pull over the suspect, then position you car behind the stopped car
- Make sure you have enough space on your back to allow the police backup car to stop.
- Open Ultimate Backup Menu and choose the "Traffic Stop" backup unit. (you can also use PoliceSmartRadio)
- Wait a few seconds and your police backup will be coming and park the car right behind yours
- Allow the police backup to walk and take position
- When everything's fine, police buddy will be waiting for you until you dismiss him (do it by standing in front of him face-to-face) or until you're leaving the scene


OBSERVATION REPORT:
-------------------
- When your police buddy taking position during the traffic stop, he/she will observe the stopped vehicle, including the driver and passengers.
- If your buddy found something suspicious, he/she will report it to you through notification
- Based on that report, you may conduct further investigation by performing a search on the reported subject.
- You must have a third party search plugin to do that. Supported search plugins are:
  # Search Warrant by Darkmyre
  # Police Search by FtDLulz


FELONY STOP
------------
- Perform a traffic stop and pull over the suspect, then position you car behind the stopped car
- Make sure you have enough space on your back to allow the police backup car to stop
- Open Ultimate Backup Menu and choose the "Felony Stop" backup unit from the "Response Type" selection. (you can also use PoliceSmartRadio)
- The backup unit will park the car next to yours and then aim the weapon at the suspect
- You can start the felony stop process by aiming your weapon at the suspect


K9 BACKUP
-----------
- K9 Backup unit is an additional unit which can only be called when you need assistance to inspect the vehicle using K9 (dog) during traffic stop
- When the K9 officer tells you that he/she is ready, move your character in front of him/her face-to-face to make him/her start the vehicle inspection using K9
- The K9 can also detect threat from the suspects. If so, it will attack the ped.
- The inspection will take a while. Once it's done, the K9 officer will tell you the result.
- Please make sure to have a car width space on the suspect vehicle right side to allow those units to move. If there's not enough space, then expect for any glitches.
- You may choose the dog model name for k9 backup unit. Set the "k9_model" attibute within "VehicleSet". It is only valid for "K9LocalPatrol" and "K9StatePatrol"
  Available dog models are: "CHOP", "HUSKY", "SHEPHERD", "ROTTWEILER", "RETRIEVER". (if nothing is set, default would be "SHEPHERD")


IMPORTANT NOTES
----------------
- About Backup car parking position:
  # When it is called with Code 2 or Traffic Stop, the backup vehicle will try to park behind player's vehicle (lining up). Make sure to park parallel with the road and provide enough space for the backup cars to stop and park their cars.
  # When it is called with Code 3 , the unit will just come as quickly as possible and stop the vehicle at nearest location
  # If you call code 2 backup, but the scene is not safe (threat detected) or you (player) is too far away from your police car, then backup parking position will not be lined up (it will stop at nearest location)

- About sirens sound:
  # By default, while in Code 2 or Traffic Stop, siren sound is set to silent by this plugin.
  # This will work great when you're using non-ELS car models.
  # But there's a limitation for ELS car. It will still play the siren sound, eventhough the plugin has turned it off.
  # If you are using ELS car and you want a silent siren while in Code 2, set "IsCode2SirenLightsOn" parameter in the .ini file to "no".

- About Traffic Stop Backup
  # To enable Traffic Stop Backup Menu, You need to have a car pulled over and have the driver still inside the vehicle
  # If you ask the driver to get out of the vehicle, the traffic stop session will be closed by LSPDFR and you will not be able to open Traffic Stop Backup Menu

- About Threat detection range
  # Sometimes if you can see threat (shootings or weapon), but your buddies don't react, you need to increase the "ThreatDetectionRange" parameter in the .ini file
  # I set the default value to "30" to support all range of CPU specs while maintaining good frames performance
  # If you feel your CPU is strong enough, you can increase the value slightly by 10. (e.g. 40, 50)


CUSTOMIZING TIPS 
-----------------
To help you customizing the peds, make sure to use GTA V Simple Trainer (TrainerV) to observe and get the number or index from each components and props. 
The component index is always the same between TrainerV (Model Spawning -> Clothes Menu) and Ultimate backup 
    0 => Head = comp_face 
    1 => Beard = comp_beard 
    2 => Hair = comp_hair 
    3 => Upper = comp_shirt 
    4 => Lower = comp_pants 
    5 => Hands = comp_hands 
    6 => Shoes = comp_shoes 
    7 => Teeth = comp_eyes 
    8 => Accessory = comp_accessories 
    9 => Accessory2 = comp_tasks 
    10 => Badges = comp_decals 
    11 => Shirt Overlay = comp_shirtoverlay 
  
If you see the "Component ID" in LSPDFR "outfits.xml", the ID is actually the above index. 
Please beware that the values for comp, props, and tex in UB is always following the TrainerV, which is started from 1. 
Unlike LSPDFR outfit.xml which is started from 0.  
  
Mappings for props: 
    0 => Hats = prop_hats 
    1 => Glasses = prop_glasses 
    2 => Misc = prop_ears 
    3 => Watches = prop_watches


FOR DEVELOPERS
--------------
You can call almost all backup units using "UltimateBackup.API.Functions" module in "Ultimatebackup.dll" file.
Please note that to call those APIs, you should have a static class wrapper, similar with all popular plugins API.


Please feel free to contact me through LSPDFR forum or download's comment section for any issue you encountered with this plugin.
Happy patroling! Enjoy! 


SPECIAL THANKS TO:
------------------
- Albo1125 for all your plugins which make LSPDFR very joyful!
- alexguirre for all your open source modules and plugins for LSPDFR


VERSION HISTORY
---------------
v1.5.6.0 (latest)
- Improvement. Added persistency handler to prevent LSPDFR from despawning pursuit backup vehicle after pursuit ended
- Tweaked the back position clearing process on traffic stop backup and code 2 backup to make it compatible with new "Stop The Ped" empty vehicle persistency module
- Tweaked pursuit backup spawn location & make faster air support response faster on pursuit backup

v1.5.5.0
- Improvement. Tweaked code 2 backup vehicle arrival to avoid getting stuck and force respawn if the parking position is blocked by objects
- Fixed Bug. Sometimes police buddy doesn't tend to the dead body. Now it should do it correctly
- Fixed Bug. Sometimes (very rare) The Roadblock units are still despawned when pursuit vehicle is closing to their position
- Fixed Bug. When player is getting into a vehicle, the buddy weapon is drawn. Now it should be holstered
- Fixed Bug. The medic unit sometimes get stuck for so long when it's blocked by wall or object

v1.5.4.0
- Improvement. Tuned drivers AI on backup units to avoid crashing into other vehicles
- Improvement. Tweaked Pursuit Backup spawn locations
- Fixed Bug. When backup unit is recruited to be Police Transport (by StopThePed), the blip is now removed
- Fixed Bug. Fire extinguisher didn't work (no burst of gas) when Firemen tried to extinguish the fire

v1.5.3.0
- New Feature. You may customize the dog textures for your K9 unit by adding "k9_tex_face", "k9_tex_shirt", and "k9_tex_accessories" attributes. Please refer to the attached "DefaultRegions.xml" file for description and examples
  Note: To set different textures on the dog, you should install  K9 dog model mods because the vanilla dogs only have single texture
- Added API for developers to access and call backup units provided by Ultimate Backup
- Improvement. The Roadblock Backup now is more effective than before! I added one more layer which should make it harder to penetrate
- Improvement. When the Spike Strips hit the suspect vehicle, the vehicle will be moving slower
- Improvement. Tweaked some game parameter to make Roadblock & Spike Strips Backup do not dismiss too early
- Fixed Bug. Now the backup unit from pursuit backup (called from Ultimate Backup) should be available to support you as Police Transport when you call it through "Stop The Ped"
- Fixed Bug. If the pursuit have more than 1 suspect, now the backup units should spawn close to the nearest suspect

v1.5.2.0
- New Feature. Fully support Coroner and Police Transport model configuration for STP. Check it in DefaultRegions.xml file (Stop The Ped is required to call the unit)
  Note: If you're upgrading, make sure to copy "PoliceTransport" and "Coroner" sections in "DefaultRegions.xml" file
- Improvement. Tuned and tweaked the initial spawn location for Pursuit Backup units
- Improvement. Now Ambulance (EMS) unit will be driving back with siren on when there's a survived patient
- Fixed Bug. Sometimes when player dismisses all the backups, it didn't dismiss all
- Fixed Bug. During Felony Stop, sometimes the game crashes if player does not follow the STP instructions (e.g. aim the ped driver)
- Fixed Rare Crash when medic is performing CPR procedure

v1.5.1.0
- Improvement. During a pull over, your Ultimate Backup "partner" will support you like Traffic Stop Backup unit (e.g. "partner" will go to passenger side and observe the vehicle)
- Fixed Rare Crash when calling Traffic Stop Backup
Note: If you're upgrading, you just need to replace the old "dll" file with the new one.

v1.5.0.0
- New Feature. Now you can convert any "Police Buddy" to become your "Partner". The partner will follow and support you wherever you go on foot or when driving with vehicle
  To convert a partner, simply call any cop backup units. When the buddy is in standby position, stand face-to-face and press "Enter" key
- New Feature. Now the backup units will follow your weapon stance (draw or holster the weapon)
- Fixed Rare Crash when calling Traffic Stop Backup
- Fixed Glitch. Sometimes the Police Buddy becomes invisible/disappeared after arresting pursuit suspect
- Fixed Glitch. Sometimes Police Buddy drops or submerges into the ground
- Fixed Bug. When you call Air SWAT unit with more than 4 seats helicopter, the last buddy falls to ground instead of rappelling

v1.4.8.0
- Fixed Major Glitch. When Police Buddies are in combat with suspect, the gunfight animation is stuttering (like a hiccup). It should be OK now.
- Fixed Bug. Sometimes Police Buddies or their Vehicles disappear (despawned by LSPDFR). I reduced the disappear frequency. But if LSPDFR wants it gone, then it's gone
- Fixed Bug. Sometimes Roadblock units despawned when suspect vehicle is closing into it.
- Fixed Bug. In Felony Stop only 2 units are coming (when expected more)
- Fixed Bug. There was a conflict on Felony Stop when player want to arrest the main suspect with Vanilla LSPDFR

v1.4.7.0
- New Feature. Ultimate Backup now supports weapon component customization (e.g. weapon flashlight, clips, scope, grip). Please refer to "DefaultRegions.xml" for example
- New Feature. Added "Group Backup" into PoliceSmartRadio button which will allow you to request a group of backup units. You can customize which backup types should be within the group by modifying the parameter .ini file
  Note: If you're upgrading from previous version, you have 2 new parameters in the ini file: "GroupBackupUnits" and "GroupBackupSeverity". You also have 1 new PoliceSmartRadio icon to add
- Fixed Bug. When you use female MP freemode for paramedic or fireman, they have male voice. It's now suppressed because there's no voice set for female medic & fireman

v1.4.6.0
- Improvement. Added random eyebrow & eyecolor to the MP freemode backup cop
- Improvement. Added random facial hair to male MP freemode backup cop
- Improvement. Added random lipstick and makeup to female MP freemode backup cop
- Improvement. Added retry handler when player request backup but the vehicle got deleted by LSPDFR
- New Parameter. The "AllowMenuSelectionOnTrafficStop" will allow menu selection during traffic stop while player is inside vehicle (you have to change LSPDFR keybind)
- Fixed Crash. Sometimes suspect disappears when requesting traffic stop backup which cause LSPDFR to crash

v1.4.5.1
- Fixed Crash. When calling Traffic Stop Backup using Controller and player is inside a police car
  The root cause is because LSPDFR 0.4 uses different keybind mechanism the cancel vehicle button (A) cannot be blocked
  Instead of calling backup, the plugin now will display notification informing that traffic stop is cancelled

v1.4.5.0
- New Feature. Ultimate Backup also supports the multiplayer freemode ped models (MP_M_FREEMODE_01 and MP_F_FREEMODE_01). 
- Fixed Glitch. When calling Female unit backup, there should be no male voice responds to dispatch
- Improved Gameplay. Increase the waiting timeout for backup arrival to be respawn to different location

v1.4.4.2
- Fixed Glitch when Paramedic or fireman tend to dead body to perform CPR, sometimes the ped is running away and rejoin pursuit
- Fixed Glitch when the ped is saved by Paramedic or fireman and they are returning to the ambulance, sometimes the ped is running away and rejoin pursuit

v1.4.4.1
- Improved Felony Stop arresting suspect mechanics. You will need Stop The Ped minimum v4.4.2.0 to make it works
- Improved Menu and Gameplay. The backup type selector (first line) will always be on focus when opening the UB menu, so you can easily switch to another backup type easily
- Fixed Bug. The Felony Stop police buddies don't aim weapon after arrived at the scene

v1.4.4.0
- Added support for LSPDFR 0.4
- New feature. Allow a unit to not have handgun during Code 2 call. You can set the new attribute 'no_handgun="true"' on the "VehicleSet" tag
- Fixed Bug. Sometimes the roadblock disappears when suspect vehicle is moving close to the roadblock

v1.4.1.0
- Added parameter in the .ini file whether medic or fireman gives medkit if player is injured
- Fixed Bug. Sometimes after the dead ped is treated by medic, the Coroner Unit from "Stop The Ped" can not detect them

v1.4.0.0
- New Unit. Air Ambulance (helicopter) is now available to serve you. 
  *If you are upgrading from previous version, copy paste "Air Ambulance" Unit from "SpecialUnits.xml" file
- New Unit. Air SWAT Backup (helicopter) is now available to serve you. 
  *If you are upgrading from previous version, copy paste "Air SWAT Backup" Unit from "SpecialUnits.xml" file
- New Feature. During car pursuit, you can request "Roadblock Support", which will try to block the road with police vehicles. You can also request it using PoliceSmartRadio 
  *if you're upgrading, don't forget to copy the roadblock icons to PSR folders)
- Improved Gameplay. Ambulance and Firetruck will now return to hospital or firestation instead of going nowhere
- Fixed Bug. When medic is coming and player is injured but not on foot (inside a vehicle), medic was getting killed. Now the medic will wait until player get out of the car to give the medkit.

v1.3.3.1
- Improvement. Some tweaks on pursuit backup spawn mechanic
- Fixed Bug. Sometimes LSPDFR crashes when requesting Spike Strips Backup

v1.3.3.0
- New Feature. Now you can assign a specific role to "Special Unit" backups. Available roles are "cop", "medic", and "fireman". You can refer to "SpecialUnits.xml" file for examples (First Responders)
- New Feature. Paramedic (Ambulance) & fireman might give firstaid kit for player to heal 
- New Feature. Added ped voice overs (speeches) to paramedics and firemen while they are in action
- New Feature. After being dismissed, ambulance or fire truck unit will give you the "Patient Report" and statistic of their life-saving's attempts
- New Feature. Added parameter to set the number of backup unit during felony stop in the .ini file. (parameter name is "FelonyBackupNum")
- New Feature. Now you can assign weapons from DLC (e.g. MK2 weapons) to your backup units. Please refer to "Weapons reference.txt" for the list of all possible weapons
- Improvement. Added throttling during pursuit backup request to add delay between backups and prevent possible crashes
- Improvement. Now the backup unit can detect threat from peds armed with DLC weapons (e.g. MK2 weapons)
- Improvement. Make arrival of all unit less chaotic, especially in a crowded location (mostly in the city area)
- Improvement. Tweak the holding duration for dismissing all backups. It's slightly shorter now
- Fixed Bug. When treating victim in the car, there's sometimes a weird animation or reaction (e.g. medic is thrown up to the sky)
- Fixed Bug. Sometimes the backup passengers don't return to the vehicle after they're dismissed
- Fixed Bug. Sometimes the backup leader just leaves passengers after being dismissed

v1.3.2.1
- Fixed an XML entry mistake in "DefaultRegions.xml" file

v1.3.2.0
- New Feature. You may choose the dog model name for k9 backup unit. Set the "k9_model" attibute within "VehicleSet". It is only valid for "K9LocalPatrol" and "K9StatePatrol" xml sections
  Available dog models are: "CHOP", "HUSKY", "SHEPHERD", "ROTTWEILER", "RETRIEVER". Please refer to "DefaultRegions.xml" if you want to use this new attribute.
- New Feature. Added PoliceSmartRadio buttons for Ambulance & Fire Department backups (If you're upgrading, make sure to copy those 2 new button icons into PSR folder)
- Improved K9 AI to react when suspect attack cops or player
- Major Performance tuning by tweaking some RPH API
- Fixed Bug. Sometimes setting vehicle extras (extra_1, extra_2, etc) did not work. It should be working fine now
- Fixed Bug. Sometimes when requesting pursuit backup too soon, LSPDFR crashed
- Fixed Bug. Applied some potential tweaks to fix intermittent crash when calling backup

v1.3.1.0
- New Feature. Added dismiss all key parameter in the .ini file ("DismissAllBackupKey")
- New Feature. If a backup vehicle model has multiple liveries, it will be randomized by default
- New Feature. Now a firetruck has 4 firemen. Previously it only had 2 (remember that FireTruck & Ambulance crew number is not affected by "pax" attribute in the xml file)
- Improved the holding key detection, so it won't be accidentally triggered when user just presses it
- Improved fireman AI to stop the fire. They will spread to different fire points instead of working at the same location
- Fixed Bug. Ambulance paramedic and firemen always put the saved ped into the right passenger seat.
- Fixed Bug. Now the CPR procedure by paramedics & firemen will be applied to human only

v1.3.0.0
- New Feature. Implement built-in Ambulance unit and AI. You may customize the unit in the xml file under "Ambulance" backup type tag. (See "DefaultRegion.xml" for reference)
  Ambulance unit will tend to the bodies and try to perform CPR
- New Feature. Implement built-in Fire Department (Fire Truck) unit and AI. You may customize the unit in the xml file under "FireTruck" backup type tag. (See "DefaultRegion.xml" for reference)
  Fire Department will find any fire sources and try to stop them. They can also tend to the bodies and perform CPR
- New Feature. Added own "Panic Button" for PoliceSmartRadio, where you can customize the units being dispatched in the .ini file (parameter name: "PanicButtonUnits")
- New Feature. Added key to dismiss all backup units at once. You can do that by HOLDING "ENTER" key
- New Feature. The Code 3 backup buddies (passengers) will be spreading out. Only the team leader is following the player
- New Feature. The Pursuit Backup will stay with the player after the pursuit finished (except air unit)
- Fixed Bug. Sometimes, multiple buddies will have racing condition (back and forth) when trying to "guard" a suspect
- Fixed Bug. The vehicle is no longer disappeared when the team leader is dead. The next available member will try to drive it during dismissal
- Fixed Bug. Sometimes, when user already have "prop_hats" set to "0" (means no hat), the ped is still wearing it
- Fixed Bug. Unable to request backup in "San Andreas" area (near Vespucci Beach) because the units always despawned

v1.2.4.0
- Fixed glitch during felony stop when the police buddy draws the wrong non-lethal weapon 

v1.2.3.0
- Added new "random_props" attribute (True or False) in "Ped" node which will randomize all props (hats, glasses, earpieces, and watches) for the backup ped
- Fixed bug. Sometimes LSPDFR crashes during menu navigation when you have too many "Special Units"
- Major Performance tweak which should minimize lags and FPS drops when calling multiple units

v1.2.2.0
- Fixed bug. When using controller and perform traffic stop, sometimes LSPDFR crash or pulled over subject got dissapeared after player select an option (press A) from the menu
- Fixed rare issue. Sometimes traffic stop menu is always displayed when opening the menu, even though there's no traffic stop session in progress

v1.2.1.0
- Improved interaction. If a unit consists of several cops (e.g. SWAT), you can just dismiss the group leader or driver (with the biggest blue blip) to dismiss them all
- Fixed Issue when it could not assign 7 passengers into a large police vehicles (e.g. RIOT)
- Added missing "Ambulance" & "Fire Truck" options into the menu. It will call the units from LSPDFR vanilla backup
- Fixed Bug. Sometimes the helicopter for pursuit backup is spawned in the middle of the road

v1.2.0.0
- New Feature. Added new spawn_distance attribute into "VehicleSet" which will override the default spawn distance (please see examples in the xml files)
- New Feature. Added new "Special units" xml customization which allow you to add your own unit into the menu. 
  For your reference, I put 2 examples in "SpecialUnits.xml" file (Police Bike and Supervisor)

v1.1.0.0
- New Feature. Now you can define the weapon customization in the xml file by 3 groups (non-lethal, handguns, and long-guns). Read the XML file for more detail.
- Fixed issue. Sometimes the police buddy cannot detect the threat if it is too far away
- Fixed bug. Sometimes a unit with police passengers cannot assign the car driver after dismissal because the leader is dead

v1.0.0.0
- Initial release
