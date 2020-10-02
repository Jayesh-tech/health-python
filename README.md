# health-python
import datetime
#================== Health management system ===================#

name = ["jayesh", "harry", "rohan"]
n = input("Enter your name>")
n_r_l = int(input('what you wanted to do 1--log and 2--retrive>'))
#============== Harry file code =================#
if n == "harry" and n_r_l == 1 :
    n1 = int(input("What you wanted to log 1--food and 2--Exercise>"))
    if n1 == 1:
        food = input("What you eat today>")
        userfileF = open("harry_food.txt","w")
        userfileF.write(food)
        userfileF.close()
    elif n1 == 2:
        exercise = input("What exercise you do today>")
        userfileE = open("harry_exercise.txt","w")
        userfileE.write(exercise)
        userfileE.close()
    else:
        print("Worng input!")
    
elif n == "harry" and n_r_l == 2:
    n2 = int(input("What you wanted to retrive 1--food and 2--Exercise>"))
    if n2 == 1:
        userfileF = open("harry_food.txt")
        content = userfileF.read()
        print(content)
        userfileF.close()
    elif n2 == 2:
        userfileE = open("harry_exercise.txt")
        content1 = userfileF.read()
        print(content1)
        userfileE.close()
    else:
        print("Wrong input!")

#==================== Jayesh file code ==================#
if n == "jayesh" and n_r_l == 1 :
    n1 = int(input("What you wanted to log 1--food and 2--Exercise>"))
    if n1 == 1:
        food = input("What you eat today>")
        userfileF = open("jayesh_food.txt","w")
        userfileF.write(food)
        userfileF.close()
    elif n1 == 2:
        exercise = input("What exercise you do today>")
        userfileE = open("jayesh_exercise.txt","w")
        userfileE.write(exercise)
        userfileE.close()
    else:
        print("Worng input!")
    
elif n == "jayesh" and n_r_l == 2:
    n2 = int(input("What you wanted to retrive 1--food and 2--Exercise>"))
    if n2 == 1:
        userfileF = open("jayesh_food.txt")
        content = userfileF.read()
        print(content)
        userfileF.close()
    elif n2 == 2:
        userfileE = open("jayesh_exercise.txt")
        content1 = userfileF.read()
        print(content1)
        userfileE.close()
    else:
        print("Wrong input!")

#============== rohan file code ====================#
if n == "rohan" and n_r_l == 1 :
    n1 = int(input("What you wanted to log 1--food and 2--Exercise>"))
    if n1 == 1:
        food = input("What you eat today>")
        userfileF = open("rohan_food.txt","w")
        userfileF.write(food)
        userfileF.close()
    elif n1 == 2:
        exercise = input("What exercise you do today>")
        userfileE = open("rohan_exercise.txt","w")
        userfileE.write(exercise)
        userfileE.close()
    else:
        print("Worng input!")
    
elif n == "rohan" and n_r_l == 2:
    n2 = int(input("What you wanted to retrive 1--food and 2--Exercise>"))
    if n2 == 1:
        userfileF = open("rohan_food.txt")
        content = userfileF.read()
        print(content)
        userfileF.close()
    elif n2 == 2:
        userfileE = open("rohan_exercise.txt")
        content1 = userfileF.read()
        print(content1)
        userfileE.close()
    else:
        print("Wrong input!")
