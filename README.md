# Assignment_2_C_Text_Based_Adventure
Homework 2 : Text-Based Adventure Game in C++

# Overview
In this assignment, you will build a simple text-based adventure game using C++.
The goal is to practice core programming concepts such as:
variables
conditionals
loops
functions
strings
user input/output
Your game will run entirely in the terminal and allow a player to explore a small world, make decisions, and either win or lose.

⚠️ This assignment is intentionally procedural. Later in the course, you will rebuild this game using object-oriented programming (OOP).

# Learning Objectives
By completing this assignment, you will be able to:
Write an interactive C++ program
Use loops and conditionals to control logic
Track game state using variables
Organize code using functions
Handle user input safely
Design a simple game flow

# Game Scenario
You are trapped in a mysterious dungeon with multiple rooms. Your goal is to:
> Find the treasure and escape without losing
> You will navigate by typing commands and making decisions.


1. Basic Game Structure
Your program must:
> Display a welcome message
> Explain how to play
> Continuously prompt the user for input
> End when the player wins or loses

2. Rooms / Locations
Your game must include at least 3 rooms.
Each room should have:
a name
a description
at least one exit

Example:
Cell → Hallway → Treasure Room
              ↘ Trap Room

3. Player Actions
You must support at least 3 types of actions:
Action Type	     Example
Movement	       go north
Inspection	     look
Interaction	     take key
You may design your own command system as long as it is clearly explained.

4. Game State
Your program must track at least 2 pieces of game state, such as:
> current room
> inventory (e.g., key)
> door locked/unlocked
> player alive/dead

5. Win and Lose Conditions
Your game must include:
One winning condition
One losing condition

Examples:
Win: find treasure and escape
Lose: enter trap room

6. Functions
You must use at least 3 user-defined functions (besides main()).
Examples:
void showInstructions();
void describeRoom();
void processCommand(string command);


# Input / Output
Example Input
Enter command:
Example Output
You are in the Hallway.
There is a key here.
Exits: west, north, east
Enter command:

# Error Handling
Your program must handle invalid input gracefully.
Example:
Invalid command. Try again.

# Deliverables
Submit the following files:
main.cpp
README.md
Your README.md must include:
your name
game title
description of your game
how to compile
how to run
list of valid commands

# Compile & Run
Example using g++:
g++ main.cpp -o game
./game

# Grading Rubric
Category	Points
Correctness	40
C++ Fundamentals	25
Code Organization	20
Input Handling	10
README & Style	5
Total	100

# Minimum Checklist
Make sure your game includes:
 welcome message
 instructions
 3+ rooms
 3+ actions
 game state tracking
 win condition
 lose condition
 3+ functions
 input validation
 README

# Hints
Start small and build up
Get movement working first
Use a loop to keep the game running
Store the current room in a variable
Test often
