# Exp No: 36  
## Circular Queue 
---

### AIM  
To write a Python program with a function to delete float values into a Circular Queue.

---

### ALGORITHM

1. Start  
2. Check if the Circular Queue is full  
   - If `size == max_size`, print `"Queue is full"` and exit the function  
3. If the queue is not full:  
   - Read the element to be deleted  
   - Convert it to float  
   - Delete the element at the `tail` position  
   - Update tail using: `tail = (tail + 1) % max_size` (circular increment)  
   - Increment `size` by 1  
4. End

---

### PROGRAM

```
class Queue():
    def __init__(self):
        self.size=int(input())
        self.queue=['' for i in range(self.size)]
        self.front=self.rear=-1
        
    def enq(self,ele):
        if self.front==-1:
            self.front=self.rear=0
            self.queue[self.rear]=ele
            
        elif ((self.rear+1)%self.size)==self.front:
            print("Queue is full")
            
        else:
            self.rear=self.rear+1%self.size
            self.queue[self.rear]=ele
    
    def deq(self):
        if self.front==-1:
            print("Queue is empty")
        
        elif self.front==self.rear:
            self.front=self.rear=-1
            self.queue.pop(self.front)
            
        else:
            self.queue.pop(self.front)
            self.rear=(self.rear+1)%self.size
            
obj=Queue()
obj.enq(float(input()))
obj.enq(float(input()))
obj.enq(float(input()))
print(obj.queue)
obj.deq()
print(obj.queue)
```

### OUTPUT
![Screenshot 2025-05-05 003638](https://github.com/user-attachments/assets/597e96cf-835e-41a7-8e82-e3f401796490)


### RESULT
Thus, the python program with a function to delete float values into a Circular Queue has been executed and verified successfully.
