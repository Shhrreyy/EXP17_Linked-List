# 🔗 EXP-17: Linked List in C++

## 🎯 Aim

To implement **Linked List operations** in C++ by:  
1. Creating a single node.  
2. Adding multiple nodes at the end of the list.  
3. Adding multiple nodes at the start of the list.  

---

## 📚 Theory

- **Linked List**  
  A Linked List is a **linear data structure** where elements (nodes) are connected using pointers instead of being stored in contiguous memory.  

- **Node Structure**  
  Each node typically contains:  
  - **Data** → Stores the value.  
  - **Pointer (next)** → Points to the next node in the list.  

- **Types of Linked Lists**  
  - **Singly Linked List** – Each node points to the next node.  
  - **Doubly Linked List** – Each node points to both next and previous nodes.  
  - **Circular Linked List** – Last node connects back to the first node.  

*(This experiment focuses on **Singly Linked List**.)*  

---

## 🧮 Algorithms / Steps

### a) **Create a Single Node**
1. Define a structure/class `Node` with `data` and `next` pointer.  
2. Create a node dynamically using `new`.  
3. Assign data and set `next = NULL`.  
4. Print the node data.  

### b) **Add Multiple Nodes at the End**
1. Start with a `head` node.  
2. Traverse to the last node using a loop.  
3. Create a new node and link it to the `next` of the last node.  
4. Repeat to insert multiple nodes.  
5. Print the list to verify insertion.  

### c) **Add Multiple Nodes at the Start**
1. Create a new node.  
2. Point its `next` to the current `head`.  
3. Update `head` to the new node.  
4. Repeat to insert multiple nodes.  
5. Print the list to check order.  

---

## ✅ Conclusion

- Linked Lists allow **dynamic memory allocation** and efficient insertion/deletion compared to arrays.  
- Nodes can be created and linked together using pointers.  
- Adding nodes at the start is faster (O(1)) than adding at the end (O(n)) in a singly linked list.  
- This experiment builds the foundation for advanced data structures like **stacks, queues, and graphs**.  

---

## 🧵 Topics Covered

- Concept of Linked List  
- Node Structure (Data + Pointer)  
- Creating a Single Node  
- Inserting Nodes at the End  
- Inserting Nodes at the Start  
- Traversing and Displaying a Linked List  
