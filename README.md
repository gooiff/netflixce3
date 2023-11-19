# NetflixCE - Reupload

- Previous repos was taken down, here is an archive incase it gets taken down again
  -REMOVED-


- the file was also uploaded in this Discord server, any new updates will be announced in here
 https://discord.gg/short 

Note: Please don't download any "Byfron Bypasses" you see online, most are rats as there aren't any "public" executors that can successfully inject into Roblox. This is the only currently known method of exploiting on the web version of roblox

A modified cheat engine created exclusively for the purpose of injecting into Roblox—a reformed tool that bypasses previous Cheat Engine (CE) detections, enabling successful script injection. Please note that CE is limited to thread identity 2 as it runs via localscripts, but it can handle substantial scripts such as Infinite Yield. An internal executor is also provided to enhance your exploiting experience. It's important to clarify that a separate tool is required for injection. This is because the script runs through the LocalScript parented to the tool. Once downloaded please read the "README_IMPORTANT.txt" to fully understand how to achieve successful injection. For any claims about this being a virus, everything was left open sourced. The tool itself is just a compiled version of Cheat Engine designed to attach to Roblox without crashing (lol).

Game link: https://www.roblox.com/games/15167092402/Baseplate


# VIDEOS


New showcase video release by inposs, W man go sub to him


https://www.youtube.com/watch?v=GtYHeCf2i5A&ab_channel=inposs



Tutorial vid (Not uploaded by me)



https://www.youtube.com/watch?v=W1qXPGQpxSc



https://www.youtube.com/watch?v=G3MhOPE0G2s&ab_channel=Anoyingguy



# How to create your own undetected CE for Roblox web client



-- Download the Cheat Engine source

https://github.com/cheat-engine/cheat-engine/releases/tag/7.5


-- Download the lazarus compiler, download the cross compiler in the same directory

https://sourceforge.net/projects/lazarus/



-- If using a win 32 OS, set the target to 64 Bit



-- select Project --> New Project and open cheatengine.lpi from the CE source



-- Ctrl + F and look for these 2 strings



00000000000000000

00007fffffffffff



(put 00007fff in the search if no results are found)



-- Change both values to "waiting………"



-- Change CE process icon either via lazarus or process hacker



-- Select Run --> Build and compile



-- Once compiled, open HxD and rename "Cheat Engine" to a different name with the same amount of characters



-- Voila, a undetected CE that works on both UWP and Web



# Errors


If you're getting pop-ups that say something along the lines of "Missing DLL Files VCRUNTIME140D.dll" Download the Visual C++ Redistributable package below



https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/



![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/afe05adc-3078-45d4-a79b-86bf405f2295)




if you get a targetScript error, this indicates that the localscript's memory address wasn't found. This can occur sometimes and if it happens, rejoin the game and re-open Netflix (Pin netflix to task-bar so you don't have to open Windows Explorer each time). If the error keeps showing up it could be that the tool does not have a localscript to target.



![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/6be8f324-ff8b-4794-b794-62e6c5f7e7b5)



This error indicates that roblox has not attached to CE, for UWP the process name is "Windows10Universal.exe", for Web the process name is "RobloxPlayerBeta.exe". Netflix has already been configured to attach to both automatically upon opening, don't open Netflix before the game is launched otherwise no process will be selected. If it says RobloxPlayerBeta.exe but still gives the same error, before injecting open the little computer icon, go to the processes tab and select RobloxPlayerBeta.exe



![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/003e85f4-82be-42e2-b57a-c6a6760cce0f)




![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/5357297d-b482-426b-aea6-3dbb688eda0a)




These are the two most frequent errors, if any other errors occur, restart Netflix and roblox and make sure a tool is located in your backpack (Equip a ability other then dash for blade ball). If web client keeps crashing, close netflix application and run through netflixprocesshandler.bat. If crashes still occur use UWP to inject into that specific game.



Credits to jay for the tool injection method, though his thread was left quite ambiguous and only allowed for dex explorer to be executed, a functional "executor" was able to be created to aid users with exploiting on the byfron client. I will make a video soon fully explaining the method and showing how you can modify scripts to run on the 64 bit client but videos above showing the tool being used were linked. The executor UI itself is just a placeholder as I plan to work on a better one with added features, busy with irl shit but I do plan to release frequent scripts and new additions.



![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/41071078-eb28-43dd-955c-fef55e68c05a)




![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/c7b94b68-1b09-4de2-847b-0bb50e662854)




Recently accusations have been spreading from the exploting server known as Rune, all of them have been proven false and have 0 evidence proving their claims to be true. The netflix file is simply a modified CE I compiled to work on 64 bit client with jay's injector. The localscripts that allow for ingame execution are all provided in the game. The original game (CE2) was uncopylocked for anyone to be able to load their own scripts via studio, though the game was downloaded and stolen by skids from Rune, being claimed as their own and used for their probably ratted CE (also forked from Netflix, proven by the "ByfronInjector" ui I made still being there). Will be linking some further screenshots regarding this situation down below. I don't advise anyone to download anything from Rune, considering they have a shady presence overall.



-- Credits to plusgiant5 for the process handler script



↓↓↓ Referring to Rune



![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/eb4abaa3-2f2c-441a-b28e-1278e13ee4e4)




![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/dd4543fb-4aff-430c-b6eb-2aea0286e4d1)


![image](https://github.com/IShade4ReaI/NetflixCE---Reupload/assets/143328800/f6a7dc33-1826-4073-ac96-7b5a1c0797dc)
