# Secret_Agent

This repository holds the files for task 1 of the COS 738 Assignment 1.
This was a group project conducted by **__Ryan Hansen__** and **__Chezlyn Petersen__**

## Project Descriptions 

As part of the Cybersecurity module, we were tasked with using Augmented Reality(AR) for the purpose of hiding some information in a Steganography problem. 

## Scenario 

The Scenario we set was that an Intelligence agency wanted to do a dead-drop using an Augmented Reality Mobile application. **Agents**(technically anybody), could download and install the apk for the application, through a number of means. The apk would be a mobile application, that stores important information, or orders the agent needs to receive. However, the information will only appear when the agent, who knows the markers, shows it to the device. 

## Solution 

We utilize **Unity** and  **Vuforia Engine** to develop our Augmented Reality application. Unity was used as a development environment and we utilized a number of their UI and game objects for our application design.  Vufoia engine is an Augmented Reality software development kit (SDK) that we imported into Unity.

We used a number of Unity UI elements for our design including panels, 3D Planes, text, and video elements,  to display relevant information at the appropriate times. 

Using Vuforia, we were able to do AR image recognition. Once Vuforia is imported into Unity, we were able to use the Vuforia ImageTarget game object. The ImageTarget is a Vuforia object that allows us to identify images through the mobile device camera. In the Unity inspector, we were able to set an image for our image target to identify, as what actions to perform when the image is found or lost. 

For our application, we set two separate image targets. The one image is a false target, which when found, plays the incorrect video. While the other image is the true target, which when found, plays the **"Mission Intro"** followed by the **Hidden Message**,  we also include a bonus feature. 

## Instructions
 To run the application, download and install it on an appropriate Android device, API LEVEL 26 or above. 
 Once installed and opened, **Accept** your mission on the Welcome page. 

To view the embed information in the **False Target **, point your device at this image

![False Target ](https://github.com/ryan11719/Secret_Agent/assets/83818995/223f7caf-0fb9-4c24-9e4e-877e846d2b95)

To view the **True Message**, point your device at this image 

![image](https://github.com/ryan11719/Secret_Agent/assets/83818995/7cfc919a-23c5-4351-892a-36f81680fec3)

The images can be displayed  digitally or physically, as long as there is appropriate lighting(not too much, not too little ). Once the targets find either of the images, the appropriate action will occur. 

## Demo Video 
The Demo video is too large to be directly embedded into this README FILE but can be downloaded from the repository 

## Link 
The repository 
https://github.com/ryan11719/Secret_Agent.git

Google Drive Containing the apk 

https://drive.google.com/drive/folders/1t3H6RwprF9g-r4VM1ptHtZefaFFQ0lbc?usp=drive_link






