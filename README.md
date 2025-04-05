# Ice Cream Sundae Node Practice

This project is a practice exercise from Codecademy focused on understanding and implementing Nodes in JavaScript. The scenario involves an ice cream shop with a signature sundae made of three flavors: strawberry, vanilla, and coconut. New hires are having trouble remembering the correct order of these flavors in the sundae.

To help them, we've used JavaScript Nodes to represent each ice cream flavor and linked them together in the correct order.

## Project Description

This exercise demonstrates the basic principles of creating and linking nodes in JavaScript. We define a `Node` class (assumed to be provided by the Codecademy exercise) and then instantiate three nodes, each representing a different ice cream flavor. These nodes are then linked together to represent the correct order of the sundae. Finally, we traverse the linked nodes to print the flavor names in the intended sequence.

## Setup

This project is primarily based on JavaScript and does not require any specific setup beyond a JavaScript execution environment (like a web browser's console or Node.js).

1.  **Access the Codecademy Exercise:** This project is part of a Codecademy curriculum. Access the specific "Nodes in JS" exercise.
2.  **Follow the Instructions:** The exercise will guide you through the process of creating the `Node` class (if not already provided) and implementing the logic described below.

## Implementation Steps

1.  **Instantiate Ice Cream Nodes:**
    * Create a node representing strawberry ice cream with the name `'Berry Tasty'` and assign it to the variable `strawberryNode`.
    * Create a node representing vanilla ice cream with the value `'Vanilla'` and assign it to the variable `vanillaNode`.
    * Create a node representing coconut ice cream with the value `'Coconuts for Coconut'` and assign it to the variable `coconutNode`.

2.  **Link the Nodes:**
    * Use the `.setNextNode()` method (part of the `Node` class) to establish the correct order:
        * Set `strawberryNode` as the next node of `vanillaNode`.
        * Set `coconutNode` as the next node of `strawberryNode`.

3.  **Traverse and Log the Nodes:**
    * Create a new variable `currentNode` and initialize it with `vanillaNode`.
    * Implement a `while` loop that continues as long as `currentNode` is not `null`.
    * Inside the loop:
        * Log the data of the `currentNode` to the console.
        * Update `currentNode` to its next node using the `.getNextNode()` method (part of the `Node` class).

## Expected Output

Running the code should produce the following output in the console, demonstrating the correct order of the ice cream flavors:
