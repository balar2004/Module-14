# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```
import collections
  
n1=input()
n2=input()
n3=input()
# initializing deque
de = collections.deque([n1,n2,n3])
de.pop()

# printing modified deque
print ("The deque after deleting at right is : ")
print (de)
```

### OUTPUT
![Screenshot 2025-05-05 004049](https://github.com/user-attachments/assets/b1a3a1d0-2764-4c62-adc3-b6a56c8db572)


### RESULT
Thus, the python program to delete elements at FRONT END of deque using a collection built-in function has been executed and verified successfully.
