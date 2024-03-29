![IMG_popupGarfield_](https://user-images.githubusercontent.com/123922342/216668038-fe2cbf04-5f57-4672-b09c-5253f1166ddc.png)
![IMG_titleLogo](https://user-images.githubusercontent.com/123922342/215550843-e68b9da0-d5bb-406e-b9e8-9476328d5fd5.png)
![myname](https://user-images.githubusercontent.com/123922342/215526601-2f8fe170-f56c-483d-b5fe-c9e9c9a2d475.png)
## **Installation Instructions**

**For Windows:**

Download BepInEx 5.4.21 (do not download BepInEx 6, as the mod might not work) and choose either x64 or x86 based on your CPU's architecture: https://github.com/BepInEx/BepInEx/releases/tag/v5.4.21

If you don't know your CPU's architecture, I recommend downloading the x64 version as it's the standard architecture for most chips from Intel and AMD right now.

To locate your Garfield Kart - Furious Racing game directory: Open Steam and go to the GKFR page in your Steam library. Click on Manage (cog icon), Manage once more, and select 'Browse Local Files'.

Extract the three contents in BepInEx_x--_5.4.21.0.zip (winhttp.dll, doorstop_config, & BepInEx folder. You don't need changelog.txt) and move them to the 'Garfield Kart - Furious Racing' game directory.

Move the plugins folder that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to "Garfield Kart - Furious Racing\BepInEx".

At the same Garfield Kart - Furious Racing game directory from the previous two steps, go to "Garfield Kart Furious Racing_Data\Managed" and look for a file called 'Assembly-CSharp.dll'. Rename that file to 'Assembly-CSharp.bak' so you have a backup copy of the original file.

Move the modded 'Assembly-CSharp.dll' file that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to the same 'Managed' folder from the previous step.

Go back to the "Garfield Kart Furious Racing_Data" folder, head to "StreamingAssets\Windows", and look for the 'localization' file. Rename that file to 'localization.bak' so you also have a backup copy of the original in-game text.

Move the modded 'localization' file that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to the same Windows folder from the previous step.

Launch the game and enjoy! :3

If you want to remove the mod, delete 'ModImages' and 'TextureReplacer' in the plugins folder. Then, delete the modded localization and Assembly-CSharp.dll files as well. Rename the '.bak' versions of these files without .bak, and you're back to vanilla GKFR.


**For Linux (including Steam Deck):**

Download BepInEx 5.4.21 x64: https://github.com/BepInEx/BepInEx/releases/download/v5.4.21/BepInEx_x64_5.4.21.0.zip

To locate your Garfield Kart - Furious Racing game directory: Open Steam (in Desktop Mode if you're on Steam Deck) and go to the GKFR page in your Steam library. Click on Manage (cog icon), Manage once more, and select 'Browse Local Files'.

Extract the three contents in BepInEx_x--_5.4.21.0.zip (winhttp.dll, doorstop_config, & BepInEx folder. You don't need changelog.txt) and move them to the 'Garfield Kart - Furious Racing' game directory.

Move the plugins folder that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to "Garfield Kart - Furious Racing/BepInEx".

At the same Garfield Kart - Furious Racing game directory from the previous two steps, go to "Garfield Kart Furious Racing_Data/Managed" and look for a file called 'Assembly-CSharp.dll'. Rename that file to 'Assembly-CSharp.bak' so you have a backup copy of the original file.

Move the modded 'Assembly-CSharp.dll' file that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to the same 'Managed' folder from the previous step.

Go back to the "Garfield Kart Furious Racing_Data" folder, head to "StreamingAssets/Windows", and look for the 'localization' file. Rename that file to 'localization.bak' so you also have a backup copy of the original in-game text.

Move the modded 'localization' file that's inside GKFR.Fargield.Mod.vX.Y.Z.by.ElectricYoshi to the same Windows folder from the previous step.

Return to Steam (you can also go to Gaming Mode if you're on Steam Deck, but not necessary) and go to the GKFR page in your Steam library.

Click on Manage (cog icon), then Properties, and add this command in Launch Options: WINEDLLOVERRIDES="winhttp.dll=n,b" %command%

Now you can play Fargield Kart - Furious Racing! Happy Farg Karting! :)

If you want to remove the mod, delete 'ModImages' and 'TextureReplacer' in the plugins folder. Then, delete the modded localization and Assembly-CSharp.dll files as well. Rename the '.bak' versions of these files without .bak, and you're back to vanilla GKFR.

<sub>***Instructions for GKFR Mod Loader coming soon...***</sub>

## **Important Notes (MUST READ)**

1. If you are updating from an earlier version of Fargield Kart, replace all old modded files (including 'localization') with the ones from the latest release.

2. Please do not click 'Verify integrity of game files' in Steam (unless you *really* have to) after the installation of Fargield Kart. Otherwise, it will remove the modded localization file.

3. Upon launching GKFR with v1.9 of the mod installed, you may encounter some glitches. Please relaunch the game and it should work as normal.

4. If the mod causes the game to have performance issues, weird bugs, or graphical/texture problems, it is highly recommended to set the graphics quality in the options menu to Average. Alternatively, reinstall Garfield Kart - Furious Racing and try to install the mod again, or contact me for any assistance.

5. This mod is safe to use and cannot get you banned from online multiplayer. As it's a texture mod, it does not have unfair advantages that affect other racers. Furthermore, the texture mod will not permanently modify the game's files. Garfield Kart - Furious Racing has no anti-cheat and anti-modding measures, therefore, a ban is impossible.

6. Other racers who do not have this mod installed will not see Fargield. They will see regular Garfield instead.

7. "That looks nothing like Fargield. It's a recolored Garfield." *sighs* I know. I wish I knew how to remodel 3D assets, so he actually looks like the real deal. The longer fur and whiskers would have been great, but modding Unity games suck. Just pretend it's Modern Fargield, like Classic Sonic and Modern Sonic lmao. Actually, if this mod is a success, I'll see what I can do with the 3D modelling for a future revision. Stay tuned for more updates! :D

8. This mod has not been tested on the Mac version of Garfield Kart - Furious Racing (if you have tested the mod on a Mac computer, please let me know). This mod is incompatible with the Microsoft Store version of GKFR, a console version of the mod is very unlikely, and a GeForce NOW version is not possible.

## **Credits**

Jacob and Peter at Mired Media for blessing the community with the creation of Fargield, their support, and their own contributions to the mod!

Kumarin from F95Zone (NSFW website) for creating the Texture Replacer plugin (v1.0.4.1) for BepInEx.

SlamGrene from Newgrounds for designing the 16-bit Garfield Kart sprite as an SRB2K mod (https://slamgrene.newgrounds.com/news/post/1049269), and Peter (artofphn) for recoloring it into Fargield for the server icon.

Bacon King for making the Discord server an approved Garfield Kart community on the Garfield Kart Tournaments server. I would also like to thank the folks from GKT who joined the FargMired Discord!

Bare Tree Media for making the Garfield emojis and stickers, and the icon creators at Flaticon.com for the Hot Hog and Marmite emojis.

emniag (Digi) for being the mastermind behind merging the Fargield Kart server as also the Mired Media server, creating the Fargield Kart installer, original music for Mired Media, and outstanding work as a super friendly and attentive moderator!

Rogototo, Bacon King, and Canadong for fact-checking important README notes 5 and 6.

Special thanks to mattb_1, Udder_Calamity (for all the mooooos!), CaerbannogRabbit, fragilityv1, xxx514 and ggood003 for being awesome mod testers, as well as their amazing suggestions!

Big thanks and shoutout to the Catpak Crew for their wonderful support. Much love to them!

Shoutout to streamers - BlondiebutGeeky, CoalitionChris, and SpitefulGuppy!

This mod was created using images from Flaticon.com. Hot dog illustration made by Icon Place. Yeast illustration made by Smashicons.

...And BIG thanks to everyone who also supported and downloaded Fargield Kart - Furious Racing <3

## **Copyright Disclaimer**

Copyright Disclaimer under section 107 of the Copyright Act 1976, allowance is made for “fair use” for purposes such as criticism, comment, news reporting, teaching, scholarship, education and research. Fair use is a use permitted by copyright statute that might otherwise be infringing. Non-profit, educational or personal use tips the balance in favor of fair use. 

Garfield and the Garfield Franchise are owned by Paws, Inc. (Paramount Global). Fargield is a fan-made parody character for exclusively non-commercial and satirical fair use purposes.

Garfield Kart - Furious Racing is developed by Artefacts Studio and published by Microids (Anuman Interactive SA). They own all game assets.

This mod is not endorsed nor sponsored by Marmite (Unilever plc).

## **Latest Version**

https://github.com/FargieldKart/Fargield-Kart-Furious-Racing/releases/tag/v1.9.4

## **Discord Server**

If you need help with installing the Fargield Kart mod, or if you just want to race with other Farg Karters, check out the Official Fargield Kart Discord server: https://discord.gg/hyeM4wum4y

## **Images**

![Screenshot (11019)](https://user-images.githubusercontent.com/123922342/216668376-0ac2ad1d-1650-491f-b5c5-737b7d6cdd4b.png)
![Screenshot (11000)](https://user-images.githubusercontent.com/123922342/216668429-bebdbadd-4abb-444e-a2b3-32eaa05f151e.png)
![Screenshot (10968)](https://user-images.githubusercontent.com/123922342/216668600-adfc9d10-e66b-48ea-9e4e-01568fc44651.png)
![Screenshot (10723)](https://user-images.githubusercontent.com/123922342/216668815-b9fe1fca-98b8-48b6-8d75-ce06dde61244.png)
