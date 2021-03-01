![Snowman icon](/snowmanicon.png)


## Snowman [Command Line Javascript Application]

A guessing game that allows the user to guess a randomly selected word one letter at a time.

![Snowman Gif](./snowman.gif)

### Setup


1. Clone this repo to your machine `git@github.com:angelinaebreo/Snowman-CLI-Game.git`
1. Go into the cloned directory `$ cd Snowman-CLI-Game` and run `npm install`
1. Play and enjoy Snowman game! `$ node snowman.js`





### Dependecies
- readlineSync Used to communicate with the user via console
`const readline = require("readline-sync")`
```
readline.keyInYN("Would you like to play again? \n"
// User will enter Y or N to either replay or quit game
```
  
- chalk Used edit text color
`const chalk = require("chalk")`


