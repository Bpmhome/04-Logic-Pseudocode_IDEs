<a href="https://github.com/CyberTrainingUSAF/04-IDE-s-and-Algorithms-Pt.-1/blob/master/00-Table-of-Contents.md" rel="Return to TOC"> Return to TOC </a>

---
 
![](/01_pseudocode/assets/bookCover.png)

**Information used in this lesson topic and Figures shown are from the following source:** Farrell, Joyce, Programming Logic & Design (2017), comprehensive, 9th edition. Centage Learning, 20 Channel Center Street, Boston, MA 02210. USA
ISBN-10: 1-337-10207-5, ISBN-13: 978-1-337-10207-0

---

## Pseudocode

**Objective**

**In this section, you will learn about:**
* Declaring and using variables and constants
* Performing arithmetic operations
* The advantages of modularization
* Modularizing a program
* Hierarchy charts
* Features of good program design

---

## Declaring and Using, Variables and Constants

**Understanding Data Types**
* Data type describes:
  * What values can be held by the item
  * How the item is stored in memory
  * What operations can be performed on the item

* All programming languages support these data types:
  * Numeric consists of numbers that can be used in math
  * String is anything not used in math

---

## Understanding Unnamed, Literal Constants

**There are two types of constants**
* Numeric constant (or literal numeric constant)
* Contains numbers only
* Number does not change

**String constant (or literal string constant)**
* Also known as Alphanumeric values
* Can contain both alphabetic characters and numbers
* Strings are enclosed in quotation marks

## Working with Variables

**Variable are named memory locations** 

**Contents can vary or differ over time**

**Declaration is a statement that provides a variable's:**
* Data type 
* Identifier (variable’s name)
* Optionally, an initial value

### Flowchart and pseudocode of number-doubling program with variable declarations

![](/01_pseudocode/assets/flowchart1.jpg)

Programming Logic & Design (2017), 9th edition

---

**Casing conventions**

* Variable names that start with a lowercase character.  If a second part is added to the name it should start with an Uppercase character.  Example: **h**ourly**W**age. Commonly referred to as (Camel case)
* Variable names where the first letter in each word in uppercase such as **H**ourly**W**age (Pascal casing)
* A form of camel casing in which the data type is part of the name such as **num**HourlyWage (Hungarian casing)

**Other examples of casing types**
* Parts of variable names are separated by underscores such as hourly **_** wage (snake casing)
* Similar to snake casing, but new words start with a uppercase letter such as **H**ourly_**W**age (mixed case)
* Parts of variable names are separated by dashes such as hourly **-** wage (Kebob case)

## Assigning Values to Variables

**Assignment statement**
* set myAnswer = myNumber * 2

**Assignment operator**
* Equal sign 
* A binary operator, meaning it requires two operands—one on each side     
* Always operates from right to left, which means that it has right-associativity or right-to-left associativity
* The result to the left of an assignment operator is called an lvalue  **Example: operand2 (lvalue) = operand1 * X **

## Initializing a Variable

**Initializing the variable - declare a starting value**

```
num yourSalary = 22.57 
string yourName = “Larry”
```

**Garbage – a variable’s unknown value**

**Variables must be declared before they are used in the program**

## Declaring Named Constants

**Named constant** 
* Similar to a variable
* Can be assigned a value only once
* Assign a useful name to a value that will never be changed during a program’s execution

**Magic number** 
Unnamed constant
* Use
```
taxAmount = price * SALES_TAX_AMOUNT 
```

**instead of:**
```
taxAmount = price * .06
```

## Performing Arithmetic Operations

Standard arithmetic operators:
+ (plus sign)—addition
− (minus sign)—subtraction
* (asterisk)—multiplication
/ (slash)—division
% (percent sign)-remainder

**Rules of precedence**
* Expressed as Order of operations
* States the order in which operations are carried out
* Expressions within parentheses are evaluated first
* All the arithmetic operators have left-to-right associativity
* Multiplication and division are evaluated next
  * From left to right
* Addition and subtraction are evaluated next
  * From left to right

### Precedence & Associativity of Five Common Operators
![](/01_pseudocode/assets/precedence3.jpg)

Programming Logic & Design (2017), 9th edition

---

## Creating Hierarchy Charts

**Hierarchy chart**
* Shows the overall picture of how modules are related to one another
* Defines which modules exist within a program and which modules call others
* A Specific module may be called from locations within a program

**Planning tool** 
* Develop the overall relationship of program modules before you write them 

**Documentation tool**

### Hierachy chart of payroll report program
![](/01_pseudocode/assets/higharchy4.jpg)

Programming Logic & Design (2017), 9th edition

---
### Billing program hiearchy chart
![](/01_pseudocode/assets/higharchy5.jpg)

Programming Logic & Design (2017), 9th edition

---
## Features of Good Program Design

**Use program comments where appropriate**

**Identifiers should be chosen carefully**

**Strive to design clear statements within your programs and modules**

**Write clear prompts and echo input**

**Continue to maintain good programming habits as you develop your programming skills**

## Maintaining Good Programming Habits

**Every program you write will be better if you:** 
* Plan prior to coding
* Continue to draw flowcharts or write pseudocode
* Draft your program logic on paper
* Think carefully about the variable and module names you use
* Design your program statements for ease of reading and use

## Summary
* Programs contain literals, variables, and named constants
* Arithmetic follows rules of precedence
* Break down programming problems into modules
* Include a header, a body, and a return statement
* Hierarchy charts show relationship among modules
* As programs become more complicated: 
* Need for good planning and design increases

<a href="https://github.com/CyberTrainingUSAF/04-IDE-s-and-Algorithms-Pt.-1/blob/master/01_pseudocode/03_Structure.md" > Continue to Next Topic </a>


