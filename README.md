


## Snowman [Command Line Javascript Application]

A guessing game that allows the user to guess a randomly selected word one letter at a time.

![Snowman Gif](./snowman.gif)

## Setup


1. Clone this repo to your machine > git@github.com:angelinaebreo/Snowman-CLI-Game.git
1. `cd` to the cloned directory and run `npm install`
1. Create a `.gitignore` file
1. Inside .gitignore, write `node_modules`
1. Write your code in `snowman.js`





### As a user, I should be presented with a random word to guess

- The computer should pick a word at random
- The user should see a number of `_` characters equal to the number of letters in the word (ex. A _ _ L E, for apple)

### As a user, I should be able to enter guesses

- Handle invalid guesses by displaying a message and having the user enter a different guess.  Invalid guesses don't count against the guess count.
- After each guess, the user should see the new updated word, replacing all `_` with letters they have guessed
- After each guess, the user should see the letters they have guessed already

### As a user, I should know how many guesses I have left

- At the beginning of the game, the number of guesses remaining should be visible
- After each guess, the updated number of guesses should be visible

### As a user, I should know when I win or lose and see the correct answer.

- The game should continue until the user has won or lost
- Once the full word is guessed, the game should display how many guesses it took and display a victory message
- If the user runs out of guesses, the full word should be revealed and the game should display a defeat message

## Rubric

![acceptanceCriteriaRubric](./acceptanceCriteriaRubric.png)
![outcomesRubric](./outcomesRubric.png)
