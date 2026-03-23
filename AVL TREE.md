# Experiment 10b: AVL Tree

## Aim
To write a Python program to construct an AVL tree and print the nodes of it using the appropriate packages and built-in functions.

---

## Algorithm

1. Start the program.
2. Define a function `getDictTree(tree)` to return the dictionary representation of an AVL tree.
3. Define a function `Construct_AVL(L)` to:
   - Create an AVL tree from the list `L`.
   - Get and print the dictionary tree using `getDictTree(tree)`.
4. Define a list `L` with integer values.
5. Call `Construct_AVL(L)` to build the tree and print the result.
6. End the program.

---

## Program

```

from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))


```

## OUTPUT
<img width="1200" height="197" alt="image" src="https://github.com/user-attachments/assets/44684e91-b5c3-4e58-9bc8-75bc93eef355" />

## RESULT
The Python program to construct an AVL tree using appropriate packages was successfully executed, and the nodes were displayed in dictionary form, verifying the correct structure and balance of the AVL Tree.
