# Student Marks Program

print("Student Marks Calculator")

# input student name
name = input("Enter student name: ")

# input marks
math = int(input("Enter Maths marks: "))
science = int(input("Enter Science marks: "))
english = int(input("Enter English marks: "))

# calculate total and average
total = math + science + english
average = total / 3

# display result
print("\nStudent Name:", name)
print("Total Marks:", total)
print("Average Marks:", average)

# grade calculation
if average >= 90:
    print("Grade: A")
elif average >= 75:
    print("Grade: B")
elif average >= 50:
    print("Grade: C")
else:
    print("Grade: Fail")