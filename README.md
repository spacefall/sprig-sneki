# sprig-sneki 
A snake like game with different foodstuffs that have different effects  
*[Now on sprig.hackclub.com](https://sprig.hackclub.com/gallery/sneki)*

![Preview photo](https://github.com/spacefall/sprig-sneki/blob/main/preview.png?raw=true)

## Instructions
Use W, A, S, D to move the snake up, left, down and right respectively.
Use K to start/restart the game.

Once the snake reaches the borders, it will loop around (unless the orange effect is active).
Eat foods to increment the score.
The different foods have different effects, only apples are neutral (just increments the score):
- Melons: switch the snake's head with its tail
- Cherries: add or remove 25% of the snake's speed
- Oranges: remove the snake's tail for 5 seconds BUT the border triggers a gameover
- Pretzels: add or remove 4 tiles of length from the snake
- Pears: teleport the snake randomly (but at least one tile away from the border)
- Bread: removes all status effects (inverted controls, speed effects, tail-less effect)
- Cocktail: inverts the controls (up <-> down, left <-> right), every item eaten with inverted controls will have double the points
