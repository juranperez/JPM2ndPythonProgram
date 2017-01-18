# JPM2ndPythonProgram
"""Pogram that grades a student score into a specific range """



score = int(input("Welcome to WestWorld please ENTER SCORE: "))

if score >100 or score <0:
    grade = "Invalid"

elif score >= 90:
    grade = 'A'

elif score >= 85: 
    grade = 'B+'

elif score >= 80: 
    grade = 'B'

elif score >= 75:
    grade = 'C+'

elif score >= 70: 
    grade = 'C'

else:
    grade = 'F'
print("Congrulations, Your final Grade is: ", grade)
