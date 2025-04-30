# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No:212223070023
Name:Saran Krishna P S
def get_grades():
    user_input = input("Enter grades separated by commas: ")
    grades_str = user_input.split(',')
    grades = []

    for g in grades_str:
        try:
            grade = int(g.strip())
            grades.append(grade)
        except ValueError:
            print(f"Invalid grade input: '{g.strip()}' is not an integer.")

    print("Valid grades:", grades)

get_grades()


```

### OUTPUT
![image](https://github.com/user-attachments/assets/b41a21b2-9e0f-4e3e-89b0-8667e14c98ce)

### RESULT
thus the above program is executed successfully
