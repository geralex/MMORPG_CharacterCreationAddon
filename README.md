# MMORPG_CharacterCreationAddon
 Codes and Scenes to Modify ur Character at run time. Tested with Synty models
These are the Items that the addon uses to setup ur List of Facial prefabs in the Creation UI

Donations are welcome 
Paypal: xxCallepoxx@gmail.com


Kit Version 1.50C is recommended
Tested with FantasyHeroes pack from Synty ( this asset is not included.. )
If u set ur prefabs right it should work with all models that have Facial textures that u can swap

Tested in Singple player and Mmo mode (Multiplayer) 

For information bout how Races work check this thread
https://github.com/insthync/UnityMultiplayerARPG_CharacterRace


Just Import the Asset File u get when u download the Files

![Database Files](Githubcreator/DatabaseFiles.JPG)

U need 4 charactermodels at all times
There are 2 Races and 2 Genders.. u need 1 model per race and gender 
So aka 4
With these 4 if u have enough prefabs for costumization u can make over 100 different models in game

![CharacterModels](Githubcreator/Characters.JPG)


Setting up the Slots for ur Characters so it can equip the items on ur model

![Slots](Githubcreator/Slot.JPG)

On the player models u find the PlayerCharacterEntity script where u can set Genders and Race for ur models

![PlayercharacterEntity Script](Githubcreator/PlayerCharacterEntity.JPG)


These are the Armour Types needed to Desstinguish ur Prefabs from each other.. basically saying which is which

![Types](Githubcreator/Types.JPG)

These are the items that need to be inserted into the database so the game knows what he can use.. 
Right now there are 2 of each in the database.. Game auto checks them and fill the list.. and shows 2 in game
If u add more it auto updates to how ever much u put

![CharacterFaceItems](Githubcreator/CustomItems.JPG)

Have Fun.
![Ingame View](Githubcreator/Example.JPG)
