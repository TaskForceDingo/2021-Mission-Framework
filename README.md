# 2019-Mission-Framework
Mission Framework for 2018

Welcome to the TFD Framework, Admins please vet and check code prior to addition, and before merging into master framework copy on github.

Mission makers please make changes you think will benifit the community add scripts you think will be useful.


Read below for complete changelog history.




24/08/2015 - Imperator
- Large amounts of changes/re-jigging of previous framework primarily to accommodate the return to TFAR and to make rookie user friendly.

27/08/15
- fixed fuck ups relating to commenting (now using notepad++!)
- tested casualty cap - working when executing custom code in array
- tested and created 1 additional parameter in desc.ext and init.sqf
- fn_f_casualtycap fixed in hpp and .sqf file to properly call
- created framework on VR map with ACE module settings place and an example DAC zone

09/09/15
- Tonny747 updated fn radio to have SW channels preset based on assigngroups.sqf at mission start

19/09/15
- Added werthless headless client script, set 120 seconds in init to let DAC initialise
- Skillet added LOPFOR new units

21/09/15
- Skilletkid added ST Gestures colouring defined in assigngroups.sqf
- Also fixed up error in DAC_units_config 

08/03/16
- Removed playerkit.sqf and transfered radio function to initplayerlocal.sqf
- Deleted truckgear.sqf
- edited TFD.hpp class configs to remove redundant functions
- moved briefing.sqf, werthless.sqf and intro.sqf into scripts folder and adjusted initplayerlocal.sqf accordingly
- removed author, onloadname, onloadmission, loadscreen, overviewtext from description.ext
- retaining debugconsole, disableAI and joinunassigned as these will override any changes made by mission makers in eden
- Updated mission makers guide to reflect new eden changes.  Will update this further at a later date.

06/04/16
- Removed css spectator script and replaced with vanilla - this will now require a simple respawn marker created

12/05/16
 - Updated fn_setradio.sqf function to include a full generic 26 man platoon layout supporting the new TFD mission making compositions

18/06/16
- Changed how insginia are now handled by creating some example config classes in the description.ext.  This allows far easier implementation of custom patches if desired by mission maker
- setpatch.sqf removed
- Removed redundant stgestures code
- updated EGspectator function call in the playerkilled.sqf

29/08/16
-added grenade stop script.
-removed setobjectVD to allow players self settings
-added example end classes in the description.ext

16/03/2017
- updated to admin panel mk2 
- updated orbat journal entry code from newer framework by JS&JT
- minor comment changes in some sqf files
- updated dynamic markers function
- minor updates to Framework Check list

29/03/17
-fixed admin panel issue in playersetup.sqf

14/12/17
- changed text in intro.sqf to placeholder text
- updated briefing.sqf with examples of markers and page breaks
- disabled ACE cook off in init.sqf
- added first implementation of civilian kill counter

21/12/17
- added civilian kill counter
- added Stalk script
- added Fire Support script 
- added increased fuel consumption script
- removed tonny's duplicate guid for the admin panel
- updated framework to support TFAR beta via cba_settings.sqf
- updated compositions and set radio fnc to have s_x where x = unit number.  makes for easier copy/paste of units

06/02/18
- EPD (Ied Scripted Used by Atreus in older missions creates awesome particle affects and realist IED's Ask him for assistance for usage **Can Be performance hindering if not careful**)
- Johnnyshootos Boobytrap script ( Enables mission maker to spawn x size explosion onto player if they pick up x weapon **Use to prevent players from looting enemy weapons again be smart about it.)
- Added DAC Documentation in PDF's 

22/04/19
- Added new DAC Behaviour and Units
- Updated CBA Settings
- Add jet service script documentation inside
