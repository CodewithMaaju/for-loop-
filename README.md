# for-loop-
Use of for loop 
#today we have learnt about the loops
#two types of loops, for loop and while loop.
#for loop is used for iterable objects
#for example 
name = "Muaz"
for i in name:
  print(i)
  print(i, end=",")
  if i == "z":
    print("This is something special")
#here i is a variable which is used for storing the value of the string. 
#we can also use the for loop for list and range
colors = ["red", "blue", "green", "yellow"]
for color in colors:
  print(color)
  for i in color:
    print(i)

#Now move towards learning range
#range is used for printing the numbers in the range
for k in range (12):
  print (k-1)
  print (k+1)

# now explore the third parameter of range 
for k in range (1, 12, 3):
  print (k)
  print("Here is the end of for loop ")
