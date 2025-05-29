# Linked List Interactive Console Program in C

## Overview

This project demonstrates a fully functional singly linked list implementation in C. It allows users to interact with the list through a command-line interface, performing various operations like insertion, deletion, and node traversal.

## Features

- Create and manipulate singly linked lists
- Add and remove elements at the head
- Insert at arbitrary positions
- Retrieve and count elements
- Move nodes between two lists
- Dynamic memory allocation with error handling
- Robust input validation

## File Structure

- `main.c`: Handles user interaction and menu-based control flow
- `linkedlist.c`: Contains the implementation of core linked list functions
- `linkedlist.h`: Declares the `Node` struct and function prototypes

## Key Functions

- `Push`: Adds a node at the head of the list
- `Pop`: Removes the head node and returns its value
- `Count`: Counts occurrences of a specific value
- `GetNth`: Gets data at a specific index
- `InsertNth`: Inserts data at a specific index
- `DeleteList`: Frees all memory and deletes the list
- `MoveNode`: Transfers a node from one list to another
