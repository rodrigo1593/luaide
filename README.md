# luaide (private rn)

attempt to make an environment a little easier to make games for ps2 using enceladus.

----------------------fixes--since---03-sep-2023---pm----private----------------------

* attempt to make an object moving failed in negative directions. solution: just swap the value and the object array name XD.
* while creating a room the objects array type are not being defined correctly. solution: similar variable to "onetime". to allow it to do it once everytime a new object is found in .room files

----------------------fixes--since---04-sep-2023---am-----private----------------------
* no more .png , instead .spr + any image extension i guess.

----------------------------------TODO------------------------------------------------
* sprite specific menu is bugged somehow idk the reason rn but it displays the wrong image/the first image created (xoffset yoffset menu)
* somehow force the sprite function to be used as drawable instead of being used as reference for the ide to place the object inside the rooms.
* convert objects into two types: preparable & loopable. (shit names xd)
* remove image name+extension requirement.
* continue music editor menu (more things)
* add mus files to detectext() function
* script, function will now open a big but simple text editor to allow writing scripts more than one line lmao.
