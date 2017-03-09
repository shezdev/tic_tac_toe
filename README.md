# Tic Tac Toe AKA Noughts and Crosses

This is a practice tech test, to develop the business logic of the game
"Tic Tac Toe", then implement this with a user interface (e.g. web or command line)

https://github.com/makersacademy/course/blob/master/individual_challenges/tic_tac_toe.md
http://web.cecs.pdx.edu/~bart/cs541-fall2001/homework/tictactoe-rules.html
## Getting started

`git clone path-to-your-repo`
`command_to_install_dependencies` (e.g. `bundle`)

## Usage
[(1) How to install it (what to clone, what to run to get all dependencies)]

`command_to_start` (e.g. `rackup` or `rails s`)
Navigate to `http://localhost:4567/`

[(2) How to run it (is it a command line tool? Do you have to load it into IRB? Is is a web application? What port needs to be used?)]

## Running tests

`test_command` (e.g. `rspec`)

Later on, you can add screenshots and additional information to your heart's content, but make sure you have this with all your repos as you proceed through the course. You will thank yourself later.
https://github.com/matiassingers/awesome-readme

![Image Title](image.png)

##The Brief
The rules of tic-tac-toe are as follows:

* There are two players in the game (X and O)
* Players take turns until the game is over
* A player can claim a field if it is not already taken
* A turn ends when a player claims a field
* A player wins if they claim all the fields in a row, column or diagonal
* A game is over if a player wins
* A game is over when all fields are taken


##User Stories
As a player
I want to play a game of tic Tac Toe with another player
So I can win or draw

As a player
I want to enter my name and be assigned a O or X
So I can start to play a game

As a player
I want to claim a field if it has not already been taken
So I can try to claim 3 fields in a row to win

As a player
I expect my turn to end
When I have claimed a field during a game

As a player
I expect to win
If I claim all fields in a row, column on diagonal

As a player,
I expect a game to be over
If myself or another player wins

As a player,
I expect a game to be over
If all fields are taken  

As a player,
I expect a game to be over (and called a "Cat game")
If myself or another player draws
