# Index-ASL-Gestures
Additional ASL gestures for Valve Index controllers in VRChat, makes use of VRCThumbParams mod by BenacleJames.

# Mod Setup
 - You'll need to install the [VRCThumbParams](https://github.com/benaclejames/VRCThumbParams) mod created by [BenacleJames](https://github.com/benaclejames). Simply drop his .dll file into your MelonLoader Mods folder.

   - You'll need install MelonLoader in order to be able to run mods. MelonLoader and it's installation instructions can be found [here](https://github.com/HerpDerpinstine/MelonLoader).

# Avatar Setup
 - First, import the provided .unitypackage file. All needed items will be found in your assets inside a new folder named ASL Gestures.
 
 - Set your Gesture Layer inside your VRC Avatar Descriptor component to the provided ASL Gestures.controller file.
 
  ![](https://i.imgur.com/T735Zxj.png)

 - If your avatar already has an Expression Menu and Parameters set up, simply add LeftThumb and RightThumb ***(CASE SENSITIVE)*** to your avatar's parameters.
 
   ![](https://i.imgur.com/ZBCk191.png)

 - If your avatar doesn't have an Expression Menu and Parameters set up, you can use the ones found within your ASL Gestures folder; ASL Params and Blank Menu. These options are found near the bottom of your Avatar Descriptor.
 
   ![](https://i.imgur.com/aOI2UuW.png)


# Control Scheme
 - The provided gesture setup is as follows:

   | Hand Position | Thumb Position | Resulting Shape
   | ------------- | -------------- | --------------- |
   | V Hand        | Thumbstick     | K Hand          |
   | V Hand        | A Button       | R Hand          |
   | V Hand        | B Button       | V Hand          |
   | V Hand        | Trackpad       | U Hand          |
   | Fist          | A Button*      | Flat O Hand     |

 - *Note that Flat O is triggered with the A button, but is set to not exit that state until your thumb is lifted from all buttons. This is to prevent accidentally brushing B from cancelling the handshape.

# Credits
 - A big thank you to [BenacleJames](https://github.com/benaclejames) both for creating the mod necessary for this whole idea to work, and for his assistance in working out some kinks in the animator controller~ <3

 - [HerpDerpinstine/MelonLoader](https://github.com/HerpDerpinstine/MelonLoader) for helping make mods possible in VRChat.
