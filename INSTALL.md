# TweakScale Companion :: SMCE

Adds (up to date) TweakScale /L patches for SMCE Add'ons.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
	+ Delete `<KSP_ROOT>/GameData/TweakScaleCompanion/SMCE`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/TweakScaleCompanion/SMCE/*` --> `<KSP_ROOT>/GameData/TweakScaleCompanion/SMCE`
		- Overwrite any preexisting file.

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[TweakScale]
			[Plugins]
				KSPe.Light.TweakScale.dll
				Scale.dll
			[patches]
				...
			CHANGE_LOG.md
			DefaultScales.cfg
			Examples.cfg
			LICENSE
			NOTICE
			README.md
			ScaleExponents.cfg
			TweakScale.version
			documentation.txt
		999_Scale_Redist.dll
		ModuleManager.dll
		...
		[TweakScaleCompanion]
			[...]
			[SMCE]
				CHANGE_LOG.md
				LICENSE*
				NOTICE
				README.md
				[...]
			[...]
	KSP.log
	PastDatabase.cfg
	...
```


### Dependencies

* Large Boat Parts V3.9.2 
	+ Optional, **NOT** included 
* TweakScale /L 2.3 or later
	+ **NOT** included
* Module Manager 3.0.7 or later
	+ **NOT** included
