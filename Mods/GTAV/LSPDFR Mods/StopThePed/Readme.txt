=======================================================
GTA V - LSPDFR - Stop The ped
Version 4.6.0.0 | Developed by BejoIjo Productions
Copyright (c) 2019 All Rights Reserved
=======================================================

PREREQUISITES:
--------------
1. Rage Plugin Hook v0.57 alpha
2. LSPD First Response v0.4 by G17
3. Traffic Policer v6.13.7.0 by Albo1125 (required to have ped observation on alcohol/narcotics)
4. Police SmartRadio v1.1.1.1 by Albo1125 (required to request police transport, tow, coroner, and insurance services)
5. VocalDispatch v1.6.0.0 by turbofandude (optional if you want voice command to call police transport, tow, coroner, and insurance services)
6. Rage Native UI v1.6.3.0 by alexguirre
7. Ultimate Backup v1.0.0.0 by BejoIjo


OVERVIEW:
---------
Basically, "Stop The Ped" is a plugin which contains replacement for the same functionality in vanilla LSPDFR.
But, there's a very annoying bug which sometimes prevents you to stop the ped by holding the "E" key.
This plugin provides almost the same functionality which allows you to stop the peds.
There's also an additional stop at gunpoint feature which have softer arrest gesture (kneel down instead of kissing the ground on vanilla LSPDFR).
Also available are the additional features to pat down the suspect and provide gun permit.


INSTALLATION:
-------------
- Copy the contents of "Plugins\LSPDFR" in this package to: "GTA V directory\plugins\LSPDFR"
- If you haven't had "RageNativeUI.dll" in your "main GTA V folder", don't forget to copy the file from this package
- If you already have newer "RageNativeUI.dll", please keep using it. No need to overwrite the file
- Please open and edit "StopThePed.ini" file, if you want to replace the keyboard key or controller button bindings


HOW TO USE:
-----------
- To stop the nearest ped:
  - When using keyboard, you just need to DOUBLE PRESS the "E" key
  - When using controller, DOUBLE TAP the "DPadRight" controller button
- Come closer to the stopped ped and press "E" key to bring up "Stop The Ped" menu.
- You may close the menu at anytime by pressing "Backspace" or "Esc" key on keyboard, and "B" button on the controller
- And you may bring back the menu (when in range) using "E" key or "DPadRight" button
- To perform stop at gunpoint, just aim the ped with your gun when performing ped stop (aiming while double press "E" key)
- To target a ped as pursuit suspect, just aim the ped with your gun and double tap "T" key or "DPadUp" button
- To open Context Menu, you have to stand near ped or vehicle and press "G" key or controller button "DPadLeft + A"
- To perform "Quick Grab" on any peds, press "LControl + T" key or "DPadLeft + B" button
- To tackle ped during foot pursuit, press "Backspace" key or "B" button
- To boost player sprint/run speed, press "Enter" key or "Y" button (the boost effect will last for 3 seconds by default)


FEATURES:
---------
- Stop the ped:
  * Stop the nearest ped peacefully. (only one ped at a time)
  * Stop the ped at gunpoint. (while aiming your weapon at the ped)

- You may stop the next nearest ped by doing the same command

- Using menu, you may choose:
  * Ask ped's ID card to see their ID and any gun permit when the ped has it
  * Issue warning to the ped which will dismiss him/her
  * Question the Ped
  * Follow Me command to make the stopped ped following you
  * Take the ped from behind (grab). You can also perform "Quick Grab" on any peds using "LControl + T" key or "DPadLeft + B" button
  * Pat Down the ped to search for any illegal items
  * Conduct Breathalyzer test
  * Conduct Drug swab test
  * Arrest the ped
  * Release the arrested ped.
  * Ask ped to kneel down or get up
  * Request nearby Police Buddy (from Ultimate Backup) to watch the ped
  * Request escort vehicle for the ped (Taxi, Uber, Ambulance, or Police Transport)

- The stopped ped will have a yellow blip with "human" icon. The arrested ped will have the red blip

- Stop the ped on the vehicle. The ped will comply as long as the vehicle is not moving

- The ped may flee if we attempt to arrest them. You may set the probability in the .ini file

- Notify the player when the ped is intoxicated (alcohol or narcotics)

- When you walk close to any police car, the arrested ped who is following you or being grabbed, might be put into the vehicle using menu

- You may ask the arrested ped to get out of the car and follow you using "E" key

- This plugin will also injects "Stop The Ped" menu into all peds who are arrested using LSPDFR vanilla gunpoint stop or ped stop (configurable in the .ini file)
  * The peds arrested by your police buddies will also be affected  
  * With this feature, you can perform all "Stop The Ped" actions such as "Pat Down Ped" on all arrested peds. Enjoy!
  * While using "Injects Stop The ped menu" above, please make sure to wait a few seconds after the arrest to allow this plugin processing the ped

- Compatible with Computer+. When you give the citation (using Computer+ shortcut key) to stopped ped, they will be dismissed automatically

- Player may ask Police Buddy from "On Scene Backup" to pat down, perform tests, or arrest the suspect (requires "On Scene Backup" plugin).
  Just make sure there's a police buddy watching for the stopped ped, and then select "By My Buddy" on the left/right selector.

- You can trigger a pursuit by just aiming the ped with your gun and double press "T" key or "DPadUp" button

- Using PoliceSmartRadio or Vocal Dispatch, you can call the following services:
  * Police Transport
  * Tow service
  * Coroner service
  * Animal Control
  * Insurance service

- You can also self transport a suspect to nearest jail. When you choose to escort suspect by yourself to cell, 
  your partner will automatically lock the cell door for you after you deliver the suspect. (after you get out of the cell)

- Make realistic ped age based on the model. You will no longer see a 63 years old chick (when checking her ID). (If you install STP, you won't need "Proper Ped Age" anymore)

- Integrated "Ped Calming" function from "Make Peds Calm Again" plugin built into Stop The ped (if you already had MPCA, you may remove it). 
  Note: It will be disabled when you run on LSPDFR 0.4 because LSPDFR 0.4 has already had its own calming ped feature.

- New Context Menu. When you approach and stand next to any Ped or vehicle, you may open this menu by pressing "G" key or controller button "DPadLeft + A".
  With this menu, you can:
  * Stop the ped, which will make the ped stopped and bring the main stop the ped menu
  * Ask the ped to go. This is needed if the peds are hanging out and you need to disperse them.
  * Drag the ped body (if the ped is injured or dead and laying on the ground)
  * Perform CPR
  * Search/frisk the dead ped body
  * Search the vehicle
  * Call Coroner (for dead ped)
  * Call Animal Control (for dead animal)
  * Call Tow service for abandoned vehicle
  * Call Insurance Service for damaged vehicle
  * Slow down traffic
  * Stop traffic

- You can tackle the ped in pursuit while you chasing them (default key="Backspace" button="B")

- You can run faster by using sprint boost feature so you won't be outrun by those criminals anymore! (default key="Enter" button="Y"). You can also set the boost duration (default 3 seconds) in the .ini file.

- Stop The Ped "Persistency" module will prevent the despawned of nearby dead bodies and empty vehicles by the game engine. This will help you to manage the crime scene with comfort. 
  * The suspect's car shall not be despawned out of no where anymore, so you can still conduct vehicle search or call tow truck to impound it
  * The dead suspect body shall not be despawned and pop off from the scene anymore, so you can still investigate it, call ambulance, or call coroner to take care of them
  * The parked vehicles will also be affected by this "Persistency" module. To maintain game performance, they will still get despawned after very far distance from the player
  * This feature can be disabled/enabled by setting the configurable parameters in the .ini file ("EnableDeadPedPersistence" and "EnableEmptyVehiclePersistence")


PAT DOWN THE PED:
-----------------
- The items list and probabilities are configurable in the .ini file.
- It is also compatible with these third party search plugin:
   - Search Warrant by @Darkmyre
   - Police Search by @FtDLulz
- When you previously searched the ped using above plugins, STP pat down will also return the same result. 
- But if the ped hasn't been searched by any of those plugins, STP will randomize the search result by picking from configured items in the .ini file (or from those third party plugins item files)
- If you are a callout developer who want to inject some items into the ped, you may use those third party search plugins API to do it. 
  "Stop The Ped" will automatically recognize and display the items.


API FOR CALLOUTS DEVELOPERS:
----------------------------
A. Pat Down items
   You may inject items into "Ped.Metadata.searchPed" variable (similar with "Search Warrant" plugin)

   Example: myPed.Metadata.searchPed = "~r~handgun~s~, ~y~pocket knife~s~, ~g~wallet~s~";
   Please notice that the ~r~, ~y~, and ~g~ are for text color of red, yellow, and green. Whether ~s~ is for text default color.

B. Vehicle Search items
   You may inject items into vehicle metadata variables (similar with "Search Warrant" plugin)
    - Vehicle.Metadata.searchDriver 
    - Vehicle.Metadata.searchPassenger 
    - Vehicle.Metadata.searchTrunk 

   Example: veh.Metadata.searchDriver = "~r~assault riffle~s~, ~y~machete~s~, ~g~a pair of shoes~s~";
   Please notice that the ~r~, ~y~, and ~g~ are for text color of red, yellow, and green. Whether ~s~ is for text default color.

C. Gun permit
   There are 3 metadata variables you could inject:
    - Ped.Metadata.hasGunPermit -> it's a boolean typed variable (true/false) to determine whether the ped has gun permit or not
    - Ped.Metadata.gunLicense -> it's a string typed variable. You're free to put any string there. Assigned values by this plugin: "Handguns", "Long guns", "Handguns and Long guns"
    - Ped.Metadata.gunPermit -> it's also a string typed variable. You're free to put any string there. Assigned values by this plugin: "Concealed" and "Public"

D. Alcohol and Drug on Peds
   You may inject the ped metadata variables to indicate whether the ped is under alcohol or drug influence
    - Ped.Metadata.stpAlcoholDetected
    - Ped.Metadata.stpDrugsDetected

   Example: myPed.Metadata.stpAlcoholDetected = true;
            myPed.Metadata.stpDrugsDetected = false;

E. You can call PT, Coroner, Tow Truck, Insurance, and Animal Control using "StopThePed.API.Functions" module in "StopThePed.dll" file.
   Please note that to call those APIs, you should have a wrapper static class, similar with all popular plugins API.



Please feel free to contact me through LSPDFR forum or download's comment section for any issue you encountered with this plugin.
Happy patroling! Enjoy! 


SPECIAL THANKS TO:
------------------
- Albo1125 for all your plugins which make LSPDFR very joyful!
- alexguirre for all your open source modules and plugins for LSPDFR
- manu450 for your time as this plugin's BETA tester


VERSION HISTORY
---------------
v4.6.0.0 (latest)
- New Feature. Added a new "Persistency" module to prevent the despawned of nearby dead bodies and empty vehicles by the game engine. 
  This will help you to manage the crime scene with comfort. 
  * The suspect's car shall not be despawned out of no where anymore, so you can still conduct vehicle search or call tow truck to impound it
  * The dead suspect body shall not be despawned and pop off from the scene anymore, so you can still investigate it, call ambulance, or call coroner to take care of them
  * The parked vehicles will also be affected by this "Persistency" module. To maintain game performance, they will still get despawned after very far distance from the player
  * This feature can be disabled/enabled by setting the configurable parameters in the .ini file ("EnableDeadPedPersistence" and "EnableEmptyVehiclePersistence")
- Improvement. Now flatbed tow truck will be able to take any non-road vehicles (e.g. planes, helicopters). If it's too big, it will be despawned to simulate the removal
- Improvement. Tuned up some codes to improve responsiveness when opening "Context Menu" (default "G" key)
- Fixed Bug. The K9 backup unit cannot be recruited as Police Transport when they are nearby
- Fixed Bug. Tow truck sometimes cannot attach the tow head to large vehicles (e.g. bus, truck) 


v4.5.6.0
- Improvement. Tuned drivers AI on support units (e.g. Police Transport, Coroner) to avoid crashing into other vehicles
- Adjustment. Changed the color of drop off point cylinder marker to orange (to distinguish it from LSPDFR marker)
- Adjustment. Moved jail drop off location on Rockford Hills, so it's not overlapped with LSPDFR marker
- Fixed Bug. When requesting Police Transport from nearby backup unit, motorbike unit should not respond to that request
- Fixed Crash. When searching the dead body, while coroner arrived and removed the body

v4.5.5.0
- Improvement. Finally made "Traffic Control - Stop Traffic" 100% effective now, while still allowing emergency vehicles to pass through
- Improvement. When you ask nearby backup unit with cop passengers (from Ultimate Backup) as a Police Transport, the cop passengers will return to the vehicle instead of being left behind
- Added API for developers to access and call services within Stop The Ped

v4.5.4.0
- New Feature. When Ultimate Backup is installed, The Coroner and Police Transport (Ped and vehicle) configurations will be taken from Ultimate Backup xml file (requires the latest Ultimate Backup)
- Improvement. Tweaked the spawn logic to find the best spawn point for all backups on a complex location (e.g. highway intersection with underpasses and flyovers)
- Improvement. Tweaked the immediate spawn location to reduce a messy teleporting (when player is holding backspace)
- Improvement. When the dead ped is still in the car, Coroner will take the dead ped out of the car first before performing the coroner procedure
- Improvement. Reduced animation hiccup when the player is grabbing the ped and when the ped is in arrest posture
- Improvement. Made "Stop Traffic Control" more effective while still allowing emergency vehicles to pass through
- Fixed Bug. During CPR procedure and drag the ped body, now the ped will look absolutely dead. (e.g. no more blinking eyes and complaining speeches)
- Fixed Bug. Sometimes when you dismiss peds, they just standing still (do not go away)
- Fixed Rare Crash when stopping the car occupant peds (double tap "E" key) during traffic stop
- Fixed Rare Crash when performing CPR

v4.5.3.1 (latest)
- Improvement. When you perform STP "gunpoint arrest" to a ped holding a weapon, they now should drop the weapon to the ground and then put the hands up
- Improvement. Some variable tunings and tweaks to improve gameplay
Note: If you're upgrading, you just need to replace the old "dll" file with the new one.

v4.5.3.0
- Fixed Bug. Sometimes you cannot go to Jail Drop Off while you already have suspect in the back of the car
- Fixed Glitch. Sometimes the suspects become invisible/disappeared after Police AI arrested them
- Improvements. A bunch of compatibility tweaks and adjustments to support new behaviors of LSPDFR 0.4

v4.5.2.0
- Improved Gameplay. Now Stop The Ped will take over arrested ped triggered by vanilla LSPDFR stop arrest action (holding "E" key)
  Note: If you want to control ped who already controlled by LSPDFR interactive menu (e.g. after you asked traffic stop ped get out of the car), you can control and have STP menu by arresting the ped
- Added Parameter to set the intensity of "sprint boost". The new parameter name is "SprintBoostIntensity". (default value is "50" out of "100")
- Fixed Bug. Sometimes PT officer doesn't have voice when it is an MP freemode ped model

v4.5.1.0
- New Feature. Integration with Ultimate backup to provide the cops and paramedic ped models (which mean they can be an MP freemode ped)
- Fixed Bug. Sometimes context menu cannot detect vehicle to search and tow
- Fixed Typo. The default parameter for "GunpointPursuitModifierKey" in the .ini file should be set to "None"

v4.5.0.0
- New Feature. There's now a headshot (close up photo) of the ped on the "ID Card" when you're asking for the ped's ID
- New Feature. Now, the arrested ped sitting position will be leaning forward when you transport them (also by Police Transport)
- New Feature. Now you can tackle the ped in pursuit while you chasing them (default key="Backspace" button="B")
- New Feature. You can run faster by using sprint boost feature so you won't be outrun by those criminals anymore! (default key="Enter" button="Y"). You can also set the boost duration (default 3 seconds) in the .ini file.
- Improvement. When you call ambulance escort for an arrested ped, the medic will be accompanied by a cop
- Improvement. Better handling to ask arrested ped get out of the vehicle when there are 2 peds inside the vehicle
- Improvement. To enable right menu scroll using controller, the StopThePed button (default "DPadRight") will not close the menu.
- Improvement. Now the arrested ped (with red icon blip) will be dismissed and despawned when they're too far away from player (more than 500 meters)
- Improvement. Player will only shout when double tap "E" key and there's a target ped to stop
- Fixed Crash. Added error handling when the ped is deleted by LSPDFR or other plugins
- Fixed Glitch. Sometime when we try to arrest the stopped ped, it's unsuccessful and the ped walks away

v4.4.3.0
- Fixed Crash during LSPDFR Traffic Stop session caused by proper ped age updates
- Fixed Glitch when drag dead body, sometimes the ped is running away and rejoin pursuit
- Fixed Glitch when performing CPR on dead/injured ped, sometimes the ped is running away and rejoin pursuit

v4.4.2.0
- New Feature. Now "Context Menu" can be accessed when the player is inside a vehicle to call for tow truck, insurance or perform traffic control
- Added support for ultimate backup new felony stop arresting ped mechanics
- Fixed Bug. Sometimes "Animal Control" service doesn't detect and tranquilize vicious animal

v4.4.1.0
- Improved take over arrest timing during pursuit, so the ped will still be counted as arrested in pursuit stat (LSPDFR 0.4)
- Improved the Police Transport officer grabbing and walking when return to vehicle with the suspect
- Tweaked cuff sound timing when arrest at gunpoint using STP.
- Fixed Bug. Sometimes Police Transport officer ans suspect are freezing when they try to go to the PT vehicle
- Fixed Bug. Sometimes the ped that already called for transport can still get another transport
- Fixed Bug. The "Context Menu" cannot be accessed while the player is in "First Person" view mode.
- Fixed Bug. Sometimes arrested ped's handcuff disappeared after getting arrested by player using vanilla LSPDFR takedown (LSPDFR 0.4)
- Fixed Rare Crash when calling a tow truck (with hook) and player just go and leave the scene without waiting until the target vehicle being towed

v4.4.0.0
- Added support for LSPDFR 0.4
- New Feature. Added "vehicle search" function on the "Context Menu" (press "G" to open the menu)
- New Feature. Integrated "Make Peds Calm Again" to be built into Stop The ped (if you already had MPCA, you may remove it). Note: It will be disabled when you run on LSPDFR 0.4
- New Feature. Police Transport officer will grab the suspect with both hands to the PT vehicle
- New Feature. Added ground markers (blue cylinder) on jail drop points to help you find it.

v4.3.2.0
- Fixed Bug. In some RPH version, the traffic control "stop traffic" function doesn't work
- Fixed Bug. Sometimes Coroner cannot detect dead ped after the ped is taken care by UB ambulance medic. This fix requires the latest "Ultimate Backup" plugin
- Added parameter for Animal Control Service to put the incapacitated animal into the back of the truck or not.

v4.3.1.0
- Fixed Crash. Sometimes it crashed when dropping off the arrested suspect to jail by partner
- Fixed Bug. Sometimes Stop The Ped stopped functioning after a few minutes (e.g. no reaction when double tapping "E" key)
- Fixed Bug. Sometimes the arrested ped in the Police Transport is disappear or leaves the vehicle
- Fixed Bug. After player put the suspect into cell and left the jail, suspect was not dismissed (the icon is still existed on the map)
- Fixed Bug. When player put non-arrested ped into police car and get them out of vehicle, the handpose was like arrested ped

v4.3.0.0
- New Feature. Added Traffic Control function to stop or slow down traffic into Context Menu (default "G" key to open) 
- New Feature. Added Animal Control Service which can neutralize wild animal (tranqualize) and handle dead animals
  *if you upgrade from old version, there's a new animal control icon to be copied into PoliceSmartRadio and new "AnimalControlService" entries in StopThePed.ini file
- Improved Gameplay. Made Police Transport and transported suspect return to nearest jail drop off
- Improved Gameplay. Arrested ped will never be despawned when far away from player. Useful when you have to leave arrested ped to chase for another suspect
- Improved Gameplay. Increased (doubled) the effective range for triggering gunpoint pursuit (aiming while double tap "T" key)

v4.2.9.4
- Improvement. In jail drop off, when we have 2 arrested suspects in the car, they will both be escorted at the same time into the jail (by player or by partner)
- Improvement. A few codes tweaking and tuning to improve performance
- Improvement. Make arrival of all supporting backup units less chaotic, especially in a crowded location (mostly in the city area)
- Fixed Bug. San Andreas area (near vespucci beach) is now grouped as city area (Police Transport). (previously it was treated as county area)

v4.2.9.3
- Added Handling. When one of Coroner is dead, the other coroner buddy will still proceed collecting bodies (instead of getting despawned)
- Added handling. When calling Police Transport, but then player releases the suspect, transport unit will not get despawned. They will just be dismissed normally
- Tweak CPR procedure animation by removing the "mouth-to-mouth" CPR animation (because it's no longer required in real life)
- Took out the "CPR successful rate" parameter from the .ini file. The rate is now determined by the cause. For example, knocked out by fist has higher successful rate than shot by firearm

v4.2.9.2
- Added police transport models in the .ini file parameters. The new paramaters are: MaleOfficerCity, FemaleOfficerCity, MaleOfficerCounty, and FemaleOfficerCounty
- Added new .ini file parameter to force transport officer ped spawned using model from vehicles.meta. The parameter name is ForceVehiclesMetaPed
- Fixed bug where sometimes a helicopter pilot cop is recruited as police transport and it caused despawn issue
- Improved plugin stability by adding some crash prevention handlers

v4.2.9.1
- New Feature. Now you are allowed to put the ped into a police vehicle with back passenger doors (e.g. POLICET)
- Improved Key Control. Now you need to DOUBLE TAP the "T" key while aiming on the ped to trigger pursuit ped. I changed it to "double tap" to prevent triggering it by accident. (previously was only single tap)
- Improved Gameplay. Now you can call tow service and insurance when you're inside your police car
- Improved Ped Handlings. Prevent the coroner unit getting despawned because the deadbody is it taken over by other plugin (conflict)
- Fixed External Issue. Sometimes the ped re-enter the vehicle after being stopped (Double tap E key). There's an additional handler to prevent this to happen
- Many game variables and constants tweaks to improve the overall gameplay

v4.2.9.0
- Added confirmation menu when calling "Insurance Service" to take police vehicle
- Make the insurance agent wearing helmet if target vehicle is a bike
- Improved logic to call nearest cop for police transport, so the nearest to the player should be chosen
- Fixed minor bug. Sometimes when calling "Tow Truck", wrong vehicle is selected instead of the one closest to player

v4.2.8.0
- Fixed crash after pat down when player is not using "Search Warrant" as 3rd party search plugin
  (you just need to replace the StopThePed.dll file)

v4.2.7.0
- New Feature. You may put any ped into police car for non-arrested (free) peds. This will allow you to put any victim or witness for safety inside your car. (The ped should be in STP control)
- Added parameter to force search result to be displayed in full screen
- Tweaked the take over arrest during pursuit timing to prevent the Police AI shooting at the ped
- Increased the recruit range of nearby police unit for transporting the suspect
- Added notification information when the transport vehicle is despawned because vehicle is not valid (It must have at least 4 doors)
- Removed unnecessary log entries which might mislead the context when crash happens
- Added handling to prevent another plugin taking over the ped (e.g. stealing player car)
- Added new plugin update checking. The plugin will notify you on loading time if there's a new version available

v4.2.6.0
- New Feature: Added "Search The Body" function to the Context Menu for dead peds. It will give you similar result like "Pat Down Ped"
- Changed the key to teleport the vehicle from "Press Backspace" to "Hold Backspace"
- Improved codes to have the menu quickly available after stopping the ped
- Fixed bug. Sometimes player cannot stop the ped while on the 1st person view

v4.2.5.0
- New Feature: Added "Vocal Dispatch" integration to call police transport, coroner, tow truck, and insurance agent
- New Feature: Coroner unit will also mention the cause of dead
- Improved configuration (in the .ini file) for insurance vehicle model to accept multiple values
- Fixed minor bug. Sometimes if player "issues warning" or "releases arrested ped" from traffic stop driver/passenger, the ped doesn't return to the car.
- Adjusted some in-game constants and variables to improve gameplay

v4.2.0.0
- Added "Quick Grab" to Context Menu and game shortcut ("LControl + T" key or "DPadLeft + B" button)
- Added first aid (CPR) procedure to the Context Menu for dead peds
- Fixed bug. Where LSPDFR vanilla transport still picks the suspect, after STP takes over arrested ped by pursuit AI.
- Fixed glitch. The tow truck driver disappear for a second when tow ruck arrived
- Fixed crash. While player is dragging dead ped and call EMS

v4.1.2.0
- Added controller support for drag body (use your analog stick "left" or "right" to navigate and "down" to stop)
- Added capability to drag fellow cop's dead body
- Added police transport siren and sound states (arrival & departure) in configuration .ini file. (make sure to put the new .ini file)
- Fixed bug. Inconsistent dead body detection when trying to open context menu
- Fixed bug. Sometimes arrested ped get uncuffed when doing pat down
- Fixed bug. The insurance service driver is driving like crazy during arrival

v4.1.1.0
- Fixed rare tow truck crashes caused by GTA V bug. Sometimes the crane on the tow truck is missing which caused the game to crash.
  Finally I found a workaround for this issue and force the crane to exist. Sorry for very quick update.

v4.1.0.0
- New Feature: Drag injured or dead ped body. You may access this feature using new interactive Context Menu. Use "A" or "D" keys to navigate, and "S" key to stop dragging.
- New Feature: Interactive Context Menu on ped and vehicle. When you approach and stand next to any Ped or vehicle, you may open this menu by pressing "G" key or controller button "DPadLeft + A" (configurable).
  With this menu, you can:
  * Stop the ped, which will make the ped stopped and bring the main stop the ped menu
  * Ask the ped to go. This is needed if the peds are hanging out and you need to disperse them
  * Drag the ped body (if the ped is injured or dead and laying on the ground)
  * Call Coroner (for dead ped)
  * Call Tow service for abandoned vehicle
  * Call Insurance Service for damaged vehicle
- Added feature to fix ped age into STP, similar with "Proper Ped Age". (you don't need "Proper Ped Age" plugin anymore)
- Added configurable spawn distance to the .ini file
- Turn off siren and sound when Police Transport vehicle is leaving
- Fixed crash. During configuration file loading, when user's window regional setting is not set to US, STP will crash during loading time
- Fixed bug. The escort vehicle never reached the target ped passenger
- Fixed rare crash when calling PT for 2 suspects in separate vehicles

v4.0.0.0
- New Feature: You can request police transport for the arrested ped (using PoliceSmartRadio)
- New Feature: You can transport the suspect by yourself to the nearest jail
- New Feature: You can request tow service to pick up the vehicle (using PoliceSmartRadio)
  You will be given tow service options: Small or large tow truck, flatbed truck, or small pickup truck (for bike)
- New Feature: You can request coroner service to take the dead bodies (using PoliceSmartRadio)
- New Feature: You can request insurance service to pick up the vehicle (using PoliceSmartRadio)
- New Feature: You may make a ped as pursuit target by pointing a ped with gunpoint and press "T" key or controller's "DPadUp" button
- Fixed minor glitch. When questioning the arrested ped, animation was still played which is not necessary
- Fixed glitch. The Police AI sometimes are shooting at the suspect after he/she got arrested
- Fixed glitch. Traffic cones or barriers from "Traffic Policer" become peds when player performing stop the ped (press "E" key twice)
- Fixed rare crash. When ped is being grabbed and player calling Police Transport

v3.0.0.0
- Major revamped on codes and algorithm for taking over arrested suspect (by AI or player) by implementing "soft ped reset".
  With the new "soft ped reset" method, callouts can still interact with suspect (e.g. callout questioning/speaking) after they got arrested and taken over by STP.
  On the previous version, the callout can not interact with the ped anymore after they got arrested.
- Increased the radius of suspect arrested by Police AI that can be taken over by STP
- Increased the dismissal (despawn) distance on stopped ped or arrested ped.
- There will be no more police unit that come and go after the Police AI arrested the suspect. It's automatically cancelled by STP
- New cool arrest animation when arresting the suspect using STP stop at gunpoint (double tap E while aiming). Try it yourself, you'll like it :)
- Increased the distance slightly of STP stop on gunpoint to improve gameplay
- Fixed minor glitch. When performing breathalyzer & drug swab tests, the player's legs were moving weirdly
- Fixed glitch on grab ped. Sometimes when player is running, the suspect does not follow to run
- Improved grab ped. Make it faster for the player to grab the ped and start moving
- Improved Menu logic. The menu will automatically refreshed on the fly when a buddy is watching the ped

v2.1.2.0
- Fixed bug. Pat down search result is not displayed when ForceUsingOwnItemList is set to "yes" and you have third party search plugin installed

v2.1.1.0
- Added more ped's hands-up variations during pat down process (e.g. hands behind the head)
- Fixed bug. The Stop The Ped item list wasn't loaded properly caused blank pat down results

v2.1.0.0
- New feature. You can question the ped using the STP menu. You can also customize the answers on the .xml file
- New feature. The ped now might flee on other interactions. Previously ped might flee only when getting arrested. (the probability is configurable in the .ini file)
- New feature. When the ped is feeing, they might also attack you. Beware! ;)
- New feature. The Ambulance escort can be requested for arrested ped (ped with cuff).
- The original Stop The Ped item list is now moved to xml file. make sure to put the file into "LSPDFR\StopThePed\" folder
- Added configurable vehicle models for taxi, uber, and ambulance escort (in the .ini file)
- Fixed bug. When "Windows regional setting" is set to a region which uses comma as decimal separator, the breathalyzer won't display the result
- Fixed bug. The escort car sometimes move backwards wildly after being teleported (because of timeout)

v2.0.0.0
- New feature. Stop The Ped is now fully integrated with the item files from "Search Warrant" and "Police Search" plugins. STP will automatically detect and use the item list from those plugins for "Pat Down Ped" results. Enjoy!
- New feature. Added menu options to request escort vehicle for the ped (Taxi, Uber, or Ambulance)
- New option in the menu to request nearby Police Buddy (from "On Scene Backup" or "Traffic Stop Backup" plugin) to watch current stopped ped, when available. (OSB and TSB latest versions are required)
- Added error handling to clean up entities and blips when LSPDFR crashes
- Fixed minor glitch (cut animation) when asking the buddy to release ped from handcuff

v1.8.2.0
- Added new variety of alcohol and drug observation results
- Added and tweaked player speech/shout on variety of situation (e.g. when stopping ped, arresting, etc.)
- Tweaked pat down animation to be slightly faster, so you won't get bored waiting for it ;)
- Improved menu. The "By Myself/By My Buddy" option will only be shown when there's at least one active Police Buddy (from OSB or TSB) watching the ped

v1.8.1.0
- Improved animations when performing breathalyzer and drug swab tests
- Improved player and police buddy position (when using On Scene Backup) during breathalyzer and drug swab test
- Fixed glitch when conducting breathalyzer or drug tests, the suspect might be moving away

v1.8.0.0
- Added new feature to ask Police Buddy from "On Scene Backup" to pat down, perform tests, or arrest the suspect (requires "On Scene Backup" plugin)
- Fixed bug. Sometimes the game clones the ped when we try to arrest them
- Added more pat down items in the .ini file

v1.7.1.0
- Fixed bug. Sometimes STP Menu does not show up even though the ped is already stopped and facing the player
- Fixed bug. Sometimes the blip map icon does not disappear after issuing warning to the ped

v1.7.0.0
- Changed flow. Player now should use menu to put the grabbed or following ped into the police car
- Changed flow. Now after exiting the police car, the ped will be waiting (standing) instead of following the player 
- Improved transition handling when 2 or more stopped peds are standing close each others
- Added configurable alcohol level and unit parameters for breathalyzer result
- Fixed bug. Sometimes vehicles or peds near the stopped ped disappear when player releasing the ped

v1.6.9.1
- Fixed rare freeze issue (probably only on slower PC) after arresting ped using vanilla LSPDFR
- Fixed bug when take over arrests from vanilla LSPDFR didn't work when ped blip is disabled on .ini file setting

v1.6.9.0
- Fixed crash when suspect is entering the car and police transport arrived
- Fixed crash after arresting suspect on code 3 callouts road rage

v1.6.8.0
- Fixed crash while the ped is being grabbed and player calls for police transport
- Improved the way suspect entering the police car from grab or follow positions
- Added optional modifier key and modifier button into the .ini file

v1.6.7.0
- Added new feature to take the ped from behind (grab). The ped will automatically enter the police car when you walk near one
- Added help notifications to inform the player any actions being performed (e.g. arrest, release)

v1.6.6.0
- Added alcohol test (breathalyzer) and drug swab test (drugalyzer). It requires Albo's "Traffic Policer" plugin
- Fixed bug, now you can perform vanilla LSDFR stop at gunpoint while the ped is stopped by STP
- Fixed bug, now you can perform vanilla LSDFR stop at gunpoint while the ped is kneeling after stopped by STP at gunpoint 
- Fixed menu interaction, now it will be closed after asking ped ID

v1.6.5.0
- Fixed bug sometimes the back of the car is floating up when police transport takes the suspect from police car
- Fixed bug when some callouts override stopped ped and make it fleeing, suspect becomes immune to stop the ped command
- Fixed rare bug when sometimes suspect disappears after getting arrested (caused by some callout)
- Improved "follow me" to enter the car. Player will only open the car door if suspect that follows you is not far away
- Tweaked animation speed when performing pat down on suspect's legs

v1.6.4.0
- Added Computer+ compatibility. When you give the citation to a stopped ped, the ped will be dismissed automatically
- Tweaked timing to inject Stop The ped menu when ped is arrested using vanilla LSPDFR
- Fixed bug when injecting gun license and gun permit information

v1.6.3.0
- Fixed rare crashes when arresting suspect using LSPDFR vanilla normal and gunpoint stop
- Fixed dissapearing suspect after got arrested on burglary in progress (code 3 callouts)
- Prevent arrest collision with Police AI when performing Stop The Ped with gunpoint
- Improved compatibility with callouts that use interior scene (e.g. inside the house, apartment, trailer)
- Improved overall stability and smoothness. Enjoy!

v1.6.2.0
- Added new feature to inject Stop The ped menu into all peds who are arrested using LSPDFR vanilla gunpoint stop or ped stop (configurable in the .ini file)
  * The peds arrested by your police buddies will also be affected
  * Now you can perform all Stop The Ped actions such as "Pat Down Ped" on all arrested peds. Enjoy!
  * While using "Injects Stop The ped menu" above, please make sure to wait a few seconds after the arrest to allow this plugin processing the ped
- Improved pat-down animation. It is now performed a slightly faster than previous release
- Fixed bug on the pat down items don't sync on third party search plugins
- Fixed bug when you do a traffic stop and ask the peds to get out using traffic stop menu, the ped doesn't return to the vehicle when you release them
- Fixed crash when arresting suspect on burglary in progress (code 3 callouts)
- Resize blip icon on the map to be slightly smaller

v1.6.1.0
- Added feature if you already arrest the ped but haven't asked for ID, you will get the ID and possible Gun Permit after you pat the ped down
- Added API description for callout developers if they want to inject pat down items or assign gun permit
- Fixed bug sometimes the ped walks away when we pat them down
- Fixed glitch animation when you activated LSPDFR intimidation gesture (right SHIFT)
- Fixed minor glitches and crashes during variety of callouts (e.g. attempted heist, petty theft, etc.)
- Fixed Pat Down items is empty when user is using "Search Warrant" plugin
- Fixed bug when ped is not returning to the vehicle on a traffic stop after we release or give warning
- Many small fixes and adjustments to improve gameplay

v1.6.0.0
- New "Pat Down Ped" (frisk) feature. You may pat down the ped and find any suspicious items. The items list and probablities are configurable in the .ini file. 
  It is also compatible with "Police Search" and "Search Warrant" plugin.
- New "Gun Permit" feature. When you asked the ped's ID and the ped has a gun permit, it will also be displayed on the screen. (the probability is also configurable)
- Revamped menu flow. The menu will no longer auto-popup when approaching the stopped ped. You will need to press "E" key to bring it up
- Keep the door open after the arrested ped enter the police car. You may close the door or leave it open
- Added compatibility with Herocop plugin. You will not be able to stop the partner
- After you release or issue warning to a ped and the ped was a car passenger, if the driver seat on the car is unocupied, he/she will take it and drive the car off.
- Fixed bug on ped blip which sometimes disappear
- Improved the smoothness of the gunpoint stop animation

v1.5.2.0
- Disabled menu when ped is in police vehicle. If you want to have the ped to get out, just press E key when you're near the door
- Fixed player is stuck when pressing E after having the ped get in the vehicle
- Fixed rare crash when arresting ped on variety of situations
- Fixed ped search finds too many items after arresting the ped
- Fixed animation hiccup/glitch when performing stop at gunpoint during foot pursuit and when the ped is falling/getting up

v1.5.1.0
- Much improved Ped stop at gunpoint mode. Added some special workarounds to be compatible with popular callouts
- Added handling to drop the ped's gun on gunpoint stop mode
- Added ability to stop ped at gunpoint while the ped is in vehicle
- Added support and compatibility to Traffic Stop Backup felony stop mode

v1.5.0.0
- Added new gunpoint stop mode to arrest the ped at gunpoint with softer gesture than vanilla LSPDFR (kneel down and hands on the back of the head).
  To perform it, just aim the ped at gunpoint when performing ped stop
- Added handling so you will not be able to stop fleeing peds or peds in combat (on peaceful stop mode)
- Added handling to holster weapon before arresting or releasing ped
- Added condition to only accept menu selection when player is not running
- Fixed bug when fleeing, the ped is still in handcuff
- Fixed bug when releasing ped near a vehicle sometimes the vehicle disappears
- Fixed bug when arresting drunk ped, the arrest animation is not played properly

v1.4.1.0
- Fixed bug where the handcuff is left on the scene when the arrested ped gets transported
- Fixed crash when releasing ped while the ped is inside the jail
- Fixed bug that sometimes the ID card doesn't appear on the ped hand on "Ask Ped ID" command
- Simplify the menu structure by hiding the slots which are not relevant
- Observation report (alcohol & narcotic) will only be announced twice instead of always

v1.4.0.0
- Implement handcuff object which can bee seen visually when the ped is arrested
- Added "Follow Me" command to make the stopped ped following you
- Added ability to have the arrested ped automatically enter the police car when following you (when you walk close to any police car)
- Added ability to ask the arrested ped to get out of the car and follow you using "Follow Me" command
- Added command to make the arrested ped "kneel down" and "get up"
- Improved menu flow to simplify the command (e.g. arrest and release ped will use the same menu slot depends on situation)
- Added ambient curse voice when the ped is released
- Added collision handling on arrested ped which will make the ped get back to the "arrest" animation after being struck and fall

v1.3.0.0
- When stopping ped on vehicle, the ped will return to the vehicle when we release him/her from being previously arrested
- Added feature to make the ped fleeing. You may set the probability in the .ini file
- Added feature to notify the player when the ped is intoxicated (alcohol or narcotics)
- Added ability to bring back the menu (when in range) using "E" key or "DPadRight" button
- Fixed rare bug when asking for ID from drunk ped, the ped sometimes disappears (despawn)
- Make map blip for stopped ped configurable in the .ini file

v1.2.0.0
- Added ability to stop the ped on the vehice (as long as it is not moving)
- Replace the menu sound with the suitable one
- Fixed a bug that sometimes crashes when asking for ID

v1.1.0.0
- Added ability close the menu at anytime by pressing "Backspace" or "Esc" key on keyboard, and "B" button on the controller
- Stop The Ped Menu will not be displayed when the ped is on vehicle

v1.0.0.0
- Initial release
