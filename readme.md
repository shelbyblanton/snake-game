# Snake Game

## **[100 Days of Code: The Complete Python Pro Bootcamp for 2023](https://www.udemy.com/course/100-days-of-code/)**

By Dr. Angela Yu

*Day 20, 21 of 100:* GUI, Animation, Coordinates, Inheritance, List Slicing, Instances, State, High Order Functions

## Project Specs

Using **[Turtle](https://docs.python.org/3/library/turtle.html)** Screen capabilities, program the classic Snake game where a user guides a snake to food and each time the snake eats the food, it gets longer. 

The game ends if the snake collides with itself or a wall.

This application is written with Python 3.11.

![alt text](https://github-readme.s3.us-west-1.amazonaws.com/SnakeGame.png)

### Main Features
This game application features a constantly moving snake that follows a path and is guided to randomly placed food on the screen.

The current score and the high scoore is tracked at the top of the screen.  

## Usage & Requirements

This project uses three classes and one data file:
- Snake
- Food
- Scoreboard
- data.txt

### Workflow
The user guides the snake head by pressing the `up`, `down`, `left` and `right` arrow keys.

When the snake eats the food, it adds length to its tail and scores a point.

If the snake head collides with either a wall or its tail, the game resets.

Once a game ends, if the score is the highest score the user has achieved, it writes that score to a text file for use in future games.

# Getting Started

All of the commands below should be typed into the Python terminal of your IDE (I use PyCharm for my Python Development).

First, clone the repository from Github and switch to the new directory:

    $ git clone git@github.com:shelbyblanton/snake-game.git
    
Then open the project in PyCharm.

**Setup is complete!** 

Click Run in PyCharm to see the app in action.


# Author & Credits

Programmed by **[M. Shelby Blanton](https://www.linkedin.com/in/shelbyblanton/)** under the instructional guidance of **[Dr. Angela Yu](https://www.udemy.com/user/4b4368a3-b5c8-4529-aa65-2056ec31f37e/)** via **[Udemy.com](udemy.com)**.
