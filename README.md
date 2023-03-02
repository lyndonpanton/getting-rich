# getting-rich
Marked Programming Assignment 2 of the "Intermediate Object-Oriented Programming for Unity Games" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

For this assignment, you need to implement the MutualFund and EmployerSponsoredAccount classes as shown in the class diagram below:

InvestmentAccount

The constructor uses the initial deposit to set the balance field

The AddMoney method adds the given money to the balance (with error checking)

The UpdateBalance method is abstract, so it doesn't have a body

SavingsAccount

The constructor uses the initial deposit to set the balance field and uses the provided interest rate to initialize the interestRate field

The UpdateBalance method accrues interest using the interestRate field

MutualFund

The constructor uses the initial deposit to set the balance

The AddMoney method deducts service charge using the ServiceChargePercent constant before changing the balance

The UpdateBalance method updates the balance using the value of the investments in the fund assuming 6% growth

EmployerSponsoredAccount

The constructor uses the initial deposit to set the balance

The AddMoney method doubles the money being added before adjusting the balance

## Getting Started

n/a

### Dependencies

* Windows 10
* Microsoft Visual Studio
* .NET

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/getting-rich)

### Executing program

n/a

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## License

n/a

## Acknowledgments

Problem provided by the _University of Colorado_ and _Coursera_
