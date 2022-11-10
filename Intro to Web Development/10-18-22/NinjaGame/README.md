This is my submission for the Ninjaman Assignment for CodingDojo

Controls:
Ninjaman Movement-Arrow Keys

Game Functions:
Onigiri = 1 pt
Sushi = 5 pts
Scared Pumpkin = 25 pts

Pinky spawns at beginning of game
Bluey spawns at 25 pts
Pumpky spawns at 75 pts
Red spawns at 150 pts

Pumpkins in their normal state advance towards ninjaman
Sushi puts pumpkins into scared state, making them edible
Pumpkins in the scared state move further away from the ninjaman
When all of the food from the map is eaten, another map is procedurally generated
When Ninjaman position and pumpkin position are the same, the game is over

Known Bugs:
When spawning a new pumpkin, it's possible that it will create an image of the pumpkin in the 1,1 position
This pumpkin is apart of no element in the HTML, so I believe it has something to do with the asynchronous nature of Javascript
I tried to fix it by making the program wait for the initGhost() function to complete before continuing to no avail.

Occasionally a pumpkin will spawn outside of the world
I tried to fix it by setting the bounds of a pumpkins spawn to the world borders to no avail.

A general browser refresh will reset the world and hopefully temporarily fix the issue

If the player spawns in an enclosed section with no food, simply moving the character will make the program register there isn't any food and move onto a new world




If you want to change the game size, you would have to go into the html file and change the width and height variables



