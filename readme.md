
# RAVEN HUNT GAME

##### Deployed Link
https://ritahc.github.io/Raven-Hunt/

# User Story

There will be multiple moving objects flying around the screen, the player can shoot them with the help of cursor clicks and build-up their score.
The user shall be able to experience the following features in the game:
- `Landing page with a PLAY button`
- `Game Screen with 2 variety of birds flying accross`
- `Different action performed on hitting different birds`
- `Game Over Screen with a click event listener`

# Technologies Used

1. HTML5
2. CSS
3. Java Script
4. Vanilla Dom 
5. Sprite Animation

# WIREFRAMES WITH HAND WRITTEN NOTES

###### HAND WRITTEN FRAMES
below is a hand drawn picture of the proposed pages

1. Initial landing page :  
2. Game Arena - where players play the game and manipulate their score

![image](https://user-images.githubusercontent.com/119079394/209360150-48915a67-3cfb-493f-8f35-fe4a9156d98a.png)

3. End page - how the page would look after the game is over
![image](wireframes/EndPage.png)

###### FINAL FRAMES

1. Landing Page
![image](wireframes/landing.png)

2. Game Screen
![image](wireframes/Game.png)

2. Game Over Screen
![image](wireframes/GameOver.png)

# Code Info
1. Create a class of objects which shall move across the canvas area, in-and-out through a repeated animation loop
2. Repeated animation loop can be created with the help of `requestAnimationFrame(callback)` & timestamp
3. The objects could be turned into an `array and be filtered`
4. Objects leaving the canvas area can be `push()` 'ed out of the Array and .filter 'ed
5. Objects could be `spread accross the whole canvas`: with the help of Array literal `spread operator [... object]`
6. `Shooting can be done by using cursor.eventListener` 
7. `Coilision` can be targeted with the help of x, y, height and width values
8. Upon coilision the object disapears and the score increases
