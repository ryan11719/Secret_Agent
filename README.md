# Secret_Agent

This repository holds the files for task 2 of the COS 738 Assignment 1.
This was a group project conducted by **__Ryan Hansen__** and **__Chezlyn Petersen__**

## Project Descriptions 

As part of the Cybersecurity module, we were tasked with using Augmented Reality(AR) for the purpose of hiding some information in a Steganography problem. 

## Scenario 

The Scenario we set was that an Intelligence agency wants to Dead-drops using an Augmented Reality Mobile application. **Agents**(technically anybody), could download and install the apk for the application, through a number of means. The apk would be a mobile application, that stores important information, or orders the agent needs to receive. However, the information will only appear when the agent finds the secret AR marker. 

##Solution 

We utilize **Unity** and  **Vuforia Engine** to develop our Augmented Reality application. Unity was used as a development environment and we utilized a number of their UI and game objects for our application design.  Vufoia engine is an Augmented Reality software development kit (SDK) that we imported into Unity.

We used a number of Unity UI elements for our design including panels, 3D Planes, text, and video elements,  to display relevant information at the appropriate times. 

Using Vuforia, we were able to do AR image recognition. Once Vuforia is imported into Unity, we were able to use the Vuforia ImageTarget game object. The ImageTarget is a Vuforia object that allows us to identify images through the mobile device camera. In the Unity inspector, we were able to set an image for our image target to identify, as what actions to perform when the image is found or lost. 

For our application, we set two separate image targets. The one image is a false target, that when found plays the incorrect video, while the other image is the true target, that when found plays the **"Mission Intor"** followed by the **Hidden Message**,  we also include a bonus feature. 

## Instructions
 To run the application, download and install it on an appropriate android device, API LEVEL 26 or above. 
 Once installed and opened, **Accept** your mission on the opening page. 




