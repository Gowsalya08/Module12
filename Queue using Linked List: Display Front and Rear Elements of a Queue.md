# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
queue = []

queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

print('Initial Queue: ' + str(queue))

front = queue[0]

print("\nElement at the front of the queue is .... ", front)

rear = queue[3]

print("\nElement at the rear of the queue is .... ", rear)
## Output
<img width="1120" height="257" alt="image" src="https://github.com/user-attachments/assets/82f924f3-7821-437d-810a-413b09852b87" />

## Result
Thus, the program was executed successfully
