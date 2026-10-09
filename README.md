# Rock-Paper-Scissor-
#In this code we play the common game  is rock paper, scissor by using conditional statement in python 

import random


choices = ("rock" , "paper" , "sessior")

user = input("Enter rock , paper , sessior : ")

computer = random.choice(choices)

print("Your choice", user)
print("Computer choice",computer)

if user == computer:
    print("Thats the tie ")

elif (user == "rock" and computer == "sessior") or \
     (user == "paper" and computer == "rock") or \
     (user == "sessior" and computer == "paper"):
    print("You win the game ")
else : 
    print("You loss the game")
