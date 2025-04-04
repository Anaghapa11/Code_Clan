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


# Challenge 7 - The Bank Account challenge

# Steps done
1. Creates a bank account.
2. Initializes account holder's name and balance.
3. Adds money if the amount is positive.
4. Deducts money if the amount is valid and sufficient.
5. Displays account holder's name and balance.


# Challenge 8 - Palindrome Checker

# Steps done
1. Keeps only letters and numbers, removes spaces & punctuation.
2. Converts everything to lowercase for case insensitivity.
3. Compares it with its reversed version to check if it's a palindrome.



# Challenge 9 - Rock-Paper-Scissors Game

# Steps done
1. Import random for computer choice.
2. Define choices "rock, paper, scissors".
3. Initialize scores: player score = 0, computer score = 0.
4. Start a while True for multiple rounds.
5. Take and validate player input.
6. Generate a random computer choice.
7. Compare choices to determine the winner.
8. Update and display the score.
9. Ask if the player wants to continue.
10. If "no", print the final score and exit.

   

# Challenge 10 - student Record Management

# Steps done
1. Check & Create File:If the file doesn’t exist, create a new one.
2. Add Student Details:Always add new student records to the file.
3. Read File: Display contents if the user wants.
4. Create Backup: Copy the file if the user chooses.
5. Delete Original : Delete only if a backup exists. 



# Challenge 11 - Longest Consecutive Sequence.

# Steps done
1. Store numbers in a Hash Set for O(1) lookup time.
2. Check each number to see if it’s the start of a sequence (num - 1 is missing).
3. Expand the sequence by checking if num + 1 exists, increasing current_streak.
4. Track the longest streak by updating longest_streak.
5.  Return the max streak after checking all numbers.














