# Ex.No 12.e Stack Using Linked List – full or not

## Aim

To write a Python program tocheck and display whether the stack is full or not. 

## Algorithm

Start
    
Initialize a queue with a maximum size of 4.

Insert elements 'a', 'b', and 'c' into the queue.

Check if the queue is full and print the corresponding message. 

Stop

## Program

```

from queue import Queue
queue = Queue(maxsize = 4)

queue.put('a')
queue.put('b')
queue.put('c')
if (queue.full()):
    print("Stack is full")
else:
    print("Stack is not full")
```

## Output
![IMAGE](https://github.com/23013357/19CS301-Module12/blob/main/modul%2012.png)

## Result

Thus,Python program tocheck and display whether the stack is full or not was implementes and executed successfully.
