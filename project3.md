---
layout: default
title: "Project 3"
---
[Click here to go Home](./index.html).

# Project 3


## Introduction

For this project, we had to work with virtual reality to change the look of the interior of the unbuilt CDRLC building. A template of this building was given by our instructor in project 2, where we had to make a small kisok in the building. Project 3 further expands on this, by allowing students to decorate the walls and add new features like switches, animations, and interactions. Although a theme was recommended, I went with having no real theme, adding random 3D objects, some with animations, to see how they would fit in this space.


![mainpic](/assets/images/proj3pics/proj3main.PNG)

**This is the link to the 5 minute youtube video! [Youtube Link](https://youtu.be/jku58D_dsgQ)**

Note, The recording framerate was poor, but the actual app running itself ran in high fps.


## How to set up
1. Create an account and install [Unity](https://unity.com/) 2021.3.6f1. We will also be using VRTK version 4.

2. Install [Git](https://git-scm.com/) and clone the project from the GitHub repository in Git. A second alternative that does not require the user to use Git, is to install the project zip folder, containing the entire project through the github link. [GitHub link](https://github.com/Jamame/cs428Project3/tree/master)

3. Open the Unity hub and add the project folder that was cloned or downloaded.

4. Open the project in Unity.

5. Delete the default scene, and under the Assets folder, CoffeeShopStarterPack folder, and Scenes folder, add the CoffeeScene to the hierarchy.

6. By default, the project will be built to use the simulator on PC. If you want to switch to a VR headset, click on the appropiate VR settings in the Build settings. For VR, you will also need to disable the CameraRigs.SpatialSimulator, and enable the CameraRigs.UnityXRPluginFramework.

8. Click the play button at the top of the screen to simulate the virtual world on PC. Press 2 and 3 to toggle the controllers, and use 'wasd' to move. If running in VR, hook the vr headset to the PC, and upload the built project folder into the headset. Developer settings may need to be enabled in order to be able to see and run the program in the VR headset.



## Sources for assets

**Models and assets online**

**Grabbable objects**

1. This is a vending machine for wine from VIS Games. ![winevending](/assets/images/proj3pics/vendingmachine1.png) 
**Makes a sound when interacted with. Also spawns an object.** [Link](https://assetstore.unity.com/packages/3d/props/interior/snack-machines-3517)

2. This is a vending machine for chips from VIS Games. ![chipsvending](/assets/images/proj3pics/vendingmachine2.png)
**Makes a sound when interacted with. Also spawns an object.** [Link](https://assetstore.unity.com/packages/3d/props/interior/snack-machines-3517)

3. This is chips from Lumo-Art 3D. ![chips](/assets/images/proj3pics/chips.png) 
**Makes a sound when interacted with.** [Link](https://assetstore.unity.com/packages/3d/props/food/free-casual-food-pack-mobile-vr-85884)

4. This is wine from Lumo-Art 3D. ![wine](/assets/images/proj3pics/wine.png) 
**Makes a sound when interacted with. Also has a particle system.** [Link](https://assetstore.unity.com/packages/3d/props/food/free-casual-food-pack-mobile-vr-85884)

5. This a piece of cheese from Lumo-Art 3D. ![cheese](/assets/images/proj3pics/cheese.png) [Link](https://assetstore.unity.com/packages/3d/props/food/free-casual-food-pack-mobile-vr-85884)

6. This human asset was created from MakeHuman and Mixamo for animation. ![human](/assets/images/proj3pics/studentHuman.png) **Makes a sound when interacted with.**

7. This is a mensa table from Albert Gregl. ![mensa1](/assets/images/proj3pics/mensa1.png) [Link](https://assetstore.unity.com/packages/3d/props/furniture/roman-furniture-roman-villa-pack-165586)

8. This is another mensa table from Albert Gregl. ![mensa2](/assets/images/proj3pics/mensa2.png) [Link](https://assetstore.unity.com/packages/3d/props/furniture/roman-furniture-roman-villa-pack-165586)




## Non Grabbable and Animated or Light Source or Flats

1. This is a wall light from FlatRiver. ![walllight](/assets/images/proj3pics/wallLight.png) 
**Has a light source.** [Link](https://assetstore.unity.com/packages/3d/props/simple-wall-lamp-69411)

2. This is a roman light from Albert Gregl. ![roman light](/assets/images/proj3pics/romanLight.png) 
**Has a light source.** [Link](https://assetstore.unity.com/packages/3d/props/furniture/roman-furniture-roman-villa-pack-165586)

5. This an animated spider from [prism bucket]. ![spider](/assets/images/proj3pics/spider.png) 
**Animated.** [Link](https://assetstore.unity.com/packages/3d/characters/animals/insects/animated-spider-22986)

6. This is an animated butterfly from INNOWELL GmbH. ![butterfly](/assets/images/proj3pics/butterfly.png) 
**Animated and moves around the scene.** [Link](https://assetstore.unity.com/packages/3d/characters/animals/insects/butterfly-animated-58355)

7. This is a rug from Azerilo. ![rug1](/assets/images/proj3pics/rug1.png) 
**Flat Model.** [Link](https://assetstore.unity.com/packages/3d/props/interior/free-rug-pack-118178)

8. This is another rug from Azerilo. ![rug2](/assets/images/proj3pics/rug2.png) 
**Flat Model.** [Link](https://assetstore.unity.com/packages/3d/props/interior/free-rug-pack-118178)

9. This is the third rug from Azerilo. ![rug3](/assets/images/proj3pics/rug3.png) 
**Flat Model.** [Link](https://assetstore.unity.com/packages/3d/props/interior/free-rug-pack-118178)

10. This is a painting from Webcadabra. ![paint1](/assets/images/proj3pics/painting1.png) 
**Flat Model.** [Link](https://assetstore.unity.com/packages/3d/props/interior/paintings-free-44185)

11. This is another painting from Webcadabra. ![paint2](/assets/images/proj3pics/painting2.png) 
**Flat Model.** [Link](https://assetstore.unity.com/packages/3d/props/interior/paintings-free-44185)

12. This is a switch that plays a voice recording by me when flipped. ![switch](/assets/images/proj3pics/switch.png) 
**Makes a sound when interacted with.**


**Sound effects**

The ambient audio is university sounds from this youtube link. [Link](https://www.youtube.com/watch?v=eXlPSFUqeSg&ab_channel=nathanolson)

The vending machine audio from this youtube link. [Link](https://www.youtube.com/watch?v=61LjQDg7Thg&ab_channel=GAMEX)

The eating chips sound effect is from this youtube link. [Link](https://www.youtube.com/watch?v=V6tCei4a_nU&ab_channel=SoundEffectsFactory)

The wine sound effect is from this youtube link. [Link](https://www.youtube.com/watch?v=KJ2CamzJhmw&ab_channel=SFX)

The audio for the human and switch was made by me using a voice recorder app.

**Models created**

I did not create any models for this project.

## Discussion

The first area or field that I thought about was that this technology is very useful for people working in the field of construction. This technology could be used to give a more realistic view of what a building model would look like before it is even constructed. It is also safer to use, as no actual construction would be necessary for a prototype or example of a build or model. For both people like a politician or my parents, this technology would allow them to explore the building and understand the scale or size of what they are currently experiencing. For a more concrete example, say I wanted to show my parents what decorations I wanted in my room or how I wanted the physical layout to be like, without the actual cost of buying these decorations or constructing anything. I could build a virtual room or model of my room, and show my parents how I would want my room to look like. For a politician, I could use this technology to show the scale of the project, and show different ways that rooms in a building could be used for productivity or various uses. They would also be able to see this building in relation to others, and see if the project is truly necessary or not without having to build a single thing. Whoever the user is, they could also just use a phone to view something like this, as it would be more common that someone would have a phone rather than a VR headset, which can cost hundreds of dollars. The accessibility of this technology is also improving, allowing for more users to use this kind of technology. This technology also has the potential to train construction workers on safety, replicating work hazards while building in a realistic environment. Training like this could improve safety and reduce the risk of injury for construction workers. This could also be used not just for safety, but to also replicate the current construction progress in real time. Having a real time view of the site can reduce the risk of miscalculations and mistakes for engineers. Other than construction, I can also see this technology being heavily used for real estate buying. A user could explore a home without the need to physically be present in that house. This allows the user to explore and see dozens or even hundreds of houses without ever stepping inside one, saving time and allowing for more accessibility. Homes that a user would normally not consider looking at, could change their mind after exploring the inside of it for a few seconds in VR technology. Due to the many potential benefits of this technology, I believe that technology like this will change the way that real estate and construction projects will be presented in the future. It is clear that this technology has the potential to shape and change the way that society functions, just like how mobile phones did in the past.