# FactoryMethodDesignPattern
This respository explores an implementation of the factory method design pattern. 
Within the main directory is a text file - "products.txt" which defines two products along with their prices on seperate lines to test functionality. 
The src directory contains the abstract classes for Grocery Factory and Grocery Product, that concrete factories and concrete items will inherit from. 
Within the test directory are all the the concrete classes that inherit from abstractions.
The test class is labelled as GroceryStore. It uses the java File package to read the text file and extract products along with their prices, and uses factories to create products accordingly.
It is responsible for testing the functionality of the design pattern and instantiating the factories that are responsible for creating concrete products.
Each new line defines a new product. It reads the lines into an array, and calls on the correct factory to create the object based on what the item is.


![image](https://github.com/j-fisher2/FactoryMethodDesignPattern/assets/113472699/53fe377e-f2a2-488c-b2a5-db807e8ef1a8)
