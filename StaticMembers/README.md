# Currency Converter Console Application

A simple **C# console application** that demonstrates the use of **static members**, **methods**, and **culture-invariant number formatting**. The application converts an amount in US dollars to Brazilian reais, applying an IOF tax.

## Features

* Read dollar exchange rate from user input
* Read dollar amount to be purchased
* Convert USD to BRL using a static conversion method
* Apply IOF tax automatically
* Display the final value formatted with `CultureInfo.InvariantCulture`

## Technologies Used

* C#
* .NET Console Application
* System.Globalization

## Project Structure

```
StaticMembers/
├── ConversorDeMoeda.cs
└── Program.cs
```

### ConversorDeMoeda.cs

Contains the `ConversorDeMoeda` class, which uses **static members** to perform currency conversion:

* `Iof`: static field representing the IOF tax percentage
* `DolarParaReal(...)`: static method that converts dollars to reais and applies IOF

This design avoids object instantiation and is suitable for utility-style classes.

### Program.cs

Contains the main execution logic:

* Reads user input from the console
* Calls the static currency conversion method
* Displays the final amount in reais

## Example Output

```
Qual é a cotação do dólar? 5.00
Quantos dólares você vai comprar? 100.00
Valor a ser pago em reais = 530.00
```

## Concepts Demonstrated

* Static classes and methods
* Separation of concerns
* Culture-independent numeric formatting
* Console input and output

## Author

Henrique Moreira
