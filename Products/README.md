# Product Inventory Console Application

A simple **C# console application** that demonstrates basic object-oriented programming concepts such as classes, methods, encapsulation, and formatted output. The application allows users to manage a product's inventory by adding and removing items while displaying updated stock information.

## Features

* Create a product with name, price, and initial quantity
* Calculate total value in stock
* Add products to inventory
* Remove products from inventory
* Display formatted product data using `CultureInfo.InvariantCulture`

## Technologies Used

* C#
* .NET Console Application
* System.Globalization for culture-independent number formatting

## Project Structure

```
Course/
├── Produto.cs
└── Program.cs
```

### Produto.cs

Contains the `Produto` class, responsible for:

* Storing product data (`Nome`, `Preco`, `Quantidade`)
* Calculating total stock value
* Adding and removing products from inventory
* Formatting output using `ToString()`

### Program.cs

Contains the `Main` method, responsible for:

* Reading user input from the console
* Creating and manipulating a `Produto` object
* Displaying product data before and after stock updates
