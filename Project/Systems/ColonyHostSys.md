[Page]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Learn/LearnHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Changes/ChangesHome.md

[Sec Welcome]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#welcome
[Sec Details]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#system-details
[Sec Features]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#features

[Feat Seed]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#ant-host-seeding-feature
[Feat Living]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#ant-living-containers-feature
[Feat Feeding]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#ant-feeding-feature
[Feat Trash]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/ColonyHostSys.md#ant-trash-feature

[Tag Sys Processing]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Sys UseMat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Tag Feat Mat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat Output]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat Process]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat ObjConstruct]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat OneTimeInput]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

# Realms Wiki Collections: "Experimental Recycle Ecosystem" - Systems - Ant Colony Host

## Site Index

- [Home][Page Home]
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
			- [System Name] System (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the Ant Colony Host System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: Ant Colony Host
	- SystemID: ExpGreenBioRec.AntsHost
	- IDPiece: AntsHost
	- Version: V 1.0.0
	- Implimented Version: V D 0.0.3.0
	- Last Changed: V D 0.0.3.0
	- Tags
		- [Processing][Tag Sys Processing]
		- [UseageMaterial][Tag Sys UseMat]< Plastic.Container >

This system is used to provide the ants a given places to live to enhance probabilities of success.

### Features

- Features
	- [Ant Host Seeding][Feat Seed]
	- [Ant Living Containers][Feat Living]
	- [Ant Feeding][Feat Feeding]
	- [Ant Trash][Feat Trash]

### Ant Host Seeding Feature

This feature is used to get the ants used to the project and comfertable using it.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: AntsHost.SeedingFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [OneTimeInput][Tag Feat OneTimeInput]< Ant=>Insect >

### Ant Living Containers Feature

This feature is used to provide the ants with a place to live.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: AntsHost.LivingFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [Construct][Tag Feat ObjConstruct]< LivingArea=>( 2, Plastic.Container ) >
		- [Material][Tag Feat Mat]< Plastic.Container, Item, 2 >
		

### Ant Feeding Feature

This feature is used as a source of processing materials using the ants digestive capabilities.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: AntsHost.FeedingFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [Processes][Tag Feat Process]< Organic.Food >
		- [Processes][Tag Feat Process]< Meat >
		- [Processes][Tag Feat Process]< Sugar >
		- [Processes][Tag Feat Process]< Liquid >

### Ant Trash Feature

This feature is used as a source of some outputs that are not able to be processed by the ants.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: AntsHost.TrashFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [Outputs][Tag Feat Output]< Bugs.Dead.Ant >

