# Index-ASL-Gestures
Additional ASL gestures for Valve Index controllers in VRChat, makes use of VRCThumbParams mod by BenacleJames.

 - [Download Here!](https://github.com/shrine-priestess/Index-ASL-Gestures/releases/download/1.5/ASL_Gestures1.5.unitypackage)

# Mod Setup
~~- You will need the [VRCThumbParams](https://github.com/benaclejames/VRCThumbParams) mod created by [BenacleJames](https://github.com/benaclejames). Simply drop his .dll file into your MelonLoader Mods folder.~~

~~- You'll also need to install MelonLoader in order to be able to run mods, if you haven't already. MelonLoader and it's installation instructions can be found [here](https://github.com/HerpDerpinstine/MelonLoader).~~

This mod is no longer publicly available after the recent ban wave for mod creators. This page will be updated to reflect any changes to this situation. <3

# Avatar Setup
 - First, import the provided .unitypackage file. All needed items will be found in your assets inside a new folder named ASL Gestures.
 
 - Set your Gesture Layer inside your VRC Avatar Descriptor component to the provided ASL Gestures.controller file.
 
   ![](https://i.imgur.com/T735Zxj.png)

 - If your avatar already has an Expression Menu and Parameters set up, simply add LeftThumb and RightThumb ***(CASE SENSITIVE)*** to your avatar's parameters. Nothing needs to be added to your Menu component.
 
   ![](https://i.imgur.com/ZBCk191.png)

 - If your avatar doesn't have an Expression Menu and Parameters set up, you can use the ones found within your ASL Gestures folder: ASL Params and Blank Menu. These options are found near the bottom of your Avatar Descriptor.
 
   ![](https://i.imgur.com/aOI2UuW.png)


# Control Scheme
 - The provided gesture setup is as follows:

   | Hand Position | Thumb Position | Resulting Shape
   | ------------- | -------------- | --------------- |
   | V Hand        | Thumbstick     | K Hand          |
   | V Hand        | A Button       | R Hand          |
   | V Hand        | B Button       | V Hand          |
   | V Hand        | Trackpad       | U Hand          |
   | Fist          | B Button       | Flat O Hand     |
   | Fist          | Trackpad       | S Hand          |

 - **Also important to note: Enabling Gesture Lock will mess with your ability to use these additional handshapes!

# Credits
 - A big thank you to [BenacleJames](https://github.com/benaclejames) both for creating the mod necessary for this whole idea to work, and for his assistance in working out some kinks in the animator controller~ 💜
 
  - Special thanks to Aisoko and SnaekySnacks for being my test monkeys~ 🖤

 - [HerpDerpinstine/MelonLoader](https://github.com/HerpDerpinstine/MelonLoader) for helping make mods possible in VRChat.
