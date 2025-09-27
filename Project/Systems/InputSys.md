[Page]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Learn/LearnHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Changes/ChangesHome.mdnWorks.md

[Sec Welcome]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#welcome
[Sec Details]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#system-details
[Sec Features]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#features

[Feat Container]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#input-container-feature
[Feat Zones]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#input-output-zones-feature
[Feat Organic]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#organic-inputs-feature
[Feat Creature]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/InputSys.md#small-creature-inputs-feature

[Tag Sys useMat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Sys ProjInputs]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Tag Feat NewArea]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat ObjConstruct]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat Mat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Tag Feat ProjInput]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat Zone]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat ZoneArea]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

# Realms Wiki Collections: "Experimental Recycle Ecosystem" - Systems - Processing Input Zones

## Site Index

- [Home][Page Home]
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
			- Processing Input Zones System (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the Processing Input Zones System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: Processing Input Zones
	- SystemID: ExpGreenBioRec.InputZones
	- IDPiece: InputZones
	- Version: V 1.0.0
	- Implimented Version: V D 0.0.1.0
	- Last Changed: V D 0.0.1.0
	- Tags
		- [UseageMaterial][Tag Sys UseMat]< Metal.Container >
		- [ProjectInputs][Tag Sys ProjInputs]

This system is used to track input areas and also to keep track of valid inputs.

### Features

- Features
	- [Input Container][Feat Container]
	- [Input Output Zones][Feat Zones]
	- [Organic Inputs][Feat Organic]
	- [Small Creature Inputs][Feat Creature]

### Input Container Feature

This feature provides basic container for Input into the project.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: InputZones.[FeatureID]Feat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [NewArea][Tag Feat NewArea]< Biorecycle.Areas.Input >
		- [Construct][Tag Feat ObjConstruct]< Biorecycle.Areas.Input=>( 1, Metal.Container ) >
		- [Material][Tag Feat Mat]< Metal.Container, Item, 1 >


### Input Output Zones Feature

This feature marks both Input And Output containers as both Input/Output as the transportation setup can't handle large objects moving through.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: InputZones.[FeatureID]Feat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [NewZone][Tag Feat Zone]< Biorecycle.Zones.InputOutput >
		- [ZoneArea][Tag Feat ZoneArea]< Biorecycle.Zones.InputOutput, Biorecycle.Areas.Input >
		- [ZoneArea][Tag Feat ZoneArea]< Biorecycle.Zones.InputOutput, Biorecycle.Areas.Output >

### Organic Inputs Feature

This feature marks the allowed inputs to the given project that fall under organic but not covered by other features.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: InputZones.[FeatureID]Feat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [ProjectInput][Tag Feat ProjInput]< Food.Organic >
		- [ProjectInput][Tag Feat ProjInput]< Meat >

### Small Creature Inputs Feature

This feature marks allowed small creatures which can be valid inputs into the project.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: InputZones.[FeatureID]Feat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [ProjectInput][Tag Feat ProjInput]< Animal.Small.Dead >
		- [ProjectInput][Tag Feat ProjInput]< Bugs.Dead >
