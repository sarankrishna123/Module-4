# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
reg:212223070023
name:Saran krishna P S
class Saveetha:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

    def div(self):
        if self.b != 0:
            return self.a / self.b
        else:
            return "Error: Division by zero"

def main():
    calc = Saveetha()

    while True:
        print("\n1. Add")
        print("2. Divide")
        print("0. Exit")
        choice = int(input("Enter your choice: "))

        if choice == 1:
            a = float(input("Enter first number: "))
            b = float(input("Enter second number: "))
            calc.setvalues(a, b)
            print(f"Addition result: {calc.add()}")

        elif choice == 2:
            a = float(input("Enter first number: "))
            b = float(input("Enter second number: "))
            calc.setvalues(a, b)
            print(f"Division result: {calc.div()}")

        elif choice == 0:
            print("Exiting program.")
            break

        else:
            print("Invalid choice")

if __name__ == "__main__":
    main()



```

### OUTPUT
![image](https://github.com/user-attachments/assets/4c40f902-befa-4dd7-80aa-deb23c92c7a6)

### RESULT
thus the program is executed successfully.
