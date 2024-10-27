# Queue Implementation in C++

This is a simple implementation of a queue using a linked list in C++. The queue supports basic operations such as enqueue, dequeue, peek, and checking if it is empty.

## Features

- **Enqueue**: Add an element to the rear of the queue.
- **Dequeue**: Remove an element from the front of the queue.
- **Peek**: View the front element without removing it.
- **IsEmpty**: Check if the queue is empty.
- **Print**: Display all elements in the queue.

## Classes

### Node

The `Node` class represents an element in the queue. It contains:
- `data`: The value stored in the node.
- `next`: A pointer to the next node in the queue.

### Queue

The `Queue` class manages the queue operations:
- `enqueue()`: Adds a new node to the queue.
- `dequeue()`: Removes the front node from the queue.
- `peek()`: Displays the front node's data.
- `print()`: Outputs all elements in the queue.
- `isempty()`: Checks if the queue is empty.
