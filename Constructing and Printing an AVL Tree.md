# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[10, 5, 15, 7, 18, 9]
```

## OUTPUT
<img width="1417" height="165" alt="Screenshot 2025-11-09 213140" src="https://github.com/user-attachments/assets/b623640d-81c4-4e96-b7e4-cc3c61e5a81c" />

```

## RESULT
Thus the Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function is executed successfully.
