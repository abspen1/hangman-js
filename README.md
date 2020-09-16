# Hangman Game
This is a simple hangman game that I built with HTML and styled with CSS. The backend is all JavaScript. This was really fun to make and I'm happy with how it turned out.. Although, I'm not that great with design! 😅

## Game Functions
I'd like to think that I thought about everything when building this application. You are able to guess until the stick figure is completely drawn out. Once this happens the figure will go red and you will get a display saying you lost! You can refresh by clicking new game in the top left at any point. When you get a letter right it is displayed instead of the '_'. Once you get the full word a display will show that you have won and you need to hit 'New Game' for a new game. The alphabet at the bottom will also dissappear after winning/losing but you can still click them.. If you do click them the display changes to tell you to click 'New Game'. There's other functions too but you'll just have to try it out yourself. 😃


# Screenshots

![Alt text](/images/starting-screen.jpg?raw=true "Starting Screen")

![Alt text](/images/winning-screen.jpg?raw=true "Winning Screen")

![Alt text](/images/losing-screen.jpg?raw=true "Losing Screen")


## Possible Improvements
**JavaScript**
# Fixed this with browserify!
* Currently hardcoding the word bank..
     * I tried using the random-words module but it doesn't work in browser.
     * Could maybe look into a dictionary website that has API and would let me pull words
     * Also could create a text file of some kind with long list of words

**CSS**
* The design could use a little touch up
* I'm sure this code is messy since I'm not that comfortable with CSS
* I probably have some unnecessary code as well
