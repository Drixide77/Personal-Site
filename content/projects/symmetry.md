+++
title = "Symmetry (PS4 port)"
description = "Porting Symmetry to the PS4."
date = 2017-08-24

[extra]
date_start = 2017-02-04
image = "symmetry.jpg"
top_project = true

[taxonomies]
projects=["Gaming"]
skills=["Game Maker Studio", "Scripting", "Videogames", "Porting", "PC", "Console", "Playstation"]
+++

This project was developed as part of my work at [**BlitWorks**](https://blitworks.com/home/).

Symmetry is a narrative-driven survival game, where you manage the resources of a group of scientists stranded on a frigid alien planet. The game, by *Sleepless Clinic* was originally developed in **Game Maker Studio**. The publisher wanted the game to have a Playstation 4 port, and so contracted our porting service.

The game's Steam page: [https://store.steampowered.com/app/537520/SYMMETRY/](https://store.steampowered.com/app/537520/SYMMETRY/)

The game's Playstation store page: [https://store.playstation.com/es-es/product/EP1546-CUSA09636_00-SYM0000000000001/](https://store.playstation.com/es-es/product/EP1546-CUSA09636_00-SYM0000000000001/)

## Responsibilities

In this project, I was the **lead** (and almost) solo developer.

I went through the usual pipeline of first assessing the state of the game as-is, observing existing issues and the *performance*. Then trying to run an initial build for the target platform, in this case, the **Playstation 4**. After finding a plethora of issues, I started *rewriting a good chunk of the game's code base*, to both fix performance and comply with Playstation's TOS and guidelines for published titles.

We added on-screen icons for the *Dual Shock*'s buttons, adapted all input to be *controller friendly*, adjusted several *UI and gameplay elements*, and added *achievements* and other *platform-related features*.

After the work was done, we retroactively also applied many of the fixes and changes to the original **Steam** release, to *consolidate the code bases* and also take advantage of the work done.
