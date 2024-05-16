# Prime Engine

## Description ##

PrimeEngine is a C++-based 3D game engine, originally developed by Artem Kovalovs. I had the chance to get hands-on with this engine during my Master's program at USC.

Aside from the core code, PrimeEngine is also compatible with Python and Lua scripting which were mainly used to integrate PrimeEngine with Maya and PyClient which is an editor tool. These tools to export assets from Maya to Prime Engine were part of the original codebase.

Other than core functionalities added in the original Prime Engine created by Artem Kovalovs, I have added a lot of other core things into this Engine such as

## Camera Frustrum Culling ## 
Reducing the number of objects that are sent to the graphics pipeline to render based on camera view visibility. This is done to optimization of Camera Rendering
**Description Document:** https://drive.google.com/file/d/17Ky7mEKu5v7nJeHj21ze7EGbeWQWCYFg/view?usp=sharing

[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/e8faa725-dbd1-4b7c-835b-8ef11d3ac9c4)](https://drive.google.com/file/d/1tjKFo773h0mkhQ4RADXaYy9uKaL__uls/view?usp=sharing)

## Physics System ##
I created a basic Physics system from scratch with Sphere Colliders, Box Colliders and Rigid Body components to detect collisions and few basics rigid mechanics like gravity, acceleration, collision movements, e.t.c
**Description Document:** https://drive.google.com/file/d/16r0O0WJxP3gN81hI2EPXz9BKX4TEaikZ/view?usp=sharing

[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/4359e911-327e-4d36-929b-bd503dc3a04c)](https://drive.google.com/file/d/1BZKeJTEjALDCzz7a1WqDhT3_04CQtJ-I/view?usp=sharing)

## Data Driven Animation System ##
I created a complete data-driven animation system where various animations can created using various layers, states, parameters and transitions to perform full body, partial body and additive animations.
**Description Document:** https://drive.google.com/file/d/1KEAODJiWUN1UEP1EzGfZ2txxjx3nqM3J/view?usp=sharing

[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/db1663aa-c077-4960-9043-249756ec53b5)](https://drive.google.com/file/d/1ElECeTLfoME2KNBrt6c2R3CWZBm8smZb/view?usp=sharing)

[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/f89a158a-ad9b-4472-8ce9-b34b1d4e674c)](https://drive.google.com/file/d/1usnWtQGpYuAnt-MMwpMPAUa1Pa3YN2dh/view?usp=sharing)

## New Level Builder System ##
I completely revamped the existing level builder in Prime Engine and created a new one. In this new system various kinds of Game Objects can be directly created in Maya without changing any code by adding gameobject hierarchy and components directly in Maya.
**Description Document:** https://drive.google.com/file/d/1REqFq_U-Db38rZVAAdsn4st1GfLUmG0Y/view?usp=sharing 

[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/3aaae584-628b-42e8-9145-6c8ebbc1b5fb)](https://drive.google.com/file/d/1EVOGCsYEX8ysS7yb_Jx27GxoYlHeVpgy/view?usp=sharing)

## Final Basic Gameplay Demo ##
[![Play Video](https://github.com/manasmuda/PrimeEngineDoc/assets/31534685/a14ccef1-269b-4e05-8122-774721bdf2ed)](https://drive.google.com/file/d/18kPbUTeQDAeugq3nkCbxE7olmT2iuLOs/view?usp=sharing)






