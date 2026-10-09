# Rock-Paper-Scissor-
#In this code we play the common game  is rock paper, scissor by using conditional statement in python 

import random


choices = ("rock" , "paper" , "scissor")

user = input("Enter rock , paper , scissor : ")

computer = random.choice(choices)

print("Your choice", user)
print("Computer choice",computer)

if user == computer:
    print("Thats the tie ")

elif (user == "rock" and computer == "scissor") or \
     (user == "paper" and computer == "rock") or \
     (user == "scissor" and computer == "paper"):
    print("You win the game ")
else : 
    print("You loss the game")
