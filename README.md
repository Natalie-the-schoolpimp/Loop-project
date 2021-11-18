# Loop-project
#This code has the ability to loop a function
for i in range(2,15,3):
  print(i)
  
 counter =2
 while counter <= 15:
  print(counter)
  counter += 3
  
  sum = 0 
value = int(input("Enter number up to 100: ")) 
for i in range(value+1):
  sum+=i
print(sum)

high_score = 0
total_score = 0 
for i in range(3): 
  my_score = int(input("Enter number: " ))
  if my_score >300 or my_score <0:
    print("Enter valid score")
    my_score = 0
  if my_score > high_score: 
    high_score = my_score
  total_score += my_score
print("The 3 game total is: ", total_score) 
print("Your high game is:", high_score)

import random
hp = 100
complete=false
while not complete:
  cont=input("PLay a round? (Y/N):")
  if cont=="Y":
    damage = random.randomint(0,100)
    hp-=damage
    if hp <=0:
      print("Game Over")
      complete=True
    else:
      print("You were damaged by,",damage, "Your hp is,",hp)
 elif cont=="n"
  complete=True
 else: 
  print("invalid input, please say y/n")
