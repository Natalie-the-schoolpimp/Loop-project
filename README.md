# Loop-project
#This code has the ability to loop a function
for i in range(2,16,3):
  print(i)
  
 counter =2
 while counter <= 14:
  print(counter)
  counter += 3
  
  sum = 0 
value = int(input("Enter number up to 100: ")) 
for i in range(value+1):
  sum+=i
print(sum)

total_score = 0 
for i in range(3): 
  my_score = int(input("Enter number: " )) 
  total_score += my_score 
  print("The 3 game total is: ", total_score) 
