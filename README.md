Sunless Sea: Rewritten
	by Nonagon (and others)
	
	
***Overview***

Sunless Sea: Rewritten is a massive undertaking to completely rewrite Sunless Sea from the ground up. Every port, every officer, every story is completely rebuilt, creating an entirely new Sunless Sea experience.


***Installation***

**To install the game files:** Find the relevant files at User/appdata/LocalLow/Failbetter Games/Sunless Sea. Before making any changes, either manually save in-game (which will cost you your Invictus Token) or go into the Saves folder and backup autosave.json somewhere safe. Then, head to the addon folder and copy the entire Sunless Sea Rewritten folder and all its subfolders into it. Be aware that due to changes to the map, starting a new game is required to prevent glitches.

Warning! Adding mods is easy, but removing them is another matter. Once a game has been saved with modded files, that save will no longer function if those files are removed. To remove Sunless Sea: Rewritten, delete the Sunless Sea: Rewritten folder from the Addons folder and revert back to your old save file. Additionally, be aware that not all mods will play nicely together.

**To install images:** Back out of the addon folder and enter images, then sn, then icons. Copy all of the image files in the provided SSR Images folder into this folder.

**To install music:** This one is a little more involved and requires an external download. Don't worry, I'll walk you through it.

First, download a stable version of the Unity Assets Bundle Extractor, found here: https://forums.7daystodie.com/forum/-7-days-to-die-pc/game-modification/tools/23262-unity-assets-bundle-extractor?22675-Unity-Assets-Bundle-Extractor=

Next, navigate to the Sunless Sea program files, most likely located at C:\Program Files (x86)\Steam\steamapps\common\SunlessSea\Sunless Sea_Data. Before doing anything else, create a new folder called Backup and copy the resources.assets file into it.

In a separate window, open the provided SSR Music folder. Copy the SSR_Music.resource file into the Sunless Sea Data folder.

Open the Unity Assets Bundle Extractor. Using the UABE, open the globalgamemanagers file in the Sunless Sea Data folder - the regular one, NOT the .assets one.

Click View > Search by name, and search for one of the names of the text files in the SSR Music folder. Select the file that you're navigated to and click Import Dump, then import the text file of the same name. This will tell the game where to find the music file and when to stop and start it. Repeat this process for each text file.

Click OK. You can't overwrite files with the UABE, so save your new .assets file under a unique name. Once it's saved, delete resources.assets and rename your new file to resources.assets.

Celebrate with cake and wine.

To uninstall the music: Delete the modified resources.assets file and replace it with your backed-up copy.


***Credits***

Failbetter Games (the game)

Nonagon (Lead writer and lead programmer)

Athanor (Writer and business manager)

Eastwood (Writer and lead musician)

CuisineCat (Artist)

Eloïse Mushroom (Artist)

snurtle (Artist)

Dratoran (Writer and programmer)

GavnerPurl (Writer and editor)

Brogues (Ideas, Discord help)

Auriculas (Ideas, editing)

quasimonomial (Ideas)


***Changelog***

v.0.09

-New art, from new artists!

-So much new music!

-Nuncio is now Henson's Landing, where Clothfolk sing and play

-Mount Palmerston is now Aditta, birthplace of Wyrms and home of the Molten Monks

-Frostfound is now Silver's Palace, lair of one of the great Wyrms

-Port Cecil is now Seaglass, mirror to other times and places

-Hunter's Keep is now Clayborne Place, home to a high-society London family

-Saviour's Rocks is now The Old Magnanery, where spiders hope to one day be like Londoners

-Aestival is now Founder's Island, where nothing is as it seems

-Demeaux Island is now Blemmiglugh, which isn't as deserted as it appears

-The Empire of Hands is now Hypatia, a scientist queen's home

-Gaider's Mourn is now Trojan's Rook, where the wicked Mistresses flock together

-Port Carnelian is now Crying Heights, where toiling nomen harvest wax-winds

-Adam's Way is now Bracksoot, a terrified London colony on the edge of the world

-Kingeater's Castle is now the Theatre of Tyrants, where Kings of the Zee are crowned

-Wisdom is now Oishigetta, a Shogunate fortress under assault

-Khan's Glory is now Namerigawa, the artistic side of the haunted Shogunate

-Khan's Heart is now Neokamakura, the military side of the haunted Shogunate

-Khan's Shadow is now Kantai, the floating fortress of the immortal Shogun

-The Wreck of the Nocturne is now the Wreck of the Repressor, a warship vanished under mysterious circumstances

-The Chapel of Lights is now Mekhane, thousands of potential ports in one

-Avernus is now Dresden, a sunny place where nothing bad could ever happen

-Naples is now Guernica, an equally happy place where surely nothing bad will ever occur

-A brand new area, New Newgate Prison, has been added to the game

-Heading East or West off the map now leads to new events

-A horde of new, non-functional Officers have been added to the game

-Smoking A Box of Cigars at zee will lower your Terror! Just don't smoke too much...

-Minor bug and text fixes
