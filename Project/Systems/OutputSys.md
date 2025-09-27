[Page]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Page Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/README.md
[Page Proj Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md
[Page Sys Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/ProjectHome.md#system-layout
[Page Learn Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Learn/LearnHome.md
[Page Changes Home]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Changes/ChangesHome.md

[Sec Welcome]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#welcome
[Sec Details]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#system-details
[Sec Features]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#features

[Feat Container]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#output-container
[Feat BioTrash]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#bio-trash-feature
[Feat Corpse]:https://github.com/Ancient-Majik-Tech/Experiment.Green.Biorecycle.Wiki/blob/main/Project/Systems/OutputSys.md#small-animal-corpse-output

[Tag Sys UseMat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Sys ProjOutputs]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

[Tag Feat NewArea]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat ObjConstruct]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat Mat]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md
[Tag Feat ProjOutput]:https://github.com/Ancient-Majik-Tech/Learn.Tutorial.Collections/blob/main/Project/Extends/ProjectUpdateInWorks.md

# Realms Wiki Collections: "Experimental Recycle Ecosystem" - Systems - Non Organics and Trash Output

## Site Index

- [Home][Page Home]
	- [Project][Page Proj Home]
		- [Systems][Page Sys Home]
			- Non Organics and Trash Output System (You are here)
	- [Learning][Page Learn Home]
	- [Changes][Page Changes Home]

## Page Index

- Page
	- [Welcome][Sec Welcome]
	- [System Details][Sec Details]
	- [Features][Sec Features]

### Welcome

Welcome to the Non Organics and Trash Output System's documentation page. This page is dedicated to helping you understand the system and its features. However please note that for understanding how to use the project you should check out [Learning][Page Learn Home] for all the dedicated learning for the given project.

### System Details

- Details
	- Name: Non Organics and Trash Output
	- SystemID: ExpGreenBioRec.NonOrgTrash
	- IDPiece: NonOrgTrash
	- Version: V 1.0.0
	- Implimented Version: V D 0.0.1.0
	- Last Changed: V D 0.0.1.0
	- Tags
		- [UseageMaterial][Tag Sys UseMat]< Metal.Container >
		- [ProjectOutputs][Tag Sys ProjOutputs]

This system is dedicated to the outputs of this project to mark them as given outputs for the project.

### Features

- Features
	- [Output Container][Feat Container]
	- [Bio Trash][Feat BioTrash]
	- [Small Animal Corpse Output][Feat Corpse]



### Output Container Feature

This feature provides a container as an Input Output Container.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: NonOrgTrash.OutputContainerFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [NewArea][Tag Feat NewArea]< Biorecycle.Areas.Output >
		- [Construct][Tag Feat ObjConstruct]< Biorecycle.Areas.Output=>( 1, Metal.Container ) >
		- [Material][Tag Feat Mat]< Metal.Container, Item, 1 >

### Bio Trash Feature

This features is used to organic material that is no longer suitable for use in the project.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: NonOrgTrash.BioTrashFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [ProjectOutput][Tag Feat ProjOutput]< Organic.Food, Spoiled >
		- [ProjectOutput][Tag Feat ProjOutput]< Bugs.Dead.Ants >

### Small Animal Corpse Output Feature

This feature is used to refer to the left overs after the ants have broken down small dead animals.

- Details
	- Status: Active
	- Version: V 1.0
	- FeatureID: NonOrgTrash.SmallCorpseOutputFeat
	- Impliment System Version: V 1.0.0
	- Last Change V 1.0.0
	- Tags
		- [ProjectOutput][Tag Feat ProjOutput]< Bone >
		- [ProjectOutput][Tag Feat ProjOutput]< Hair >
		- [ProjectOutput][Tag Feat ProjOutput]< Nails.Organic >
		- [ProjectOutput][Tag Feat ProjOutput]< Bugs.Exoskeleton >