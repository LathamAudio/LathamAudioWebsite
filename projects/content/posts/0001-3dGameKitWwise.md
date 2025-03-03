---
title: "Unity+Wwise - 3dGameKitWwise"
description: "A Wwise implementation of the 3dGame Kit in the Unity Engine"
date: 2024-11-01
draft: false
tags: ["3d Game Kit", "Unity", "Wwise", "Sound Design", "Sound Effects", "Music"]
cover:
    image: "/projects/images/0001-3dGameKitWwise/3dGameKitWwise.jpg"
summary: "Unity's 3d Game Kit + Audiokinetic's Wwise"
---
## DOWNLOAD HERE 
https://drive.google.com/file/d/12sdJIlbeuURle7mnvwCzz62_KizaedJl/view?usp=sharing



## Intallation

1. Download & install the Unity Hub at http://unity.com/

2. Install Unity 2022.3.59f1


Create 3dGameKitWwise Project
3. Create a new Unity project using the 3d template, call it something like “3dGameKitWwise” and save it in your favorite file location

4. Once the project is open navigate to the Asset Store found at http://assetstore.unity.com

5. Search for "3d Game Kit" in the Unity Asset Store. Download and import it into your project, approving any popups (this can take a while).


Open first 3d Game Kit scene 
6. Once complete you can find and open the Start scene by going to "Assets\3dGameKit\Scenes\" in the Project window

7. Try playing 3dGameKit to see if will run by pressing Play button, once successful you can close Unity

8. Download [3dGameKitWwise_WwiseProject.zip](https://drive.google.com/file/d/12sdJIlbeuURle7mnvwCzz62_KizaedJl/view?usp=sharing) here and unzip the contents into the 3dGameKitWwise Unity project folder.


Install Wwise
10. Download & install the Wwise Launcher at http://www.audiokinetic.com/

11. Install Wwise 2019.1.8 You only need to select the Authoring tool & SDK at this time, no plugins are needed for this project

12. In the Wwise Launcher go to the Unity tab and choose "Integrate Wwise Into Project..." for the 3dGameKitWwise Unity project


Integrate Wwise Into 3dGameKitWwise Project
13. You may need to update Wwise to integrate it into the project, press "Modify Wwise..."

14. This will take you back to Wwise install screen with all of the necessary packages and platforms already selected, press "Modify" and again you don't need to install plugins

15. Once that has completed successfully, press "Add WWise to 3dGameKitWwise"

16. Next set the Wwise Project Path by navigating to your Unity project and into the 3dGameKitWwise_WwiseProject folder to select the "3dGameKitWwise_WwiseProject.wproj" file

17. Press the "Integrate" button to integrate Wwise into the Unity project


Generate Wwise Soundbank
18. Once complete open the "3dGameKitWwise_WwiseProject.wproj" session in Wwise. It may ask to update the project, press "Yes"

19. Go to the Soundbank layout and generate the soundbank choosing PC or MAC depending on the platform



Play and Test 3dGameKitWwise

12. Open Unity and the 3dGameKitWwise project

12. From Assets->Import Package->Custom Package... choose '3dGameKitWwise.unitypackage', and import all assets

23. Open Unity and then open the Start scene. Hit play in Unity to test project and hear audio from Wwise.

24. You can remotely connect Wwise in realtime to profile the audio playing in the game











0. Download the 3dGameKitWwise.zip. This contains the Wwise session and Unity package

1. Download Unity Hub

2. Install Unity 2022

3. Create new Unity project called 3dGameKitWwise

4. Download and install 3dGameKit from Unity Asset Store

5. Close Unity

6. Unzip the provided Wwise session into the new 3dGameKitWwise folder

7. Download the Wwise Launcher

8. Install Wwise 2023 

9. Copy 3dGameKitWwise Wwise session into the Unity project folder

10. Integrate Wwise into 3dGameKit Unity project, make sure to reference the 3dGameKitWwise Wwise session

11. Open the 3dGameKitWwise Unity project


13. Run the game to test and profile in Wwise
 