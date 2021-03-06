# road-to-yuzu-without-switch
This Repo explains how to install the yuzu Switch Emulator without a Switch on a Windows PC

[![Twitter URL](https://img.shields.io/twitter/url?label=Follow%20me&style=social&url=https%3A%2F%2Ftwitter.com%2Fprincessakari_)](https://twitter.com/princessakari_)
[![Discord](https://img.shields.io/discord/622504866132000768?logo=Discord)](https://discord.gg/8AyNesa)

  * [Introduction](#introduction)
  * [Guide](#guide)
  * [yuzu-Setup](#setup)
   * [Needed-Files](#files)
   * [Settings](#settings)
   * [Games](#games)
  * [Additional](#additional)
   * [GameUpdates](#gameupdates)
   * [GetKeys](#getkeys)
   * [Mods/Patches](#Addons)
  * [Goodbye](#goodbye)



 # Introduction
 Hey, im Akira and I'm writing you a guide on how to install yuzu without having a Switch, since I discovered this is literally a pain in the ass.
 I try to make it as easy as possible, but be sure to check this out if you need new keys, since I try to keep this always up-to-date! <3

 # Guide

  # Setup
 First you will need the [yuzu-Installer](https://github.com/yuzu-emu/liftinstall/releases/download/1.8/yuzu_install.exe).
 Open it, and let it do its own stuff and be sure to have it like this.
 ![yuzuInstall](https://fuckedyour.doctor/jHMFQqDS.png?key=r2dUCnMvj8qhPR)

 After it's done just press Exit and search for yuzu in your Windows searchbar.
 ![yuzuWeilPrime](https://sexin.church/dVZ1smTb.png?key=56adoSGTXNiWYu)

 yuzu will open and show this screen
 ![DuBistDoof](https://nuke.bayern/9RTatw4x.png?key=J7cFCPraHXStHb)
 on there click Emulation -> Configure -> System -> Profile
 Then press on Add and make a new profile, then close yuzu

  # Files
 Inside of yuzu click File -> Open yuzu folder.
 This will open the yuzu configuration folder inside of explorer.

 Create a folder called "keys" and copy the key you got from [here](https://drive.google.com/drive/folders/1i17XAjiwKLwml_9mzLQ4GF6RYidaCFcG?usp=sharing) and paste it in the folder.
 Then go back out of the keys folder and paste the contents of the Switch firmware folder found [here](https://drive.google.com/drive/folders/19wfoBUpXyqxJdzADhepPBYm_A-xDUNKa?usp=sharing) and click yes if it wants to overwrite any files
 ![CaccaIsCute](https://fuckedyour.doctor/iQ6Yvxxj.png?key=Tka82acKrlYqlS)

  # Settings
 For settings open yuzu up Emulation -> Configure -> Graphics, Select OpenGL and set it to Vulkan.
 Then go to Controls and press Single Player yadiyadiyada and set it to this
 ![Reeeeeeee](https://nuke.bayern/tQRi6Dco.png?key=TKvixrA2KWor0u)

 Then Press Configure and set Player 1 to Pro Controller if you have a controller/keyboard and to Joycons if Joycons.
 Press Configure and press the excat buttons on your controller (it's easier for Xbox but for you PS4 and keyboard users I have a graphic for yo found [here](https://compass-ssl.xboxlive.com/assets/c7/a1/c7a12fbe-af04-4a90-92f2-18338219c2aa.png?n=one-controller-front-l.png))
 After you're done press Okay and continue to the next step.

  # Games
 Download any ROM you want from any ROM Website you like.
 I recommend [Switch-XCI](https://switch-xci.com/), but any ROM Site does it.
 After you got your File (can be .xci or .nsp) create a folder somewhere on your PC and in that folder create another folder for your game.
 After that double-click into yuzu and select the folder you put your game folder in.
 ![UwU](https://sexin.church/7CT7o3Sr.png?key=XuV6NAPCK1ZTH0)
Now the game should be in the list. Next do what I do in the gif below
![GIFFFFFFFFFF](https://fuckedyour.doctor/DVR1L6Fo.gif?key=2I5FdMRG7pL8HA)

 # Aditional

  # GameUpdates

 Download the update of your game or DLCs, usually as a .nsp.
 Put it in your folder of the game, then open yuzu. Do exactly as in there
 ![rererere](https://i.uwu.plus/hNmEGB8V.gif?key=gGAX37XVMM7o1q)
 For me it was already installed but it should then show under addons that you have it installed

  # GetKeys

 To get keys easily just go to [this Subreddit](https://www.reddit.com/r/yuzuPiracy/) and look for posts with prod.keys
 Then just paste their code into a [decoder](https://www.base64decode.org/) and copy the keys and paste them in a newly created file called prod.keys

  # Addons

 Here ima show how to install mods.
 It's pretty simple, we're gonna take the mod from [here](https://gbatemp.net/threads/pokemon-mystery-dungeon-dx-60-fps-mod.559469/)
 When you download the zip file you will have a folder called "exefs_patches".
 Go inside that folder and in the other folder in there until you are at this file with an .IPS
 ![memememem](https://nuke.bayern/QTwbBtLy.png?key=GP1JZ3BylhCn9q)
 Then move that IPS file into exefs_patches and delete the now empty folder.
 Then rename exefs_patches into exefs.
 Now open yuzu and rightclick your game -> Open Mod Directory.
 Create a new folder with any name you want and move the exefs folder into that, then restart yuzu and you're done.
 You now see your mod at compatibility.
 - Additional Note here:
 If you got any other names for the folder don't rename it to exefs.
 Instead rename them to romfs or romfs_ext.

 You can completly skip these steps if you use mods from [here](https://github.com/yuzu-emu/yuzu/wiki/Switch-Mods)

  # Goodbye

 Thank you for reading this, I hope it helped you with your start into Switch emulation.
 If I forgot something just create a Pull Request with the stuff added and I will review it ASAP.
