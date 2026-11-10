MINI PROJECT: Number Guessing Game

Project Overview: This is a mini game that accepts a guessed number and check a guessed number match with generated number or not,
for understanding the python programming language using different concepts includes -
(functions, conditional statements, error handling, loops, variables, pre-defined functions).

Technologies Used:
Python Programming Language
Jupyter Notebook

Purpose: Implement a basic version of guess number puzzle

Difference between Pre-existing code vs My code?

The existing code suffers from missing input validation, infinite attempts, and sudden crashes:
it directly converts input using int(input(...)), causing a ValueError crash if a user enters letters or symbols,
accepts invalid out-of-range numbers (<1 or >100) without warning,
and runs in an infinite while True loop without any attempt limit or game-over state.

My notebook code resolves these errors by wrapping user input in a try-except ValueError block to prevent crashes,
adding range checks (< 1 or > 100) to reject invalid entries without adding attempts of the user,
and setting max_attempts = 10 (it can be differ by programmer),
so that attempts only increment on valid guesses and the game ends with a proper "Game Over" message if the limit is reached.

Verification: I attached both the files you can compare by own.

How to Run My code:
Download code file
paste or attached in Jupyter notebook
Run code

Author: Farhan Ahmad

*During making this game, I understand the basic concepts that mentioned above.
I use this program in my class to represent not just a code but a little activity
where a group of students guess a number and if they guess correctly they won and take price.
but the maximum limit of attempts are three. 
Why I reduce the limit? because a game have secret number between 1 to 100 and a group can be guess easily
so if you want to do these type of activity in you educational platform/area you can increase the number that helps you in program modifications.
Let me know if you use or do this activity.*
