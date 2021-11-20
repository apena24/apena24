'''
Adrian Pena
November 16, 2021
Test #2
'''
n = int(input("How many student data you want to store? "))

# Adds new student data

for i in range(0,n):
  name = input("Name: ")
  gender = input("Gender of " + name + ": ")
  height = int(input("Height in cm of " + name + ": "))
  weight = int(input("Weight in pounds of " + name + ": "))
  grade = int(input("Grade(9-12) of " + name + ": "))
  
  
  if grade == 9:
    print("Do you attend all of the classes shown? \n 1) Geometry \n 2) Biology \n 3) Spanish \n 4) World History \n 5) Theology \n 6) Health/Physical Education \n (yes or no):  ")
  
  elif grade == 10:
    print("Do you attend all of the classes shown? \n 12) Peer Ministry II \n 2) American Literature 3) \n 3) Chmistry \n 4) Algebra 2 and Trigonometry \n 5) Spanish \n 6) U.S. History \n 7)Elective \n (yes or no): ")
  
  elif grade == 11:
    print("Do you attend all of the classes shown? \n 1) Peer Ministry III \n 2) Pre-Calculus \n 3) British Literature \n 4) Physics 5) \n U.S. Government \n 6) Western Civilization and Art History \n 7) Elective \n (yes or no): ")

  elif grade == 12:
    print("Do you attend all of the classes shown? \n 1)  Peer Ministry IV \n 2) World Literature \n 3) Mathematics \n 4) Latin American History \n 5) Philosophy \n 6) Economics \n 7) 2 Electives \n (yes or no): ")
  
  all_grades = input("List grades for each of your classes(1-6): ")
  previous_gpa = input("Average GPA's from previous years: ")


#Search for student

search_student = input("Would you like to search for a student?(yes or no) ")

print(search_student)

if search_student == "yes":
  print("What grade is this student in? (9-12)")
else:
  print("ok")

