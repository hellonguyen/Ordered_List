# ORDERED_LIST IMPLEMENTATION PROJECT

## Why the project matters? 

The project will help us gain better understanding of Abstract Data Types, Temple, Arrays, and Linked Lists. There are two versions of the list, which have the same interface, but different implementations, one using an array and another using a linked list.

## Ordered List Interface
***Constructor:*** Your constructor should set the initial state of the object correctly setting defaults for all properties.

***Deconstructor:***  A deconstructor is required in the linked list version to ensure that memory leaks are not created when the ADT is deleted.

***int getLength():*** Returns the length of the list.

***void putItem(const DataType &item):*** Inserts the value of the item into the list. Throws a FullError if the list is full.

***bool getItem(const DataType &item, DataType &found_item):*** Finds the item in the list and assigns the value to the found_item. Returns true if the item is in the list and false if it is not

***bool isFull():*** Returns true if the list is full, false if it is not.

***void makeEmpty():*** Sets the list to empty.

***bool deleteItem(const int &item):*** Removes the item from the list.Returns true if the item was in the list and false if it was not.

***bool getNextItem(DataType &item):*** Progressively set item to values in the listReturns true if there was an item to return and false if there was not.

***void resetList():*** Resets the cursor for getNextItem to the beginning of the list.

**Linked list version:** having the same methods above and add two more:
* A copy Constructor
* An Assignment Operator
