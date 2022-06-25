# Emo's Outward Mount Mod

Currently I consider this 'early access' as there quite a few moving parts, I hope to have caught the majority of them but I can't promise a bug-free experience so you might want to back up your saves before installing it, I have found nothing game breaking so far...

The base mod comes with 3 types of mounts each with a few variations. 

There are 4 NPCs stationed in the 4 base game cities that allow you to store and retrieve mounts incase you decide to change later, currently there is no cost inccured to do this, but this might change later.

I'll leave it to people to find them in-game, currently they are world drops that have a small chance of dropping from everything you can loot.

The numbers will be adjusted later.

You must also set the three required keybinds(Follow/Wait, GoTo, Dismount) in the keybind options.


### Getting a mount

First you must acquire a whistle in order to summon a mount for the first time, after that it will follow you wherever you go with the caveat it can't follow you into places where there is no "NavMesh" for it to use these are usually places you would find no moving NPCs, one example at the start is the player house in Ciezro. 

You can still mount and ride them pretty much anywhere you would expect the player to be able to go.

### Feeding the mount

The mounts require feeding they lose a little bit of food passively over time and a little for X distance travelled while mounted, most of these settings can be changed in the XML files found in "MountSpecies" folder. 

Everything currently eats either Vegatables or Meat. The value on the UI for the food is the amount it will restore. With Favourite foods restoring more and making your mount happy.


### Utility
Mounts also come with a bag, mounts like the player have a carry limit, which is a combination of the things in the mounts bag and your own inventory. 
Generally mounts can carry more than the player can over longer distances quicker, with the draw back they need feeding more. 

The mount should also fully save including all its bag contents, please let me know if you run across any bugs.




## Known Issues
- You can steal the mounts bag by pressing "take all" with no items in the inventory, aslong as this bag is not destroyed or sold it should reattach itself to the mount on reload.
