# Javascript
Dear Bob
This project was inspired by our dorm cats. His name is Bob. He's cool and never takes the initiative to approach people. Every time I try to touch him, he always ducks, so I want to simulate this process with javascript. I recorded bob's voice, and put a button in the lower left corner, press the button to hear it (you can press it to turn off the sound if you feel noisy) I originally wanted to use PS to draw a cat, but I felt that I should make full use of the programming language, so the drawing process took me a lot of time, and it was actually a bit boring. The whole cat is based on pixels, I give each pixel a different color to compose it (I set a transparent color of 180px x 220px through the box, this color is the main color of the cat's body), and name it whole Regarding the avoidance setting, first I get the height and width of the screen, and finally return "bodyArr", which is used to calculate the X and Y values of the cat's positioning, so as to prevent the cat from moving outside the screen (at the end, use the while function as a conditional limit ) I set the bounds of the cat (mainCat), and if the mouse touches this area, the cat will start doing random movements. The position of the cat moves differently each time, so I named the position of the cat catMove, and recalculated the position of the cat with catX and catY: catMove(catX, catY). The position of the mouse is named with posX and posY, and finally the position of the mouse is obtained: posArr(posX, posY) I used randomnum to calculate the random value to ensure that the cat's movement is not regular Finally, the cat's trajectory is based on: screen size (bodyArr), mouse position (posArr) cat positioning (catX, catY) to randomly determine the cat's movement position.
