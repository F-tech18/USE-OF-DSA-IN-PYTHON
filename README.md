# USE-OF-DSA-IN-PYTHON


## 📌 Project Overview

This assignment focuses on Python data structures, particularly dictionaries and lists. It demonstrates how to store and retrieve student marks using a dictionary and how to extract and reverse elements from a list using list slicing.

## 🎯 Objectives

- Understand dictionaries and key-value pairs in Python.
- Store student names and marks in a dictionary.
- Retrieve student marks based on user input.
- Handle cases where a student is not found.
- Learn list slicing to extract specific elements.
- Reverse a list using Python slicing techniques.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Concepts:** Dictionaries, Lists, List Slicing, String Handling, Conditional Statements, User Input
- **Editor:** VS Code / IDLE / Jupyter Notebook

## 📂 Project Structure

```text
Assignment_5_Data_Structures/
│
├── task1_student_marks.py
├── task2_list_slicing.py
└── README.md
```

**File descriptions:**

- `task1_student_marks.py` – Creates a dictionary of student marks and retrieves marks based on the student's name.
- `task2_list_slicing.py` – Creates a list of numbers, extracts the first five elements, and reverses the extracted list.
- `README.md` – Provides project documentation, instructions, and sample outputs.

## 📝 Task 1: Create a Dictionary of Student Marks

### Problem Statement

Write a Python program that creates a dictionary containing student names and their marks, asks the user to enter a student's name, and displays the corresponding marks. If the student is not found, the program displays an appropriate message.

### Concepts Practiced

- Dictionary creation
- Key-value pairs
- User input using `input()`
- Dictionary lookup
- Conditional statements (`if-else`)
- Handling missing dictionary keys

### Sample Output

**When the student exists:**

```text
Enter the student's name: Alice
Alice's marks: 85
```

**When the student does not exist:**

```text
Enter the student's name: John
Student not found in the dictionary.
```

*Note: The output depends on the student names and marks defined in the program.*

## 📝 Task 2: Demonstrate List Slicing

### Problem Statement

Write a Python program that creates a list of numbers from 1 to 10, extracts the first five elements, reverses those elements, and displays both lists.

### Concepts Practiced

- List creation
- List slicing using `[:5]`
- Reversing a list using `[::-1]`
- List indexing
- Printing list values

### Sample Output

```text
Original list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

First five elements: [1, 2, 3, 4, 5]

Reversed list: [5, 4, 3, 2, 1]
```

## ▶️ How to Run the Project

### Step 1: Install Python

Download and install Python from [python.org](https://www.python.org/downloads/) if it is not already installed.

### Step 2: Open the Project Folder

Open the folder in Visual Studio Code or another Python-compatible editor.

### Step 3: Run Task 1

Open a terminal in the project folder and execute:

```bash
python task1_student_marks.py
```

Enter a student's name when prompted to retrieve their marks.

### Step 4: Run Task 2

Execute the following command:

```bash
python task2_list_slicing.py
```

The program will display the original list, the first five elements, and the reversed list.

## ✅ Expected Learning Outcomes

After completing this assignment, I gained practical experience in:

- Using Python dictionaries to organize and retrieve information.
- Understanding keys and values in a dictionary.
- Performing conditional checks when searching for data.
- Extracting list elements using slicing.
- Reversing lists using Python's slicing syntax.
- Writing simple, readable Python programs.

## 📌 Conclusion

This assignment strengthened my understanding of Python's built-in data structures. By implementing dictionary-based student mark retrieval and list slicing, I practiced organizing data, searching for values, and manipulating sequences efficiently.

**Module:** 6 – Data Structures and Strings in Python  
**Assignment:** 5  
**Status:** Completed
