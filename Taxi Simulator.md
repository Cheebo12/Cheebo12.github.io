---
layout: post
title: Taxi Simulator
---

City Car Driving: Taxi Games is a realistic simulation game that allows players to experience the thrill of being a taxi driver in a city. With a range of different taxi models to choose from, each with their own unique characteristics and handling, players must navigate through city streets, picking up and dropping off passengers at various locations while avoiding collisions. As they progress through the game, players can earn money and use it to upgrade their taxi's appearance. With its immersive gameplay and attention to detail, this game offers an exciting and authentic taxi-driving experience for players of all ages.


## Game Assets

All game assets used in this game, including 3D models, textures, animations, and sound effects, are company-owned and team of designers, modelers, and sound artists to ensure a high-quality and immersive gaming experience.


## Features

Here are some features that were used in the game

| Features        | Description                                              |
|<br/><br/>|---------------------------------------------------------------------------------|
| Ragdolls | Ragdolls were used on the pedestrian so they give off realistic movement when hit by a car |
| Object Pooling | Performing ragdolls on every pedestrian would be expensive. So since there are only 3 pedestrians spread out in the city I used only 3 ragdolls and activating them when the pedestrian was hit and resetted the position and rotation of limbs of the character for later use. |
| DoTween | The UI animations were made using a library called dotween. |
| Scriptable objects | Since this game has 30 levels I created a data container and stored pick/drop position and rotation of each level and dropped them inside the container to reduce scene size which ultimately reduced the game size by 11mbs. |
| PlayerPrefs | prefs were used to store coins earned the items bought in inventory and the color paint purchased |
| Ads Integration | Integrated Admob, unityAds with mediation |





## Gameplay

Check out the gameplay video on YouTube:

<iframe width="560" height="315" src="https://www.youtube.com/embed/oVqIyTHJg_4" frameborder="0" allowfullscreen></iframe>