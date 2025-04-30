# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.No212223070023
#Name:Saran Krishna P S
import sys

my_dict = {'a': 1, 'b': 2, 'c': 3}
size = sys.getsizeof(my_dict)
print("Size of dictionary:", size, "bytes")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/1c5a424a-1710-4c66-9c31-43f0b2937706)


### RESULT
Thus the program is executed successfully.
