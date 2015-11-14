# Rock Paper Scissors Assignment

Please implement a simple rock, paper, scissors game in javascript. Player1 is the computer. Player2 is a human interacting with your program.

# Important

We are NOT looking to build a UI. Instead, we want to demonstrate an understanding of underlying programming concepts.

# Requirements

1. write a function, generateRandomNumber, that will generate a random number based on arguments startLim, endLim
2. write a function, getUserInput, that will ask user for input and return that value
3. write a function, computeWinner, that will take two arguments -- player1Choice and player2Choice -- and return 1 if player1 has won, 2 if player2 has won, or -1 if it is a tie

# Code starter 

(Note, the main.js code has this as well so you don't need to copy and paste)

## generateRandomNumber
```js

function generateRandomNumber( startLim, endLim ) {
	var randomNumber;

	// write your logic here that will generate a random number
	// and save it to the var called 'randomNumber'

	// NOTE: must be a _whole_ number

	return randomNumber;
}

```

## getUserInput
```js
function getUserInput() {
	var userPrompt;

	// use the window.prompt() method ( mdn is a good resource to find more info on it ) to solicit user input and save it to userPrompt

	return userPrompt;
}
```

## computeWinner
```js
function computeWinner( player1Choice, player2Choice ) {
	var winner;

	// write some if/else statement logic here to determine who has won this game
	// if player1 has won, return 1
	// if player2 has won, return 2
	// if it is a tie, return -1

	return winner;
}
```

# Questions to think about

No need to actually answer them in any formal way, just food for thought.

1. What is the purpose of the randomNumber generator? How can we use it to determine player1 (the computer)'s choice?
2. Is it necessary to return 1,2, and -1 from computerWinner? What other ways could we have done this?
3. How will we store player1Choice and player2Choice? Does this have any ramifications on how you write your computeWinner function?