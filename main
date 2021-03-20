import random

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


user_input = int(input('What option do you chose? Type 1 for Rock, 2 for Paper or 3 for Scissors'))
random_choice = random.randint(1,3)
win_message = 'You win!'
tie_message = 'It`s a tie!'
lose_message = 'You lose!'

game_images = [rock, paper, scissors]
user_image = game_images[user_input-1]
computer_image = game_images[random_choice-1]
computer_option = 'Computer chose: '

print(user_image)

print(computer_option)

print(computer_image)

if user_input == 1:
  if random_choice == 1:
    print(tie_message)
  if random_choice == 2:
    print(lose_message)
  if random_choice == 3:
    print(win_message)

elif user_input == 2:
  if random_choice == 1:
    print(win_message)
  if random_choice == 2:
    print(tie_message)
  if random_choice == 3:
    print(lose_message)

elif user_input == 3:
  if random_choice == 1:
    print(lose_message)
  if random_choice == 2:
    print(win_message)
  if random_choice == 3:
    print(tie_message)

else:
  if user_input != range(1, 4):
    print('This is not a valid option. Try again')
