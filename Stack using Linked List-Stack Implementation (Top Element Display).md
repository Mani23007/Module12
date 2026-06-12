# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program:
```python
stack = []

for i in range(3):
    value = input("Enter value: ")
    stack.append(value)

print("Top element:", stack[-1])
```

## Output:
<img width="470" height="198" alt="image" src="https://github.com/user-attachments/assets/1e953d61-2b19-4272-99d4-b0be1bc25069" />


## Result:
Thus,the program is executed successfully.
