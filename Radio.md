[Back](README.md)
# Make a radio/pod player

## Rules

- When you don't know what to do or need help with something that is wrong with the code. Use Copilot Chat, It's not allowed to use resources on the internet other than accessing the api documentation.
- Use what you know but you can also pretend that you don't know and challenge what Copilot can do.

## Tips

- I you don't like what you get from Copilot you can change the promt to be more specific and regenerate.
- Think in "steps" get copilot to help out one step at a time.
- If you don't know what to do next or at all, start with asking in the Chat window.
- Be as specific as you can in the chat window, it will help Copilot to help you.

## Target (read this before you start)
Create an application that lists the active radio shows from Sveriges Radio using [`http://api.sr.se`](http://api.sr.se). When the user selects a show it lists the episodes of the show. The user should then be able to listen to an episode. The user should be able to play, pause, scribble and skip 30 sek forwand and back

Remember - try to read the API documentation as little as possible. Let CoPilot do the work for you!

If you want more of a challenge implement one or more of the following: 

Let the user sort the episodes by name or release date 

Let the user queue episodes to play. When one episode ends the next one from the queue should start automatically.

List the music played in the episode (if applicable)

## Detailed Instructions (only read this if you get stuck)
- Decide on a technique to use. You could build a web app or a desktop app. Maybe it could even be done in the console?
- If CoPilot can't help you with how to use the SR Api - try giving CoPilot the releveant parts of the discription from [`https://api.sr.se/api/documentation/v2/index.html`](https://api.sr.se/api/documentation/v2/index.html) and ask it how to create methods for getting the data.
- Some api methods (like sorting) is documented under [`https://api.sr.se/api/documentation/v2/generella_parametrar.html`](https://api.sr.se/api/documentation/v2/generella_parametrar.html)


## Excepted Result (check if the challenge is completed)
- An app that can list and play radio episodes