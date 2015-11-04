# Pacman_clone
  A small Pacman-like game written in Javascript with Canvas.
  
##Aim
  The aim of the game is to get as many points as you possibly can, points are gained mostly by eating food.
  You must eat all of the food on a level without being attacked by a ghost. If you achieve this, then the food will be
  reset, and you advace to the next level. 
  
  You have to see how much food you can eat before dying, your score will be saved in the highscores,
  should you get enough points.
  
##Controls
  The game is controlled primarily by the user's keyboard.
  You can use the directional buttons, or as most keyboard gamers prefer,
  you can also control the game with the "W" "A" "S" and "D" buttons. 
  
###"Up"/"W"
    By pressing up or W, the user will move pacman up if there is an available move there.
    
###"Left"/"A"
    By pressing left or A, the user will move pacman left if there is an available move there.
    
###"Right"/"D"
    By pressing right or D, the user will move pacman right, if there is an available move there.
    
###"Down"/"S"
    By pressing down or S, the user will move pacman down, if there is an available move there.
    
  Should the user ask pacman to move to a blocked location, that keypress is saved, and pacman will keep trying to 
  move for example, up until it either does move up, or the user presses a different key
  
##Scared mode
  If the user eats a superfood, all of the active ghosts will suddenly become terrified of you. They will run away, 
  flashing between blue and white. When a ghost is scared, you can eat them too.
  
##Death
  Outside of the above scared mode, you should not touch the ghosts, they will cause you to lose a life.
  You start out with only three lives, so don't die!
  
