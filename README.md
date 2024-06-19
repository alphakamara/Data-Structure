# Data-Structure
# Stack, Queue, and Sorting Operations

This C++ project provides basic implementations and operations for a Stack and a Queue data structure, along with a bubble sort function. The code includes a main menu to interactively perform these operations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Class Methods](#class-methods)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Overview

This project includes:

1. Stack operations: push, pop, isEmpty, isFull, count, peek, change, display.
2. Queue operations: enqueue, dequeue, isEmpty, isFull, count, display.
3. Bubble sort function for sorting an array of integers.
4. A main menu to interactively use the stack, queue, and sorting operations.

## Features

### Stack Operations

- **Push**: Add an element to the stack.
- **Pop**: Remove an element from the stack.
- **IsEmpty**: Check if the stack is empty.
- **IsFull**: Check if the stack is full.
- **Count**: Get the number of elements in the stack.
- **Peek**: Get the element at a specific position in the stack.
- **Change**: Change the element at a specific position in the stack.
- **Display**: Display all elements in the stack.

### Queue Operations

- **Enqueue**: Add an element to the queue.
- **Dequeue**: Remove an element from the queue.
- **IsEmpty**: Check if the queue is empty.
- **IsFull**: Check if the queue is full.
- **Count**: Get the number of elements in the queue.
- **Display**: Display all elements in the queue.

### Sorting

- **Bubble Sort**: Sort an array of integers using the bubble sort algorithm.

## Class Methods

### Stack Class

- `bool isEmpty()`
- `bool isFull()`
- `void push(int val)`
- `int pop()`
- `int count()`
- `int peek(int pos)`
- `void change(int pos, int val)`
- `void display()`

### Queue Class

- `bool isEmpty()`
- `bool isFull()`
- `void enqueue(int val)`
- `int dequeue()`
- `int count()`
- `void display()`

### Sorting Function

- `void bubbleSort(int a[], int size)`

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/alphakamara/Data-Structure.git
   ```
2. Navigate to the project directory:
   ```sh
   cd stack-queue-sorting
   ```
3. Compile the code using a C++ compiler:
   ```sh
   g++ -o main main.cpp
   ```

## Usage

1. Run the executable:
   ```sh
   ./main
   ```
2. Follow the on-screen instructions to perform stack, queue, and sorting operations.

### Main Menu

- **1. Stack Operations**
- **2. Queue Operations**
- **3. Sorting**
- **4. Exit**

### Stack Operations Menu

- **1. Push**
- **2. Pop**
- **3. Is Empty**
- **4. Is Full**
- **5. Count**
- **6. Peek**
- **7. Change**
- **8. Display**
- **9. Clear Screen**
- **10. Back to Main Menu**

### Queue Operations Menu

- **1. Enqueue**
- **2. Dequeue**
- **3. Is Empty**
- **4. Is Full**
- **5. Count**
- **6. Display**
- **7. Clear Screen**
- **8. Back to Main Menu**

### Sorting Menu

- **1. Start to Sort**
- **4. Back to Main Menu**

### Contributors
- **1. ALPHA KAMARA**
- **2. OLU KUNMI THOMAS**
- **3. SAFFIATU AMADU TUCKER**


## License

This project is licensed under the Limkokwing University License.

---

Feel free to contribute to the project by submitting issues or pull requests. Happy coding!
