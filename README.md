# D4-Fall21
Discussion #3-2 - Rolling a Dice 

A dice is an example of an object we can simulate with a Python class.  Actually, die is singular and dice is plural, but we will just call one die a dice in this assignment. Our Dice class will have a constructor (__init__ method) along with additional methods to track our rolls and get data on them. For this exercise, you will be making a Dice class with the following:
Constructor (__init__) method: the constructor will initialize a new dice object that has not yet been rolled.  When you create the Dice object you will set how many sides the dice has.  By default, it will have 6 sides. In the constructor, initialize instance variables for:
The number of sides  
A list keeping track of all of the values this dice has rolled
__str__ method: create a string method so that printing an instance of the dice class outputs the value of the last roll.  For example:



roll method: Rolls the dice to get a random integer between 1 and the number of sides (hint: use the random module). Save the value at the end of a list that tracks all the values rolled.  Returns the number rolled.


Example Output From Discussion3.py 
NOTE: Your output will not look exactly like this because we are using random.

Bonus quiz
Implement the following method: 
print_count_for_num method: Takes in a parameter num which specifies which roll value to look for.  Loop through the roll history list and count how many times that num was rolled.  Print the number of times that value was rolled:



