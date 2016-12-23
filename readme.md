#Week 13 Homework

Implement a doubly linked list

The **MyLinkedList** class used in Listing 24.6 is a one-way directional linked list that enables one-way traversal
of the list. Modify the **Node** class to add the new data field name **previous** to refer to the previous
node in the list, as follows:

Here is a sample run of the program:

	```bash
	**public class** Node<E> {
	  E element;
	  Node<E> next;
	  Node<E> previous;
	  
	  **public** Node(E e) {
	    element = e;
     }
	}
	```

##Tasks
Implement a new class named **TwoWayLinkedList** that uses a doubly linked list to store elements.
The **MyLinkedList** class in the text extends **MyAbstractList**. Define **TwoWayLinkedList** to extend
the **java.util.AbstractSequentialList** class. You need to implement all the methods defined in
**MyLinkedList** as well as the methods **listIterator()** and **listIterator(int index)**. 
Both return an instance of **java.util.ListIterator<E>**. The former sets the cursor to the head
of the list and the latter to the element at the specified index.

Turn in all files using git.
