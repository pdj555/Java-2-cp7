# Class Notes Week 9

## Linked List vs ArrayList
https://stackabuse.com/difference-between-arraylist-and-linkedlist-in-java-code-and-performance/

<img width="484" alt="image" src="https://user-images.githubusercontent.com/102199778/197311569-ddb9e0af-11d5-415e-842c-988401677f4e.png">

## Time Complexities
https://www.bigocheatsheet.com/

## Data Structures vs Abstract Data Types
- Data Structure
    - specific way of organizing data and operations to access/use the data
    - ex: arrays, ArrayList
- Abstract data type
    - an implementation independent group of data and set of operations on this data
    - a programming language is used to implement
    
## Array and ArrayList differences
- Array
    - static in size
- ArrayList
    - dynamic in size
    - cannot have primitive data types
    - type safety
    
## Class Hierarchy for ArrayList
<img width="522" alt="image" src="https://user-images.githubusercontent.com/102199778/197314724-7489cbea-211f-4b51-a569-6b20da107978.png">

## Collection Interface
- A collection is a "bag" of objects
- Provides:
    - .add()
    - .remove()
    - .contains()
    - Iterator

https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collection.html

## LinkedList
- concrete class

## Choosing Lists
- LinkedList instead of ArrayList when: 
    - size of structure changes radically over time
    - random access not needed
    - insertion and deletion at head and tail and more common than search
    
## Iterator<E>
- Object that iterates over some collection
- Should not be modifying the list as you are iterating

## Collection vs Collections
- Collection interface: the root of the JCF
- Collections class: provides static methods

## Abstract Data Type: Queue
- "First-In-First-Out"

### classes that implement the Queue interface
- LinkedList
- ArrayDeque

## Priority Queue
- Standard Queue: order by insertion order
- Priority Queue: order by some ordering

## Stack
- Last in First out
- Add and remove items to/from the top of the stack

## Backward Compatibility
- Vector and Stack
    - synchronized
- Vector
    - extensible array
    - added generic
    - enumeration interface

## Sets and Maps

## Set Interface
- abstract data type
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Set.html

## Choosing Sets
- when order isn't important

## HashSet
- data structure
- implements the Set interface
- Approach: 
    - create a hash code from the object
    - code summarizes the content of the object
    
## TreeSet
- problem with HashSet is that the elements aren't ordered in any useful way
- TreeSet uses a natural ordering

## Abstract Data Type: Map
- Stores <key, value> pairs
- Key used to organize data
- Value is the data

## Map
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Map.html

## Enum
https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Enum.html

## Classes with Enum
- EnumMap
- EnumSet
