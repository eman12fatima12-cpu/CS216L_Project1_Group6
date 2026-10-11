## Project Description
A menu-driven Java console application designed to manage student records efficiently. It uses a custom Singly Linked List to perform CRUD (Create, Read, Update, Delete) operations, search, and sort, along with a custom Stack to support undo capability for record operations.

## Data Structures Used
- **Custom Linked List (`StudentLinkedList`)**: Stores and manages all student records dynamically.
- **Custom Stack (`ActionStack`)**: Tracks user actions to support multi-level Undo functionality.

## Features
1. **Add Student**: Add a new student record to the list.
2. **Delete Student**: Remove a student record by ID.
3. **Update Student**: Update details of an existing student.
4. **Search Options**: Search by Student ID or Name.
5. **Sort Records**: Sort students by GPA.
6. **Display Records**: Print all currently stored student records.
7. **Undo Last Action**: Revert the last operation (Add/Delete/Update).
8. **View Action History**: Display the current stack of performed actions.

## Time Complexity Table

| Operation / Feature | Best Case | Average Case | Worst Case | Space Complexity |
| :--- | :--- | :--- | :--- | :--- |
| **Add Student** | O(1) | O(1) | O(1) | O(1) |
| **Delete Student** | O(1) | O(n) | O(n) | O(1) |
| **Update Student** | O(1) | O(n) | O(n) | O(1) |
| **Search (by ID / Name)** | O(1) | O(n) | O(n) | O(1) |
| **Sort by GPA** | O(n) | O(n²) | O(n²) | O(1) |
| **Display All** | O(n) | O(n) | O(n) | O(1) |
| **Undo Action** | O(1) | O(1) | O(1) | O(1) |

---

## Program Screenshots
![Main Menu & Operations](./Screenshot%202026-10-11%20205403.png)
![Search & Sort Features](./Screenshot%202026-10-11%20205437.png)
![Undo Action Feature](./Screenshot%202026-10-11%20205522.png)
---

## GitHub Repository
**Repository Link:** `https://github.com/eman12fatima12-cpu/CS216L_Project1_Group6`
