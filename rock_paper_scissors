rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
import random

rps = input("What do you choose? Type 0 for Rock, 1 for Paper or 2 for Scissors. ")

rps_input = int(rps)

computer_choose = random.randint(0,2)

if rps_input == 0:
  print(rock)
elif rps_input == 1:
  print(paper)
elif rps_input ==2:
  print(scissors)

print("Computer chose:\n")

if computer_choose == 0:
  print(rock)
elif computer_choose==1:
  print(paper)
elif computer_choose == 2: 
  print(scissors)

#tie
if rps_input == computer_choose:
  print("It's a tie")
# invalid number
elif rps_input >= 3 or rps_input < 0:
  print("You've typed an invalid number. You lose.")
# rps = rock, comp = paper
elif rps_input == 0 and computer_choose ==1:
  print("You lose")
#rps = paper, comp= scissors
elif rps_input == 1 and computer_choose ==2:
  print("You lose")
#rps = scissors, comp = rock
elif rps_input == 2 and computer_choose == 0:
  print("You lose")
else:
  print("You win")
