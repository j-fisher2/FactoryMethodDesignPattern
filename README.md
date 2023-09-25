# FactoryMethodDesignPattern
This respository explores an implementation of the factory method design pattern. 
Within the main directory is a text file - "products.txt" which defines two products along with their prices on seperate lines to test functionality. 
The src directory contains the abstract classes for Grocery Factory and Grocery Product, that concrete factories and concrete items will inherit from. 
Within the test directory are all the the concrete classes that inherit from abstractions.
The test class is labelled as GroceryStore. It uses the java File package to read the text file and extract products along with their prices, and uses factories to create products accordingly.
This test/client is responsible for testing the functionality of the design pattern and instantiating the factories that are responsible for creating concrete products.
This results in a dependency relationship between the factories and products. The factories it instantiates utilize polymorphism, as they both inherit from an abstract factory.
Each new line defines a new product. It reads the lines into an array, and calls on the correct factory to create the object based on what the item is and the price associated with it. 
Then, in addition to this creation, it maintains an array labelled as inventory, holding objects of type GroceryProduct (polymorphism), and adds each new grocery item to this array.
For this assignment, the featured client was only interested in the production of apples and bananas, but the real world implementations of this concept are endless.



![image](https://github.com/j-fisher2/FactoryMethodDesignPattern/assets/113472699/53fe377e-f2a2-488c-b2a5-db807e8ef1a8)
