# Tool Learning Log

Tool: **Kaboom.Js**

Project: **Platform game/ zombie shooting game**

---

11/6/23
* First I went to Kaboom.Js and read the tutorial. I inputted the script src code to my html file. Then I needed an canvas for the project. So it was between putting ``<canvas id="game"></canvas>`` or going to replit.com to do it. Luckily, replit had an inbuilt kaboom file that you can create, and it comes with the template of the background and a green frog. I tried inputting some effects to the mouse when everytime I click, an certain effect will pop out. 

11/13/23:
* Today on Kaboom, i tried adding a sprite character to my canvas. Then I tried adding the Player and making the player move via WASD. Since I'm making a zombie shooter game, i need enemies. So I added more spirtes as the zombies. 

12/18/23


* Tried to move the spirtes. 
  ``
keyPress("space", () => {
  if (player.grounded()) {
    player.jump(320);
  }
});
``


   To use arrows keys to move left or right I did
   ``
keyDown("right", () => {
     player.move(120, 0);
});
 ``


  ``
  keyDown("left", () => {
  player.move(-120, 0);
});
``                                    
