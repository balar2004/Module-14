# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```
from collections import deque

li = [int(input()) for i in range(3)]
de = deque(li)

de.append(14)
de.append(15)
print("The deque after appending at right is :")
print(de)
```

### OUTPUT
![Screenshot 2025-05-05 003949](https://github.com/user-attachments/assets/009b5751-9da7-4204-83de-89847f910b61)

### RESULT
Thus, the python program to insert elements at REAR END of deque using a collection built-in function has been executed and verified successfully.
