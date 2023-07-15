# Basic Datatypes and Data Structures in Java

## Introduction
Programming in Java requires a solid understanding of basic data types and data structures. This technical communication aims to provide a comprehensive overview of these fundamental concepts and code samples in Java to help developers grasp their usage effectively.

## Basic Datatypes
Basic datatypes in Java are fundamental building blocks used to store and manipulate different types of data Let's explore them briefly:

1. **Boolean**: Represents a boolean value (true or false).
   
   ```java
   boolean flag = true;
   ```

2. **Byte**: Represents an 8-bit signed integer.
   
   ```java
   byte value = 10;
   ```

3. **Char**: Represents a single character.
   
   ```java
   char ch = 'A';
   ```

4. **Short**: Represents a 16-bit signed integer.
   
   ```java
   short number = 1000;
   ```

5. **Int**: Represents a 32-bit signed integer.
   
   ```java
   int count = 10000;
   ```

6. **Long**: Represents a 64-bit signed integer.
   
   ```java
   long population = 1234567890L;
   ```

7. **Float**: Represents a 32-bit floating-point number.
   
   ```java
   float pi = 3.14f;
   ```

8. **Double**: Represents a 64-bit floating-point number.
   
   ```java
   double value = 3.14159;
   ```

## Data Structures
Data structures help organize and manage data efficiently. A data structure in programming refers to a way of collecting and storing data in a computer's memory. 
It provides methods for accessing, manipulating, and managing the data effectively. Let's discuss some commonly used data structures in Java:

1. **Arrays**: A fixed-size collection of elements of the same data type.
   
   ```java
   int[] numbers = {1, 2, 3, 4, 5};
   ```

2. **ArrayList**: A dynamic array that can grow or shrink in size.
   
   ```java
   import java.util.ArrayList;
   
   ArrayList<String> names = new ArrayList<>();
   names.add("Alice");
   names.add("Bob");
   names.add("Charlie");
   ```

3. **LinkedList**: A data structure that consists of a sequence of elements, each pointing to the next element.
   
   ```java
   import java.util.LinkedList;
   
   LinkedList<Integer> numbers = new LinkedList<>();
   numbers.add(10);
   numbers.add(20);
   numbers.add(30);
   ```

4. **Queue**: A collection that follows the FIFO (First-In-First-Out) principle.
   
   ```java
   import java.util.LinkedList;
   import java.util.Queue;
   
   Queue<String> queue = new LinkedList<>();
   queue.add("Alice");
   queue.add("Bob");
   queue.add("Charlie");
   ```

5. **Stack**: A collection that follows the LIFO (Last-In-First-Out) principle.
   
   ```java
   import java.util.Stack;
   
   Stack<String> stack = new Stack<>();
   stack.push("Alice");
   stack.push("Bob");
   stack.push("Charlie");
   ```

6. **Tree**: A hierarchical data structure with a root and branches.
   
   ```java
   class TreeNode {
       int val;
       TreeNode left;
       TreeNode right;
   
       TreeNode(int val) {
           this.val = val;
       }
   }
   
   TreeNode root = new TreeNode(1);
   root.left = new TreeNode(2);
   root.right = new TreeNode(3);
   ```

7. **Graph**: A collection of nodes connected by edges.
   
   ```java
   import java.util.ArrayList;
   import java.util.List;
   
   class GraphNode {
       int val;
       List<GraphNode> neighbors;
   
       GraphNode(int val) {
           this.val = val;
           neighbors = new ArrayList<>();
       }
   }
   
   GraphNode node1 = new GraphNode(1);
   GraphNode node2 = new GraphNode(2);
   node1.neighbors.add(node2);
   node2.neighbors.add(node1);
   ```

These examples provide a glimpse of basic datatypes and commonly used data structures in Java. By mastering these concepts, developers can effectively manage and manipulate data in their Java programs.

## Conclusion
Understanding basic data types and data structures is essential for efficient programming in Java. This technical communication has introduced primitive datatypes and popular data structures such as arrays, ArrayLists, LinkedLists, queues, stacks, trees, and graphs. The provided code samples offer practical illustrations of their usage. By applying these concepts, developers can create well-organized and optimized Java programs.
## Reference 
* Tutorials provided by java w3schools : [java w3schools](https://www.w3schools.com/java/)
* Visit their website at geeksforgeeks : [geeksforgeeks](https://www.geeksforgeeks.org/java/) for more information.

