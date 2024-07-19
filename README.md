# Random_Fruit
Will print random fruit
fruits=["apple","banana","cherry"]
import random 
number=len(fruits) - 1
fruit_choice=random.randint(0,number)
# you can add any number to print the exact fruit if you want by providing the index value ranging in between  to 2 and it will print the name of it and if you remove the fruits then it will print the value or indexing of that particular fruit 
# like print(fruits[0])
print(fruits[fruit_choice])
