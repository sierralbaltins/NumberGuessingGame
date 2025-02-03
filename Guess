import random
actualNumber = random.randint(1, 10)

print("Welcome to the Number Guessing Game!")
print(" ")
print("Enter a number from 1 to 10 to see if you guessed the correct number!")

try:
    guessedNumber = int(input("Enter your guess:"))

    if guessedNumber == actualNumber:
        print("You guessed", guessedNumber, ", the machine guessed ", actualNumber, ".")
        print("Congratulations! You won!")
    elif guessedNumber < 1 or guessedNumber > 10:
        print("The number you guessed is out of range!")
        print("Please choose a number between 1 and 10.")
    else:
        print("You guessed ", guessedNumber, ", the machine guessed", actualNumber, ".")
        print("You guessed incorrectly, please try again!")
except ValueError:
    print("Invalid input! Only integers from 1 to 10 are accepted.")

