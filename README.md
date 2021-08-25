# BSc_MS

## Repo of a B.Sc. project & an interactive widget to get the pixel coordinates of a maze

---
This repository is part of the **DCLwidgets** series. 
These repositories are dedicated to foster the joint development of tools and resources by the [Defense Circuits Lab](https://www.defense-circuits-lab.com/). 
The intended use of each tool may vary greatly from very lab- and/or analysis-specific problems, to tools and resources that may be of use also for other researchers.
The common goal for each repository, however, is to provide the tool as an interactive, userfriendly, and intuitive GUI so that the user needs little to no coding expertise.

List of all repositories of the DCLwidgets series:
- [DCL_stats_and_plots](https://github.com/DSegebarth/DCL_stats_and_plots/): A widget to compute statistics and plot the data with several options to customize the plot
- [DCL_to_NWB](https://github.com/DSegebarth/DCL_to_NWB/): A widget to convert datasets acquired in the DCL into the NWB file format
- [BSc_MS](https://github.com/DSegebarth/BSc_MS/): A widget to annotate the corners of a maze within video files and save the corresponding x- and y-coordinates

---

## About this widget

The purpose of this widget was to get the pixel coordinates of the corners of a maze (OpenTrack) from movie files.
These coordinates were required for the subsequent analysis of the tracking data (generated using DeepLabCut).
Since the position of the maze within the movie files was not always identical, the tracked coordinates had to be transformed into a standardized space.

This widget is quite specific for the described use-case. However, if you are interested in implementing a smiliar tool, feel free to contact us or to leave some feedback!

---
