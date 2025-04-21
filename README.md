# Expression Tree: Inorder and Postorder Traversal

## 📌 Aim
To write a Python program to build an **Expression Tree** using the `binarytree` module and display its **inorder** and **postorder** traversals.

---

## 🛠 Procedure
1. Import the required modules from `binarytree`.
2. Create a list of elements that represent the expression tree in level order format.
3. Use the `build()` method to construct the expression tree.
4. Use `.inorder` and `.postorder` properties to print the respective traversals.

---

## 💻 Program

```python
from binarytree import build, Node

x = ['*', 4, '-', 5, '+', 2, 7]
t = build(x)
print(t.inorder)
print(t.postorder)
```
---
## Output 

![image](https://github.com/user-attachments/assets/b67e666f-b8e8-4f66-b04e-e5cdf06de7cd)

---
## Result 

Thus, the program was successfully created and executed to perform inorder and postorder traversal of the expression tree.


