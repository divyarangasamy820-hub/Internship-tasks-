import random
print("Welcome to the Number Guessing Game! ")
secret_number = random.randint(1, 10)
while True:
    guess = int(input("Enter your guess (1 to 10): "))
    if guess < secret_number:
        print("Too low! Try again.")
    elif guess > secret_number:
        print("Too high! Try again.")
    else:
        print(" Correct! You win! ")
        break
