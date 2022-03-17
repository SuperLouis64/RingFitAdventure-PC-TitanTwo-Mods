# RingFitAdventure-PC-Mods
This a collection of .gpc scripts that mod the Ring Fit Adventure controller scheme for the PC. This allows the user to attempt to exercise while also playing their favorite game. Overall design of the mod is to mirror Ring Fit Adventure. The joystick is locked behind the movement of jogging in place while squeezing or punching with the joycon does an action in game. If you aren't jogging, you aren't moving. The idea of these scripts is to provide a template for you to work on if you need something specific. If you end up using these scripts/mods in your project, YouTube, Twitch streams, etc, all I ask is to be credited. Don't be a jerk about it. Stealing or not crediting is a quick way to put things like this behind a paywall. Credit me on twitter [@SuperLouis_64](https://twitter.com/SuperLouis_64) and on [YouTube](https://www.youtube.com/channel/UCaG9FzEfuHkvh7J6W6MH4eA). 

### Current Mods 
- Dark Souls X Ring Fit Adventure: Tutorial here: <https://www.controllerbend.com/darksouls-ringfitmod.html>

### Hardware Needed
This mod needs some hardware to get running. I have a full tutorial on my website if you need more information: <https://www.controllerbend.com/darksouls-ringfitmod.html>
- Titan Two Input Converter
- RingCon and Legstrap (not needed but helps)
- Titan Two Wireless Expansion Kit

### Software Needed
To interact with the Titan Two, you'll need to download Gtuner IV. "Gtuner IV is the main software for programming, updating and configuring the Titan Two device, featuring an complete IDE with integrated compiler for the GPC script language. Gtuner IV also provides user friendly interfaces for easy download, configure and use gamepacks or user made scripts. Based in a modern framework, Gtuner IV supports multi-platform, high resolution monitors and localization" - ConsoleTuner's site. 
- Download the software here: <https://www.consoletuner.com/titan-two-downloads/>
- Make sure to read over how the hardware/software works on the website. It'll save you a good amount of headaches.

### How to Set-up the Mod
I have a more in-depth way to set-up these mods on my [Dark Souls X Ring Fit Page](https://www.controllerbend.com/darksouls-ringfitmod.html)
1. Connect your Titan Two to your PC via the OUTPUT port
2. Connect your Titan Two to your PC via the PROG port
3. Connect a Xbox 360 or Xbox One controller to the SLOT B port
4. Open up the Gtuner IV software
5. Load the .GPC file to the Gtuner IV GPC Script IDE
6. Connect your joycons to the Titan Two via the Device Configuration tab on the right side of the UI. (Use the "Wireless Bluetooth Pairing" button after activating the JoyCons Sync Button")
7. On GTuner IV, under "Device Configuration", Make sure the Output Protocol is set to either: "USB Automatic" or "USB Xbox 360"
8. Press the Green "Test and debug" Arrow on Menu file
9. Enter into your game's window and have fun!

### FAQ
- Q: Do I need the Wireless Expansion Kit?
- A: Yes, you can't connect to your Joycons without it.

- Q: My Squat/Run doesn't work very well
- A: You'll have to test somethings out and replace numbers in the squat and running functions. In the code I have comments showing how things work and you can see the values of your joycon in the Device Monitor. I do this for free and currently do not have the time/financial grounds to make this a 1:1 mod to Nintendo's product.

- Q: Why does [insert button here] not press [insert another button here], it would make more sense "..."
- A: These are template scripts! The cool thing about PC games is that you can changes the button inputs in-game. For Example, I did not mod the buttons on the joycon outside of locking the joystick. If you don't like the current button assignments you can remap them in-game! 

- Q: This is a bit expensive, is there a cheaper option?
- A: At the moment no. I'm staring to work on an Arduino version that will significantly reduce the cost of the mod and provide more room to work with! As of writing this Readme file, there is no other way to play games with the ring fit adventure mod that is as plug-and-play and easy to use. There are other really cool ways to do this that require drivers, multiple softwares running at the same time, and in some cases 3D printing and making your hardware. My goal is to make it as easy as possible to do this so anyone at any level can do this. I want my Arduino version to do the same thing!

- Q: Can I use/mod/update this for my projects!
- A: Yeah! If this ends up making you money or content that makes money please hit me up! Just keep in mind that a ton of time and work goes into this and don't be a jerk about stealing content. 
