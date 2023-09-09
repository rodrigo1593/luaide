# luaide (private rn)

attempt to make an environment a little easier to make games for ps2 using enceladus.

----------------------fixes--since---03-sep-2023---pm----private----------------------

* attempt to make an object moving failed in negative directions. solution: just swap the value and the object array name XD.
* while creating a room the objects array type are not being defined correctly. solution: similar variable to "onetime". to allow it to do it once everytime a new object is found in .room files

----------------------fixes--since---04-sep-2023---am-----private----------------------
* no more .png , instead .spr + any image extension i guess.

----------------------fixes--since---05-sep-2023---am-----private----------------------
* now if there is no sprite assigned then the object will show default sprite instead

----------------------fixes--since---06-sep-2023---am-----private----------------------
* remove image name+extension requirement.
* sprite specific menu is bugged somehow idk the reason rn but it displays the wrong image/the first image created (xoffset yoffset menu) solution: delete sprclone sprite if exists.


----------------------fixes--since---06-sep-2023---pm-----private----------------------
* add mus files to detectext() function

----------------------fixes--since---07-sep-2023---am-----private----------------------
* continue music editor menu (more things). (just an audio preview (listening), simple as that lmao)
* output the get left stick & get right stick functions correctly


///////////////////////////-------------TODO--------/////////////////////////////////////////
* somehow force the sprite function to be used as drawable instead of being used as reference for the ide to place the object inside the rooms.
  ->problem 1: less control on what should be drawn or not.
  ->problem 2:  funny and safe tho.
  
* convert objects into two types: preparable & loopable. (shit names xd) -> problem 1: less control on when should you use while loops.
* script, function will now open a big but simple text editor to allow writing scripts more than one line lmao.

* play audio function.
* now i hope you can prepare adp's long array in order to play audios.
* dinamically change and watch changes made with the sprite in sprite editor instead of loading the same sprite default properties every menu.

* rewrite rooms menu+room editor
