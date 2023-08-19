# Reptile
A simple grade calculator in Python
      #      GRADE CALCULATOR
#Prompt the user to input the score they received on a test. Assume the score is out of 100 
#Convert the input string to an integer using the int() function

#Determine the corresponding grade based on the following grading scale:
'''A: 90-100
B: 80-89
C: 70-79
D: 60-69
F: 0-59'''
#Print the grade that corresponds to the entered score.
#The program should help the user quickly find out the grade they received based on their test score.
user_input = str(input('Enter your score'))
user_score = int(user_input)
if user_score > 100:
    print('Invalid input. Score should be between 0 and 100')
elif user_score >=90:
    print('Your grade is A')
elif user_score >=80:
    print('Your grade is B')
elif user_score >=70:
    print('Your grade is C')
elif user_score >=60:
    print('Your grade is D')
else:
    print('Your grade is F')
