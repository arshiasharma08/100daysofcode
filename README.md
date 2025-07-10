# 🐍 100 Days of Code: Python 🚀

Welcome to my journey through the **100 Days of Code - Python** challenge! This repository contains all the projects, scripts, and exercises I complete as part of the course.

## 📘 About the Challenge

The **100 Days of Code** challenge is a commitment to code for at least an hour every day for 100 days. I’m following a Python-focused curriculum to deepen my programming skills and build a strong foundation in Python.

## 🛠 What You’ll Find Here

This repo will be organized by day, with each folder representing a single day's challenge or project.

DAY 1 -
Band Name Generator Project
Create a greeting for your program.
Ask the user for the city that they grew up in and store it in a variable.
Ask the user for the name of a pet and store it in a variable.
Combine the name of their city and pet and show them their band name.

DAY 2 -
Tip Calculator Project
We're going to build a tip calculator.
If the bill was $150.00, split between 5 people, with 12% tip.
Each person should pay:
(150.00 / 5) * 1.12 = 33.6
After formatting the result to 2 decimal places = 33.60

DAY 3 -
Treasure Island Project
Your goal today is to build a "Chose your own adventure game". Using what you have learnt in the lessons today you will be building a very simple version of this type of text game.

DAY 4 -
Rock Paper Scissors Project
You are going to build a Rock, Paper, Scissors game. You will need to use what you have learnt about randomisation and Lists to achieve this.

DAY 5 -
Password Generator Project
The program will ask:
How many letters would you like in your password?
How many symbols would you like?
How many numbers would you like?
The objective is to take the inputs from the user to these questions and then generate a random password. Use your knowledge about Python lists and loops to complete the challenge.

DAY 7 - 
Hangman Game Project
TODO-1:
Update the word list to use the word_list from hangman_words.py
TODO-2:
Update the code to use the stages from the file hangman_art.py
TODO-3:
Import the logo from hangman_art.py and print it at the start of the game.
TODO-4:
If the user has entered a letter they've already guessed, print the letter and let them know.
We should not deduct a life for this.
e.g. You've already guessed a
TODO-5:
If the letter is not in the chosen_word, print out the letter and let them know it's not in the word.
e.g. You guessed d, that's not in the word. You lose a life.
TODO-6:
Update the code below to tell the user how many lives they have left. print("****************************<???>/6 LIVES LEFT****************************")
TODO 7:
Update the print statement to give the user the correct word they were trying to guess.
e.g. IT WAS <Correct Word>! YOU LOSE

DAY 8 -
Casear Cipher Project
TODO-1:
Import and print the logo from art.py when the program starts.
TODO-2:
What happens if the user enters a number/symbol/space that's not in the List alphabet?
Can you fix the code to keep the number/symbol/space when the text is encoded/decoded?
e.g.
original_text = "meet me at 3!"
cipher_text = "XXXX XX XX 3!"
 Hint 1 
If it's not a letter in the List alphabet, maybe you can just add it to the end of cipher_text as the unmodified character?
TODO-3:
Can you figure out a way to restart the cipher program?
e.g.
Type 'yes' if you want to go again. Otherwise, type 'no'.
If they type 'yes' then ask them for the direction/text/shift again and call the caesar() function again.

DAY 9 -
Blind auuction Project
The goal is to build a blind auction program.
Clearing the Output
There are several ways of clearing the output. The easiest is to simply print "\n" many times so that the output scrolls down many lines.
e.g.
# This will add 20 new lines to the output
print("\n" * 20)
Functionality
Each person writes their name and bid.
The program asks if there are others who need to bid. If so, then the computer clears the output (prints several blank lines) then loops back to asking name and bid.
Each person's name and bid are saved to a dictionary.
Once all participants have placed their bid, the program works out who has the highest bid and prints it.

DAY 10 - 
Calculator Project
Functionality
Program asks the user to type the first number.
Program asks the user to type a mathematical operator (a choice of "+", "-", "*" or "/")
Program asks the user to type the second number.
Program works out the result based on the chosen mathematical operator.
Program asks if the user wants to continue working with the previous result.
If yes, program loops to use the previous result as the first number and then repeats the calculation process.
If no, program asks the user for the fist number again and wipes all memory of previous calculations.
Add the logo from art.py

DAY 11 - 
Blackjack Project
Chose your difficulty
Normal 😎: Use all Hints below to complete the project.
Hard 🤔: Use only Hints 1, 2, 3 to complete the project.
Extra Hard 😭: Only use Hints 1 & 2 to complete the project.
Expert 🤯: Only use Hint 1 to complete the project.
Our Blackjack Game House Rules
The deck is unlimited in size.
There are no jokers.
The Jack/Queen/King all count as 10.
The Ace can count as 11 or 1.
Use the following list as the deck of cards:
cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]
The cards in the list have equal probability of being drawn.
Cards are not removed from the deck as they are drawn.
The computer is the dealer.
