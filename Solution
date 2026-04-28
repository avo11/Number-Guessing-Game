import random


print ("Number Guessing Game")
print ("easy")
print ("medium")
print ("hard")

choice = input("Choose a difficulty: ")

if choice == "easy":
    guessAmount = 10
    
if choice == "medium":
    guessAmount = 5

if choice == "hard":
    guessAmount = 3
        
num = random.randint(1, 100)
    
while guessAmount > 0:
    guessNum = int(input("Guess a number: "))
    if guessNum > num:
        guessAmount -= 1
        print("Number is lower than", guessNum)
    elif guessNum < num:
        guessAmount -= 1
        print("Number is higher than", guessNum)
    else:
        print("Winner winner chicken dinner")
        break
    
if guessAmount == 0:
    print("Game over")
    

    
    
