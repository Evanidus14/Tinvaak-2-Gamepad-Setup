# Tinvaak 2 Gamepad Setup & Guide

![Logo](https://user-images.githubusercontent.com/89932487/139698859-f32a30bb-0c34-41d3-ba30-9ea768d9af01.png)


## Foreword

Setting up Tinvaak 2 with a gamepad can be a daunting task with all of it's extra features and possible keybinds. In addition to that, the main combat mod, Engarde, works in such a way that dodges and power attacks won't respond to your analog stick movements - effectively locking you out of most of your defensive and offensive options right from the start. There are some workarounds such as mapping your controller to keyboard keys for movement, but this is less than ideal as it intereferes with movement and camera control, not to mention it's also a pain to set up. Hopefully, with the help of this guide, you won't have to worry about *that*, anymore.

If you follow the instructions within this guide, you'll be able to play Tinvaak 2 utilizing all of what it's systems have to offer, comfortably, with your gamepad while still enjoying all of what a controller brings to the table. Finally, you won't have to download any crazy software or tinker around with configurations - All we need is a Steam configuration and a custom_controlmap.txt which has already been done for you and will be linked for easy access further into the guide!

... You *will* have to spend time and read this guide in its entirety though, otherwise you will be lost when trying to use your controller in game. Please read the full guide before asking for support. This guide has been prepared to help YOU help yourself. With that being said, if you believe you've followed the guide to the letter and are still having issues, let someone on the team know in the support channel on the Wabbajack discord or in the Tinvaak 2 Bugs & Questions channel on Althro's discord and we will be happy to assist you.

## First Steps & Setup

### Important Considerations

The best time to follow this guide is after you've followed the main readme for the install of Tinvaak 2. You can follow this guide while making your character in game or after you've already made your character - either option will work just fine.

### Connecting Your Controller To Steam

This step can be somewhat difficult depending on your hardware and PC setup. Before we move on, Steam needs to be recognizing your controller (THAT MEANS THE CONTROLLER NEEDS TO BE ON) for you to be able to apply the Tinvaak 2 configurations. If you are having difficulty, make sure you go into Steam's settings, then controller settings, and then click on "GENERAL CONTROLLER SETTINGS" to ensure you have the right support boxes checked for the controller you're using. 

So, that will look like this...
![image](https://user-images.githubusercontent.com/89932487/133790433-f562b809-d170-487c-aa3a-2763e6bc7d79.png)

... and then this. Make sure you check the appropriate box or boxes for your specific controller situation!
![image](https://user-images.githubusercontent.com/89932487/133791623-28808010-9c55-426f-a998-a1d7f30edbb0.png)


Steam's controller support is very broad, so just about any controller will work. This guide, however, will be focusing on the PS4/PS5 controller and the Xbox family of controllers as those are the most widely known and used. If you still can't get your controller connected, you'll have to google solutions as the potential source of the problem could be a great many things and support/troubleshooting for it goes beyond the scope of this guide. Take solace in the fact that someone out there has most likely experienced your issue and has a solution for you, you just have to find it (yourself).

### Importing The Steam Controller Configurations

As was stated earlier, you don't need to mess around with any custom controls, software, or configurations yourself, that has ALL been done for you. This step is simply applying the configuration that has already been made to your specific controller. The configurations were made on a PS5 controller and an Xbox Elite controller, but they will still work with earlier generation models. That is to say, the PS5 controller configuration works with a PS4 controller and the Xbox Elite configuration works with any Xbox controller. If you're using some sort of wonky 3rd party controller, it *should* work with the Xbox configuration. So, depending on which controller you're using, Steam may give you a warning telling you the configuration you are trying to apply was made for a different controller, simply hit the "OK" option and the controls will map appropriately - SO LONG AS YOU APPLIED THE MATCHING CONFIGURATION THAT WAS JUST MENTIONED. 

Simply copy and paste the appropriate controller configuration from below into your browser and it will attempt to open Steam. Allow it to do so and then accept the configuration as was just mentioned. (Google and Firefox seem to be the best browsers for this step)

The Steam controller configurations are here: 
  - [PS4/5 controller] (steam://controllerconfig/489830/2643232367)
  ![image](https://user-images.githubusercontent.com/89932487/139701647-784c6b6d-62f8-428e-885d-48621bcb802f.png)

  - [Xbox and all 3rd party controllers] (steam://controllerconfig/489830/2643259291)
  ![image](https://user-images.githubusercontent.com/89932487/139708703-65997a20-a0f1-4206-ab2b-8ebd1bc35657.png)

Feel free to browse through the various keybindings to get a visual of the controls. However, DO NOT CHANGE ANYTHING! That will completely mess up your controls. If you do accidentally change something, simply re-import the configuration from this guide. 

## Important Mods to Understand

### Engarde

Engarde is the main combat mod being used by Tinvaak 2, alongside SkySA. Go to the [Changes to Gameplay.md](https://github.com/Althro/Tinvaak2/blob/main/Changes%20to%20Gameplay.md) for details on many of the gameplay changes made. What you need to understand about Engarde when it comes to playing with your controller, is how it was designed and why it is notoriously hard to play with a controller. It was designed around keyboard directional keys for determining movement, so since we use an analog stick, Engarde can't read what our character is doing and therefore we can't use the dodges or power attacks correctly (without a custom solution). We have gotten around that issue by mapping key combos that, when pressed, press a directional keyboard key (W, A, S, and/or D) and the dodge key at the same time. This allows us to get past the limitations of Engarde when it comes to a controller, however...

### True Directional Movement

True Directional Movement (TDM) is the movement overhaul everyone wants to be using - and for good reason: it allows you to play Skyrim with a truly modern movement style. It also features a lock on feature (much like Dark Souls) that you will need to make extensive use of for this entire setup to really shine. 

### Engarde+True Directional Movement Together

So, with both mods put together, we have some issues. Firstly, because TDM changes how movement occurs, it messes with our Engarde setup. Since Engarde relies on strafing type movement to determine dodge direction and since TDM essentially puts your character into an "always moving forward" state, we won't be able to use our directional features from Engarde... UNLESS you are locked on! Once you lock on to enemies, all of the features of both mods come together and you can experience the full effect of both mods. So, when not locked on, it won't matter which directional dodge you try to use, you'll simply do the forward dodge/slide. But that all changes when you lock on to your enemies. 

## Configuration In-Depth Explanation

These configurations were made possible by Steam's "shift modifier" and "action layer" options. What that means is this - While playing normally, you have the vanilla/default keybinds (for the most part). However, when you hold one of two modifiers, you get another set of new keybinds. I made both configurations virtually the same between PS4/5 and Xbox for ease of use. The two modifiers I make extensive use of are the LB & RB buttons on the Xbox controller and L1 & R1 for the PS4/5 controller. That means their vanilla/default functions have been remapped elswhere on the controller where it makes sense in order to free them up for modifier usage. Normally Engarde has directional power attacks that work very similar to the directional dodges, however, with SkySA we essentially only have standing power attacks - that means we don't need to worry about directional power attacks! That simplifies things for us.

#### Dodge Focus
Holding L1/LB will bring up your directional dodges from engarde and your first set of 4 groups from SkyUI. The 4 groups are located on the directional buttons (left, right, up, and down) and the 4 dodges are located on your face buttons (PS4/5: Square, Circle, Triangle, and Cross) (Xbox: X, Y, B, and A). They were added to the controller in a way that made sense to me - holding L1/LB and hitting Triangle/Y will give you a forward dodge. Holding L1/LB and hitting Square/X will give you your left dodge etc. 

#### Remaining SkyUI Groups
Holding R1/RB will bring up your last set of 4 groups from SKYUI. The groups are located on the directional buttons like before (left, right, down, and up). There is a slight difference between the controller archetypes here in that the Xbox controllers also have campfire functionality mapped to the face buttons while holding RB whereas the PS4/PS5 controllers have that same campfire functionality while holding the left side of the trackpad. If that confuses you, worry not! The controls are laid out in depth further into the guide.

#### Vanilla Hotkey Functionality
You have access to the 8 vanilla hotkeys with this setup. To map certain items/spells to each hotkey, simply press one of your keyboard keys (1-8) while highlighting the item/spell in question while in the favorites menu in order to map it to that specific hotkey. To actually USE that hotkey in game, simply press the directional button or directional button combination that corresponds with the hotkey you want to use. They are as follows: Left (1), Down (2), Right (3), Up (4), Hold Circle + Left (5), Hold Circle + Down (6), Hold Circle + Right (7), Hold Circle + Up (8). These controls will also be laid out plainly further into the guide. They are only listed here so you know they are available to use. 

#### Gameplay & Controller Configuration Tutorial/Demo

I've created a video that may make it easier for you to understand how the controls work as you'll be able to see them in action. It is HIGHLY SUGGESTED you sit through the entire video to properly understand this control scheme. I know it's long, but it will help.
https://youtu.be/hK_LAULD8G8 ***This video is now out of date, it will be updated in the near future***


## Keybindings

This section will list out the keybinding setup for both controller configurations as a reference. For those of you that want to edit things - feel free to do so but know that you void any support in the Tinvaak 2 support channels if you do. Also, keep in mind this setup was achieved with a combination of a custom_controlmap.txt AND the steam configuration - that means you need to know how to edit both before you try and change things with any chance of success. Modifying these settings isn't difficult, but it does require time, effort, and reading as well as research that you'll have to do on your own. 

### PS4/PS5:

I highly suggest you take a look at the configurations and familiarize yourself with the buttons. All have been labeled so you can easily see what button does what. They will also be listed for a comprehensive view of every keybind, but they will make more sense if you visualize them in the configuration. Make sure to switch between all three layers (Default, L1 Hotkeys and R1 Hotkeys). Keep in mind that while holding L1 or R1, any buttons that do not have a mapping listed here will perform the mapping from the default "layer" of the configuration.

![image](https://user-images.githubusercontent.com/89932487/139701647-784c6b6d-62f8-428e-885d-48621bcb802f.png)

Default Keybinds (No Modifiers)                            
- L1 - Modifier Button 
- L2 - Left Hand
- R1 - Modifier Button & Engarde Modifier (This is the key you have to hold to use a spell in the left hand while wielding a weapon in the right!)
- R2 - Right Hand
- Dpad Left - Hotkey 1
- Dpad Down - Hotkey 2
- Dpad Right - Hotkey 3
- Dpad Up - Hotkey 4
- Circle + Dpad Left - Hotkey 5
- Circle + Dpad Down - Hotkey 6
- Circle + Dpad Right - Hotkey 7
- Circle + Dpad Up - Hotkey 8
- Square - Sheath/Unsheath
- Cross - Activate
- Circle - Hold to Sprint, cancel, and hotkey modifier
- Triangle - Jump
- Left Stick Click - Sneak
- Right Stick Click - Lock On
- Right Stick Click (Hold for 0.25 seconds and then release) - Change POV
- Share (left side) - Wait 
- Start (right side) - System Menu
- Left Pad Click - Menu Control Sort Left
- Right Pad Click - Menu Control Sort Right
- Circle + Share - Tween Menu
- Circle + Left Stick Click - Favorites Menu

L1 Modifier Keybinds - This button must be held down for the following keybinds to work
- L1 + R1 - Shout/Power
- L1 + Dpad Left - Favorites Group 1
- L1 + Dpad Down - Favorites Group 2
- L1 + Dpad Right - Favorites Group 3
- L1 + Dpad Up - Favorites Group 4
- L1 + Square - Dodge Left
- L1 + Cross - Dodge Backwards
- L1 + Circle - Dodge Right
- L1 + Triangle - Dodge Forward
- L1 + Left Stick Click - Open Console
- L1 + Share (left side) - Immersive HUD Toggle 
- L1 + Right Pad Click - Shoulder Cam Switch

R1 Modifier Keybinds - This button must be held down for the following keybinds to work
- R1 + Dpad Left - Favorites Group 5
- R1 + Dpad Down - Favorites Group 6
- R1 + Dpad Right - Favorites Group 7
- R1 + Dpad Up - Favorites Group 8
- R1 + Select (left side) - Quick Load
- R1 + Start (right Side) - Quick Save
- R1 + Left Stick Click - Lichdom Mode Change

Campfire Actions (Hold Left Side Pad Button) - You must hold the Left Side Pad (LSP) Button for the following keybinds to work
- LSP + Square - Create Item
- LSP + Cross - Instincts
- LSP + Circle - Harvest Wood
- LSP + Triangle - Build Campfire

### Xbox:

I highly suggest you take a look at the configurations and familiarize yourself with the buttons. All have been labeled so you can easily see what button does what. They will also be listed for a comprehensive view of every keybind, but they will make more sense if you visualize them in the configuration. Make sure to switch between all three layers (Default, LB Hotkeys and RB Hotkeys). Keep in mind that while holding LB or RB, any buttons that do not have a mapping listed here will perform the mapping from the default "layer" of the configuration.

![image](https://user-images.githubusercontent.com/89932487/139708703-65997a20-a0f1-4206-ab2b-8ebd1bc35657.png)

Default Keybinds (No Modifiers)                            
- LB - Modifier Button
- Left Trigger - Left Hand
- RB - Modifier Button & Engarde Modifier (This is the key you have to hold to use a spell in the left hand while wielding a weapon in the right!)
- Right Trigger - Right Hand
- Dpad Left - Hotkey 1
- Dpad Down - Hotkey 2
- Dpad Right - Hotkey 3
- Dpad Up - Hotkey 4
- B + Dpad Left - Hotkey 5
- B + Dpad Down - Hotkey 6
- B + Dpad Right - Hotkey 7
- B + Dpad Up - Hotkey 8
- X - Sheath/Unsheath
- A - Activate
- B - Hold to Sprint, Cancel, and Hotkey Modifier
- Y - Jump
- Left Stick Click - Sneak
- Right Stick Click - Lock On
- Right Stick Click (Hold for 0.25 seconds and then release) - Change POV
- Select (left side) - Wait 
- Start (right side) - System Menu
- B + Select - Tween Menu
- B + Left Stick Click - Favorites Menu

LB Modifier Keybinds - This button must be held down for the following keybinds to work
- LB + RB - Shout/Power
- LB + Dpad Left - Favorites Group 1
- LB + Dpad Down - Favorites Group 2
- LB + Dpad Right - Favorites Group 3
- LB + Dpad Up - Favorites Group 4
- LB + X - Dodge Left
- LB + A - Dodge Backwards
- LB + B - Dodge Right
- LB + Y - Dodge Forward
- LB + Left Stick Click - Open Console
- LB + Select (left side) - Immersive HUD Toggle 
- LB + Start - Shoulder Cam Switch

RB Modifier Keybinds - This button must be held down for the following keybinds to work
- RB + Dpad Left - Favorites Group 5
- RB + Dpad Down - Favorites Group 6
- RB + Dpad Right - Favorites Group 7
- RB + Dpad Up - Favorites Group 8
- RB + Select - Quick Load
- RB + Start - Quick Save
- RB + Left Stick Click - Lichdom Mode Change
- RB + X - Create Item
- RB + A - Instincts
- RB + B - Harvest Wood
- RB + Y - Build Campfire


## MCM & Control Settings

You're nearly there! We just have a few steps left. First we need to add one line into our Skyrim.ini file in order for our power attacks to function as normal. If you aren't sure where the Skyrim.ini is or which one you need to modify, the easiest way to get to the one we need is through MO2. At the top-middle of MO2's UI you should see several icons. Click on the Folder shaped icon to bring up several options - we want the third option "Open INIs Folder." This will open up the folder containing all the INI files for the specific profile you're using in MO2. Find the Skyrim.ini and open it. Now find the "Controls" section and add this line below the other settings:
- fInitialPowerAttackDelay=0.15
If you miss this step, you won't be able to use your power attacks correctly! 

### Vanilla Control Changes and Import

The first step here is to go into the Tinvaak 2 install folder and then go into the "Game Root" folder. If you see a Custom_Controlmap.txt, delete it. Then go into your actual Skyrim Install's Data folder and delete any Custom_controlmap.txt if you see one. You shouldn't have one, but check just in case.

Now, we have a controlmap.txt within a mod that needs to be loaded by Skyrim. For us to ensure that happens, open up MO2 and ensure that the mod "Gamepad Specific - Modified controlmap.txt" is enabled (Click the box to it's left). It should be under the "Generated Files" heading and down at the bottom of the mods within that heading. 

![image](https://user-images.githubusercontent.com/89932487/134393263-30cf74d9-54a8-4c68-ba55-5b7945864817.png)

If you can't find it, in the lower right corner of the main mod pane, you should see a search box. Type in the name of the mod in this searchbox and it should narrow it down for you.

Finally, when you are in game and AFTER you have setup all the MCMs from the main guide, open the system menu and go into controls. Hit the button that resets the controls to default. This will ensure that our modified controls are loaded. 

### MCM Settings

It is imperative that you map all keys exactly as they are in this guide! The configurations were built around these specific keybinds, so if you change any of them, you'll have to change the Steam Controller Configurations and custom control map as well.

#### Campfire
- Gameplay
  - Hotkeys
    - Create Item - N
    - Build Campfire - B
    - Harvest Wood - H
    - Instincts - G

#### Classical Lichdom
  - Change Grip - K

#### Engarde
- KeyButton
  - Modifier - (Use your controller for this button) Set it to R1/RB. It will say LB is what mapped but worry not, this is intended.
  - Defensive Action Key - \

#### Immersive Hud
  - Activation
    - Compass Activation
      - iHUD Hotkey - X

#### SkyUI
  - Controls
    - Favorite Groups
      - Group 1 - F1
      - Group 2 - F2
      - Group 3 - F3
      - Group 4 - F4
      - Group 5 - F6
      - Group 6 - F7
      - Group 7 - F8
      - Group 8 - F10
      - Be careful not to map F5 or F9 here, we want to keep those free as they are quick-save and quick-load. 

#### SmoothCam
  - Following
    - Misc
      - Shoulder Swap Key - V

#### True Directional Movement
  - Target Lock
    - Controls
      - Enable "Toggle Target Lock with Toggle POV Button" 
      - I also personally go into the Target Lock Widget and make the lock on UI a simple dot and scale it down. That is, of course, up to you.

#### Quick Save and Quick Load
  
  - Your default control scheme is set for a quick save on R1/RB + Start and a quick load on R1/RB + Select

## Final Tips & Troubleshooting

While this setup has worked well in my testing, there are a few quirks that can and will occur. During my testing they did not hamper or stop my gameplay. I will attempt to address them all as I have encountered them. You will be directed back to the readme if you ask questions about these "quirks" in the support channel.

#### Dodging Quirks

If you never use lock on from True Directional Movement, you will never be able to use the directional dodging feature. When you press any of the dodge directions, you will simply dodge/slide/roll in the direction you are moving. This can be useful if you switch back and forth between locking on and not locking on. It is not a bug though, so don't ask in support as if it is.

#### SkyUI Favorites & Groups

If you're like me, you've never used the hotkeys provided by SkyUI. Well, if you want to really have fun, you need to change that up. I learned about them for the first time myself while I built these configurations. I have found them to be an amazing replacement for the somewhat script heavy Serio's Hotkeys that I use in every list. If you are unsure how the groups work, watch this [SkyUI Favorites & Groups Tutorial](https://youtu.be/FSrwmH4_dJM). Now that you understand how they work, you can fully utilize the 8 groups you have available from these configurations. You never have to pause during combat again, it really is amazing. 

Here are some tips I have for utilizing those groups on your 8 directional pad hotkeys. I tend to keep a theme on specific directional pad buttons. For example, the down directional pad button is easy to get to when you're in combat, so I tend to map healing spells there on the first layer (thats group 2 while holding L1/LB) and then I use the second layer as buffs which is group 6 (while holding R1/RB). Then I keep offensive magic on the two left directional pad hotkeys I have and utility spells for the up directional pad hotkeys. That leaves me with two slots on my right directional pad keys for two different groups of whatever I want (perhaps swords, bows etc...).

If you take the time to understand how these systems and features work, you will reap the benefit when you actually get around to playing the game.


#### You're Done! Have Fun!

#### Special Thanks
Althro and his team for making this awesome list
Chreicula For helping me create and test this setup
