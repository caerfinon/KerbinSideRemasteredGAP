# KerbinSideRemasteredGAP  
# Current Version: v2.1.0
# Contributors: Caerfinon, ColdJ
Contract Pack for Air flights to bases in Kerbin Side Remastered mod

Discord: https://discord.gg/HZJ9znHqYH

Notes:
- Contains flight contracts from KSC to Bases in the Kerbin Side Remastered mod.
     - modeled after flight missions provided in Contract Pack: Giving Aircraft a Purpose (GAP) V1.6.1 but not dependent on this mod
- Contains flightplans for Kramax Autopilot Continued mod
     - Flightplans provide landing information for the various runways at the individual bases
     - Runways where the AoA of the landing sequence proved to be too steep due to terrain were omitted from the flight plans.
     - Complete site to site flightpalns as provided by the original Kerbin Side GAP mod are not included.
- Contains runway definitions for NavUtilities continued mod
- Contains runway definitions for use with MechJeb2 - Author: ColdJ   
- Contains Kerbal contrstuct statics 
	- modifications for Baikerbanur taxiways from runway to terminal
	- original runway for KSC Extended mod at the TSC launch site that is no longer included in the mod

Install:
- place directory KerbinSideRemasteredGAP and all sub directories and files in your Gamedata/ContractPacks directroy (Create if it does not already exist) 

#-----------------------------------------------------------------------------------------------------------------
*** Notes on Version 2.0.0 ***
- Version 2 is a major rewrite of the Airline-Flight missions and Flight Progress is now tracked using the Persistent Data Store method rather than the contract complete method so current progress form the version 1 code will be lost.
	- You must complete the "Let's Start and Airline" mission to begin the Flight Progress
	- If you want to restore your previous base progress you can edit the persistent.sfs file for your game and serch for "PersistentDataStore" you will see something like this; 
	
	SCENARIO
	{
		name = PersistentDataStore
		scene = 7, 8, 5
		DATA
		{
			ksrgapFlightProgress = Int32:-2
		}
	}
	
	- Change the the number after "Int32:" to a value between 0 and 22 to open bases, The numbers represent progress to the following bases; 
			0 = Island Airfield
			1 = Kola Island Naval Air Station
			2 = Jeb's Junkyard and Spaceship Parts
			3 = Cape Kerman Space Center
			4 = Sandy Island Naval Air Station
			5 = Kerman Atoll Launch Facility
			6 = Meeda Naval Air Station
			7 = Kojave Sands Launch Facility
			9 = Desert Airfield
			10 = Polar Research Alpha
			11 = Baikerbanur Inland Kerbal Space Center
			12 = South Field Airfield
			13 = Harvester Airfield
			14 = Uberdam Airfield
			15 = Kamberwick Green Airfield
			16 = Kermundsen Research Station
			17 = South Lake Airfield
			18 = Hazard Shallows Naval Air Station
			19 = Dununda Airport
			20 = Round Range Airfield
			21 = Nye Island Field
			22 = Top Secret Area 15
			
	- Save the persistent.sfs file and next time you start your game you will have flights available to the number you set and all lower numberd bases.  

#-----------------------------------------------------------------------------------------------------------------

Thanks and Acknowledgements:
- Lots of inspiration and ideas from the following creators
	- inigma - Contract Pack: Giving Aircraft a Purpose (GAP)- https://forum.kerbalspaceprogram.com/index.php?/topic/129208-contract-pack-giving-aircraft-a-purpose-gap-161-milestones-air-flights-coast-guard/
	- Keniamin - Kerbin Side GAP - https://forum.kerbalspaceprogram.com/index.php?/topic/133545-13x-kerbin-side-gap/
	- TranceaddicT - For the fork of Contract Pack: Giving Aircraft a Purpose (GAP) - https://github.com/7ranceaddic7/GAP
	- Nations States - Kerbin - https://www.nationstates.net/region=kerbin For providing the Geographical backdrop for the flight contracts. 

- Required Mods
	- Eskandare - Kerbin Side Remastered - https://forum.kerbalspaceprogram.com/index.php?/topic/174336-kerbin-side-remastered-101-173/
	- AlphaAsh,ozraven,Ger_space - Kerbal Konstructs - https://forum.kerbalspaceprogram.com/index.php?/topic/151818-181-kerbal-konstructs-18115-15dec2019/
	- nightingale - Contract Configurator - https://forum.kerbalspaceprogram.com/index.php?/topic/91625-1101-contract-configurator-v1305-2020-10-05/

- Optional Mods	
	- linuxgurugamer - Kramax Autopilot Continued - https://forum.kerbalspaceprogram.com/index.php?/topic/150846-19x-kramax-autopilot-continued-course-guidance-and-auto-land-for-spaceplanes/
	- Ser - NavUtilities continued - https://forum.kerbalspaceprogram.com/index.php?/topic/162967-140-181-navutilities-continued-ft-hsi-instrument-landing-system-v072-2018-apr-1/
	
- Test Planes from KerbalX.com 
	- Kerbin Side Remastered GAP KerbalX Hanger - https://kerbalx.com/hangars/130138
	- Aircraft and rovers I find useful to use with this mod 
	
	

	
	
	