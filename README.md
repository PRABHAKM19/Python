print("Welcome to my Quiz Game!")
playing=input("Do you want to play? ")

if playing.lower()!="yes":
    quit()

print("Okay! Let's Play :) ")
score=0
Answer=input("what is the CPU stands for? ")

if Answer.lower()=="central processing unit":
    print("Correct! Well Done :)")
    score+=1
else:
    print("Oops! Let's go Again")

Answer=input("what is GUI stands for? ")

if Answer.lower()=="graphical user interface":
    print("Correct! Well Done :)")
    score+=1

else:
    print("Oops! Let's go Again")

Answer=input("what is the RAM stands for? ")

if Answer.lower()=="random access memory":
    print("Correct! Well Done :)")
    score+=1

else:
    print("Oops! Let's go Again")


Answer=input("what is the ROM stands for? ")

if Answer.lower()=="read only memory":
    print("Correct! Well Done :)")
    score+=1

else:
    print("Oops! Let's go Again")


Answer=input("what is the other name for main memory? ")

if Answer.lower()=="primary memory":
    print("Correct! Well Done :)")
    score+=1

else:
    print("Oops! Let's go Again")

Answer=input("OS starts with letter 'i' is? ")

if Answer.lower()=="ios":
    print("Correct! Well Done :)")
    score+=1
else:
    print("Oops! Let's go Again")
Answer=input("What is 1+1 in binary operation? ")

if Answer.lower()=="10":
     print("Correct! Well Done :)")
     score+=1
else:
    print("Oops! Let's go Again")

print("You have got " + str(score) + " questions Correct!")
