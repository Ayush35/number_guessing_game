# number_guessing_game
#Its a game in which you asked the user to guess the winning no.
import random
num= random.randint(0,100)
print("******Guess the number and win**********")
for i in range(1,100):
    a = int(input("Enter your guess :   "))
    if a== num:
        print("YOU WIN!!!")
        print(f"You guessed the number in {i} times")
        break
    elif a<num:
        print("oh ho!! you guessed less")
    else:
        print("oh ho!! you guessed more")
