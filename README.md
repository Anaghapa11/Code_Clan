# Code_Clan
# Challenge 1 - Age Calculator
1. Get the user's birth year
2. Get the current date datetime.today()
3. Calculate the age
4. Display the result
 
# Challenge 2 - Magic Number Guessing game
1. The program picks a random number between 1 and 10
2. You have to guess it correctly
3. Compare the guessed number with the magic number
4. It gives hints if your guess is too high or too low
5. Repeat until the user guesses correctly
6. End the game when the correct number is guessed


# Challenge 3 - The Multiplication Table

# Steps done
1. The program prompts the user to enter a number using input(), then converts it to an integer using int().
2. A for loop runs from 1 to 10 to generate the multiplication table.
3. The loop multiplies the user-entered number by the current value of i (loop variable).
4. The results are printed in a structured format using an f-string (f"{num} * {i} = {num * i}").
5. The program starts by printing a title (Multiplication table of {num}:) for better readability.


# Challenge 4 - Emoji Mood checker

# Steps done
1. Asks how they’re feeling and converts it to lowercase.
2. Maps feelings to emoji responses.
3. Finds a response using .get().
4. Gives a generic reply if the feeling isn’t listed.
5. Displays an emoji-based message.


# Challenge 5 - The Simple Calculator

# Steps done
1. The program prints options for addition, subtraction, multiplication, and division.
2. Takes user input for operation – The user selects an operation by entering a number (1–4).
3. Takes two numbers in one line – map(float, input().split()) allows the user to input two numbers separated by a space.
4. Performs calculations – Uses if-elif conditions to perform the chosen operation.


# Challenge 6 - Temperature Converter

# Steps done
1. Asks for temperature and unit (C or F).
2. Converts input case – Uses .upper() to handle lowercase input.
3. Performs conversion using formulas:
   Celsius to Fahrenheit: (temp * 9/5) + 32
   Fahrenheit to Celsius: (temp - 32) * 5/9
4. Display the converted temperature.
