#UNDERTALE Engine Start Tutorial
Welcome to my simple turorial about starting with Undertale Engine!

[TOCM]

#Downloading the engine.
To use this engine, you need Game Maker 2.

Game Maker Studio 2 is at **$39** per year, it is also at **$99** to have it permanently.

You need of minimiun the version **1.4** but here is a link to recommended version:

https://gms.yoyogames.com/GameMakerStudio-Installer-2.2.5.481.exe

***WARNING:*** Dont use pirated versions because your computer will have a virus or a malware... right?

Then, when you have Game Maker 2, follow these steps:

1. Go to the engine github: https://github.com/Animelici804/undertale_engine_legacy (This isn't the original github, but original engine was canceled. also original link is: https://github.com/TML233/undertale_engine_legacy)
2. Fork the engine with the button Fork.
3. Download GitHub Desktop (https://desktop.github.com/)
4. Clone the repository to your computer.
5. After finishing cloning, click Branch → New branch, create a branch based on the master branch. You will develop your game on this new branch(hereafter referred to as the game branch).
6. Click Show in Explorer And open the file named undertale_engine

With that, you can start using engine.

#Learning Game Maker
To use this engine you need to know about GML basics. 
I recommend these channels to start:

##Lets learn Game Maker
https://www.youtube.com/c/letslearngamemaker/playlists
-For the newest of beginners. Learn the interface and the basics of GMS

##Space Rocks YoYoGames tutorial
https://www.youtube.com/watch?v=raGK_j1NVdE
-Space Rocks, an easy to understand beginner's course to learning GMS. I recommend just jumping in with the code version and not the drag and drop.

##Game Maker Station Matharoo
https://www.youtube.com/c/GameMakerStationMatharoo/playlists
-Matharoo has many videos covering a great range of concepts for beginners and beyond.

##Shaun Spalding
https://www.youtube.com/c/ShaunSpalding/playlists
-Shaun has many tutorial video series that cover games like platformers and action rpgs. Great knowledge from here can be transferred to your Undertale Fangame. Slightly more advanced than the other options here.

##Cosmonaut
https://www.youtube.com/c/FriendlyCosmonaut/playlists
-Cosmonaut has tutorials and topics on subjects that are a little more advanced, but still great information on making games.

#Starting with engine.
WARNING: Don't change the project name or you will have problems updating engine.

Open Options → Windows in the Resources window. Change the value of the Executable Name box to your game name. Don’t forget to click OK!

Open the script `Macro_Game`, change undertale_engine in `#macro GAME_NAME “undertale_engine"` to your game name. For example:

```gml
macro GAME_NAME "undertale_a_new_hope"
```
Save the script.

##Updating engine
When there’s a update, checkout the master branch, click Update from … in Github Desktop. If there are merge conflicts, fix it. Then checkout the game branch, merge the master branch into the game branch. If there are merge conflicts, fix it.

##Learning engine
This engine has so much things to learn. Here is documentation link:
https://docs.google.com/document/d/1Z3522rB_iudRIpaj6EOw9KFZJre4gA3ZzgC5G-CM8WQ/edit?usp=sharing

#Alternatives to use this engine.
REMEMBER: Gamemaker is not a program we recommend pirating for. You'll very likely be hit with a virus or some other form of malware. Please only use the free trials yoyo games offers, or buy the product. Your computer safety comes first. Please note the alternatives mentioned here are unaffiliated with us, and are just my own recommendations.

##Scratch engine
https://scratch.mit.edu/projects/224896574/#player
-Extremely beginner friendly and free. Only battle

##Unitale/Choose Your Frisk/Choose Your Kris
https://www.reddit.com/r/Unitale/comments/akhrcs/download_links_guides_and_help_for_unitale_and/
-Both an Undertale Engine and Deltarune Engine. Battle/Overworld

While it uses LUA, a beginner's programing language, learning how to use CYF/CYK is a learning curve and can be confusing to new comers. CYF is a fork of Unitale. You do not need a copy of Unity to run or make your own Undertale battle, but will be necessary for the overworld. You can get around this with a mod of CYF that has a scripting version of the overworld. Unity however is not beginner free, so if you do choose to make your overworld in unity, understand Unity was made for 3d and can be less intuitive to learn. The actual programming of the engine is beginner free, while Unity is less so.