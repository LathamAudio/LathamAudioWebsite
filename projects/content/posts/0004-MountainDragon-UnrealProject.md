---
title: "Unreal+Metasounds+Wwise - Mountain Dragon"
description: "An Unreal Project to implement audio for the Mountain Dragon creature"
date: 2025-02-01
draft: true
tags: ["Unreal Engine", "Audio", "Sound Design", "GitHub", "Game Audio", "Wwise", "Metasounds"]
cover:
    image: "/projects/images/0004-MoutainDragon/DragonCover2.png"
summary: "An Unreal Project to implement audio for the Mountain Dragon creature"
---
Have you watched & listened to 'How To Train Your Dragon' or 'Game of Thrones' and thought "I could do that!" Have you ever wanted to work on improving your creature design chops? Have you wanted to work on implementing your audio in the Unreal Engine with both Metasounds and Wwise to compare them? Are you me, because that is a very specific set of goals? Anyways, here is your chance!

This is the Mountain Dragon from the Quadraped Fantasy Creatures for the Unreal Engine found on Fab.com. It comes as a set of creatures that have all the textures, animations, and skeletal mesh needed to get started but no audio! That's where we come in. I have set up the Mountain Dragon with basic movement, flying, and attack controls and setup the audio hooks to implement your own sound design. Follow the steps below to get started. 

# Setup
![Third Person Project](/images/0004-MountainDragon/ThirdPersonProject.png)

## Install Unreal & Create Third Person Project
1. Download Unreal Engine 5.0 - 5.4 (dragon works in UE5.5 or less, but fireball particle only works in UE5.4 or less)
2. Open Unreal Engine
3. Create Third Person Project
4. Close Unreal Engine
\
\
\
![Mountain Dragon](/images/0004-MountainDragon/QuadrapedFantasyCreature.png)
## Install Pre-Requisites
1. From Fab.com download "**Quadraped Fantasy Creatures**" (This is the dragon)
	- https://www.fab.com/listings/52d686b6-1180-4f26-901f-ce3c69a14767

2. From Fab.com download "**Paragon: Minions**" (This is the fireball)
	- https://www.fab.com/listings/039ea035-9360-4e76-ad06-5d3a92da6f65

3. From Fab.com, download "**Realistic Starter VFX Pack Vol 2**" (This is fire & explosions)
	- https://www.fab.com/listings/ac2818b3-7d35-4cf5-a1af-cbf8ff5c61c1

4. In the Epic Launcher add the Quadraped Fantasy Creatures to your project
5. In the Epic Launcher add the Paragon: Minions to your project
6. In the Epic Launcher add the Realistic Starter VFX Pack Vol 2 to your project
  
## Metasounds or Wwise - Which do I choose?
At this point it is time to download the audio setup for the Mountain Dragon and you have a choice of two implementations, Metasounds or Wwise.

**Metasounds** - If you want the most direct path for getting started on your sound design for the dragon then choose the Metasounds option. Metasounds are part of the native Unreal Engine audio system and does not require running any external authoring tools to implement your audio. Go to the [Download Metasounds Audio Setup](#download-metasounds-audio-setup) section below for the next steps in the setup process.

**Wwise** - If you are interested in learning more about the using Wwise audio system with the Unreal Engine then choose this option. As an added bonus this version still has all the same audio setup in Metasounds so this is a great opportunity to compare the two systems and see if one works better for you or just to improve your chops on both systems. Go to the [Download Wwise Audio Setup](#download-wwise-audio-setup) section below for the next steps in the setup process. 

![Mountain Dragon Github](/images/0004-MountainDragon/MountainDragon_Github.png)
## Download Metasounds Audio Setup
1. Download "UE_MountainDragon_Audio-main.zip" from the LathamAudio Github using the green "<>Code" button
	- https://github.com/LathamAudio/UE_MountainDragon_Audio

2. Unzip the "MountainDragon" & "QuadrapedCreatures" folders to your Content folder in your Unreal project
4. Skip over the Wwise section below and go to [Setup the Mountain Dragon Pawn](#setup-moutain-dragon-pawn) section to proceed.

![Mountain Dragon Wwise](/images/0004-MountainDragon/Wwise_MountainDragon.png)
## Download Wwise Audio Setup
1. Download "UE_MountainDragon_Wwise-main.zip" from the LathamAudio Github using the green "<>Code" button
	- https://github.com/LathamAudio/UE_MountainDragon_Wwise

2. Unzip the "UE_MTNDragon_Wwise_WwiseProject" folder to your Unreal project folder. This contains the Wwise project. Do not unzip the "Content" folder yet.
3. Open the Wwise Launcher
4. In the Unreal Engine tab find your project and choose "Integrate Wwise in Project..."
5. Choose the version of Wwise you would like to use
6. Set the "UE_MTNDragon_Wwise_WwiseProject" path in the Wwise Project field
7. No Wwise plugins are needed for this setup
8. Back in the "UE_MountainDragon_Wwise-main.zip" unzip "Content" folder into your Unreal project
9. Proceed to [Setup the Mountain Dragon Pawn](#setup-moutain-dragon-pawn)


![Mountain Dragon Github](/images/0004-MountainDragon/DefaultPawn.png)
## Setup Moutain Dragon Pawn
1. Open your Unreal project
2. Open "BP_ThirdPersonGameMode" and change the Default Pawn to be "MountainDragon_BP"

## Controls
W - Move Foward\
S - Move Back\
A - Move Left\
D - Move Right\
E - Fly/Land\
Shift - Glide\
Left Click - Bite/Claw on Ground, Fireball in Air\
Righ Click - Breathe Fire

<!-- ![Mountain Dragon in Maps](/images/0004-MountainDragon/MountainDragon.gif) -->
## Adding the Mountain Dragon to other maps
Now that we have a dragon that can walk, fly, attack, breathe fire, launch fireballs we don't just want to use the test environment. The "Stylized Fantasy Provencal" environment is an appropriate setting for testing out your dragon sound design.
1. From Fab.com download "**Stylized Fantasy Provencal**", and add it to your project
	- https://www.fab.com/listings/ced19ea1-31ed-437f-ae64-2b6b1561fede
2. Open the "Main" level located in "StylizedProvencal/Maps"
3. With the Default Pawn set in the Game Mode set you should be able to download envoronments from Fab.com and use the Mountain Dragon in all of them!



## If you have any questions contact me at: [chris@lathamaudio.com](mailto:chris@lathamaudio.com)