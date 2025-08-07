# JavaStaticAndInstanceDemo
A simple Java project that demonstrates the execution order of static blocks, static methods, instance blocks, constructors, and instance methods in a class. Useful for Java beginners to understand class loading and object instantiation behavior.


# JavaStaticAndInstanceDemo

This Java project illustrates the concept and execution order of:

- Static blocks
- Static methods
- Instance initialization blocks
- Constructors
- Instance methods

## 🔍 What It Demonstrates

This code shows how Java handles class-level and object-level initialization using static and instance blocks. It prints the execution order of each block/method when the class is loaded and an object is instantiated.

----------- OUTPUT ------------
Inside static block.
Inside static method.
Inside instance block.
Inside constructor.
Inside instance method.

<-----------END

------------>START

# JavaStaticVariableInterestCalculator

This Java project demonstrates how to use a `static` variable as a common shared resource across multiple objects—in this case, to calculate **Simple Interest (SI)** for different businessmen using a fixed rate of interest.

## 💡 Key Concepts Demonstrated

- Use of `static` variables for shared values (interest rate).
- Object-oriented programming (OOP) concepts.
- Simple user input using `Scanner`.
- Basic formula-based calculations in Java.
- Reusability of class methods across multiple objects.

## 🧮 Simple Interest Formula

\[
Simple Interset(pi) = (p*t*r)/100
\]

Where:  
- **P** = Principal amount  
- **T** = Time (in years)  
- **R** = Rate of interest (common for all instances, declared `static`)

-----------------OUTPUT------------------
Enter the principle amount: 50000
Enter the tenure : 2
15200.0
Enter the principle amount: 100000
Enter the tenure : 2
30400.0
Enter the principle amount: 150000
Enter the tenure : 2
45600.0
