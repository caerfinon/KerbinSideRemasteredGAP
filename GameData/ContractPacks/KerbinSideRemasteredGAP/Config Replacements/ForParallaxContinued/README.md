# Baikerbanur Rebuild for KerbinsSideReastered and Parallax Continued 
If you use thee Parallax Continued mod then the KerbinSideRemasterd site Baikerbanur will have its runway partially obstructed by the KSC2 Anomaly buildings.
The contents of these folders will make corrections to the airport site and move the runway so as to be unobstructed.
The flight contracts provided by KerbinSideRemasterdGAP will now use the the new runway location and navigation aids such as NavInstruments
and KramaxAutoPilot will have the proper runway information.      

Install:
- All the files in the following directories have the sxtension ".txt" so as to not be active during game play
- Copy the Gamedata folder to your Desktop and rename each file to remove the .txt and leave only the .cfg extention   
- Then just replace the files that exist currently in your GameData folder with the ones shown below.
- When you have moved the files and tested the Baikerbaur airport in game, you can delete the folder from your desktop. 
- If you do not use the NavInsrtuments mod, you do not need to copy the files from that folder.
- If you encounter issues with the new files, reinstall the mods KerbinSideRemasterdGAP, KerbinSideRemastered NavInsrtuments and WaypointManager from their sources      

GameData 
	- ContractPacks
		- KerbinSideRemasterdGAP
			- Kerbal-Konstructs
				-Sites
					- Base-Instances
						- Baikerbanur
							-KSR_pstr-instances.cfg
							-KSR_ptee-instances.cfg
			- Patches
				- CustomWaypoints.KSRGAP.cfg
				- GlideSlopes.cfg
				- KerbinSideRemasteredFlightPlans.cfg
			- Groups.cfg
	
	- KerbinSideRemastered
		- Statics
			-ExampleBases
				-KSC2
					- EHIFuelTanks-instances.cfg
					- KK_2500m_runway-instances.cfg
					- KS_ALSF_2-instances.cfg
					- KS_filler_B2-instances.cfg
					- KS_ODALS-instances.cfg
					- KS_PAPI-instances.cfg
					- KS_smallhangarblockH-instances.cfg
					- KS_TaxiLarge-instances.cfg
					- KSC_Crawlerway_level_2-instances.cfg
					- KSC_FlagPole_level_2-instances.cfg
					- KSC_SpaceplaneHangar_level_2-instances.cfg
					- KSC_VAB_AC_level_2-instances.cfg
					- KSC_VAB_RnD1_level_2-instances.cfg
					- KSC_VehicleAssemblyBuilding_level_2-instances.cfg
	
	- NavInsrtuments 
		-ModuleManagerCfg
			-KerbinSideRemastered.cfg
	
	- WaypointManager
		- PluginData
			-CustomWaypoints
				- CustomWaypoints.KSRGAP.cfg