[Back](README.md)
# Make a Pong game

## Rules

- When you don't know what to do or need help with something that is wrong with the code. Use Copilot Chat, It's not allowed to use resources on the internet.
- Use what you know but you can also pretend that you don't know and challenge what Copilot can do.

## Tips

- I you don't like what you get from Copilot you can change the promt to be more specific and regenerate.
- Think in "steps" get copilot to help out one step at a time.
- If you don't know what to do next or at all, start with asking in the Chat window.
- Be as specific as you can in the chat window, it will help Copilot to help you.

## Target (read this before you start)
Create a pong game (https://en.wikipedia.org/wiki/Pong). The game should be playable with 2 players using the same keyboard. It should keep track of both players score. When the game starts after one of the players score the ball should start from the middle again and its starting direction should be randomized. The game should end when one player reaches 10 points. The game should then display a message in red saying what player won the game. It should then be possible to start the game again with the score reset. 

If you want more of a challange you can implemet one or more of the following: 

In original Pong the ball trajecotry was different depending on what part of the paddle the ball hit. If it hit the top part of the paddle the ball would go more up. If the ball hit the center of the paddle it would go straight and if it hit the lower part it would go more down.

Let the users enter their names before the game starts and add a high score list. 

Maybe the players should be able to change the game speed, the paddle color or other settings.  

You could also try to implement a one player mode where you play against the computer. 

## Detailed Instructions (only read this if you get stuck)
- The basic game should be pretty straight forward for CoPilot to implement by giving the first paragraph of the instrucions as a prompt.
- I tried this using Python with the Pygame library but it could be build using js with HTML5 Canvas API, Java with the Swing library or something else.
- When you have a basic game working - try writing prompts to improve the game.

## Excepted Result (check if the challenge is completed)
- A playable game for two players that keeps track of the score and restarts when one player reaches 10 points. 
- Depending on what other parts you chose to implement the game could have more or less functionallity

