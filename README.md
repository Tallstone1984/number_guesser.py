# number_guesser.py
a number guessing game created with python.

# Number Guessing Game
Based on a tutorial.
This is a simple number guessing game implemented in Python. The game presents a series of multiple-choice questions related to computer hardware. The player's score is calculated based on the number of correct answers.

## Instructions

1. Run the Python script to start the game.
2. You will be asked if you want to play. Enter "yes" to start or any other input to quit the game.
3. If you choose to play, the game will begin by presenting a series of questions.
4. Answer each question by typing the correct option or phrase and pressing Enter.
5. After answering all the questions, your total score will be displayed along with the percentage of correct answers.

##CODE

print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()  
    
print("Okay! Let's play :)")
score = 0

answer = input("What does CPU stand for? ")
if answer.lower() == "central processing unit":
    print('Correct!')  
    score += 1 
else: 
    print("Incorrect!")
    
answer = input("What does GPU stand for? ")
if answer.lower() == "graphics processing unit":
    print('Correct!')
    score += 1   
else: 
    print("Incorrect!")
    
answer = input("What does RAM stand for? ")
if answer.lower() == "random access memory":
    print('Correct!')
    score += 1   
else: 
    print("Incorrect!")
    
answer = input("What does PSU stand for? ")
if answer.lower() == "power supply unit":
    print('Correct!') 
    score += 1  
else: 
    print("Incorrect!")
    
print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")


Feel free to use and modify this game according to your needs. Enjoy the game and have fun learning about computer hardware!
