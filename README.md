# Subtle Changes in Programming Languages

### by David Murdoch

## Contents

|Statements            | C | C++ | C# | Java | Javascript | Pascal | PHP | Python | Ruby | Scala |
|:---:                |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Hello World!         | [➤](#user-content-c) | [➤](#user-content-c-1) | [➤](#user-content-c-2) | [➤](#user-content-java) | [➤](#user-content-javascript) | [➤](#user-content-pascal) | [➤](#user-content-php) | [➤](#user-content-python) | [➤](#user-content-ruby) | [➤](#user-content-scala) |
| Declare Variable     | ➤ | ➤ | ➤ | [➤](#user-content-java-1) | [➤](#user-content-javascript-1) | [➤](#user-content-pascal-1) | [➤](#user-content-php-1) | [➤](#user-content-python-1) | [➤](#user-content-ruby-1) | [➤](#user-content-scala-1) |
| Type Conversions    | ➤ | ➤ | ➤ | [➤](#user-content-java-2) | [➤](#user-content-javascript-2) | [➤](#user-content-pascal-2) | [➤](#user-content-php-2) | [➤](#user-content-python-2) | [➤](#user-content-ruby-2) | [➤](#user-content-scala-2) |
| If/Else             | ➤ | ➤ | ➤ | [➤](#user-content-java-3) | [➤](#user-content-javascript-3) | [➤](#user-content-pascal-3) | [➤](#user-content-php-3) | [➤](#user-content-python-3) | [➤](#user-content-ruby-3) | [➤](#user-content-scala-3) |
| Switch Cases         | ➤ | ➤ | ➤ | [➤](#user-content-java-4) | [➤](#user-content-javascript-4) | [➤](#user-content-pascal-4) | [➤](#user-content-php-4) | [➤](#user-content-python-4) | [➤](#user-content-ruby-4) | [➤](#user-content-scala-4) |
| Arrays             | ➤ | ➤ | ➤ | [➤](#user-content-java-5) | [➤](#user-content-javascript-5) | [➤](#user-content-pascal-5) | [➤](#user-content-php-5) | [➤](#user-content-python-5) | [➤](#user-content-ruby-5) | [➤](#user-content-scala-5) |
| For Loops         | ➤ | ➤ | ➤ | [➤](#user-content-java-6) | [➤](#user-content-javascript-6) | [➤](#user-content-pascal-6) | [➤](#user-content-php-6) | [➤](#user-content-python-6) | [➤](#user-content-ruby-6) | [➤](#user-content-scala-6) |
| While Loops         | ➤ | ➤ | ➤ | [➤](#user-content-java-7) | [➤](#user-content-javascript-7) | [➤](#user-content-pascal-7) | [➤](#user-content-php-7) | [➤](#user-content-python-7) | [➤](#user-content-ruby-7) | [➤](#user-content-scala-7) |
| RegExp         	| ➤ | ➤ | ➤ | [➤](#user-content-java-8) | [➤](#user-content-javascript-8) | [➤](#user-content-pascal-8) | [➤](#user-content-php-8) | [➤](#user-content-python-8) | [➤](#user-content-ruby-8) | [➤](#user-content-scala-8) |
| Functions         | ➤ | ➤ | ➤ | [➤](#user-content-java-9) | [➤](#user-content-javascript-9) | [➤](#user-content-pascal-9) | [➤](#user-content-php-9) | [➤](#user-content-python-9) | [➤](#user-content-ruby-9) | [➤](#user-content-scala-9) |
| Objects             | ➤ | ➤ | ➤ | [➤](#user-content-java-10) | [➤](#user-content-javascript-10) | [➤](#user-content-pascal-10) | [➤](#user-content-php-10) | [➤](#user-content-python-10) | [➤](#user-content-ruby-10) | [➤](#user-content-scala-10) |
| Inheritance         | ➤ | ➤ | ➤ | [➤](#user-content-java-11) | [➤](#user-content-javascript-11) | [➤](#user-content-pascal-11) | [➤](#user-content-php-11) | [➤](#user-content-python-11) | [➤](#user-content-ruby-11) | [➤](#user-content-scala-11) |
| Constructors         | ➤ | ➤ | ➤ | [➤](#user-content-java-12) | [➤](#user-content-javascript-12) | [➤](#user-content-pascal-12) | [➤](#user-content-php-12) | [➤](#user-content-python-12) | [➤](#user-content-ruby-12) | [➤](#user-content-scala-12) |
| Exception Handlers | ➤ | ➤ | ➤ | [➤](#user-content-java-13) | [➤](#user-content-javascript-13) | [➤](#user-content-pascal-13) | [➤](#user-content-php-13) | [➤](#user-content-python-13) | [➤](#user-content-ruby-13) | [➤](#user-content-scala-13) |

## Hello World!

##### C

> ```c
> #include<stdio.h>
>
> main()
> {
>     printf("Hello World!\n"); /* prints Hello World! */
>     return 0;
>
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### C++
> ```cpp
> #include <iostream>
>
> //using namespace std;
> 
> int main() 
> {
>     std::cout << "Hello, World!\n"; // prints Hello World!
>     return 0;
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### C#
> ```c#
> using System;
> 
> class Program
> {
>     static void Main(string[] args)
>     {
>         Console.WriteLine("Hello World!"); // prints Hello World!
>     }
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Java
> ```java
> public class Main {
>     public static void main(String[] args) {
>         System.out.println("Hello World!"); // prints Hello World!
>     }
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Javascript
> ```javascript
> alert("Hello World!");
> console.log("Hello World!");
> document.write("Hello World!");
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Pascal
> ```
> program Project1;
> 
> uses SysUtils;
> 
> begin
> 	Writeln('Hello World!');
> end
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### PHP
> ```php
> <?php
>     echo "Hello World!\n";  // prints Hello World!
> ?>
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Python
> ```python
> print("Hello World!") # prints Hello World!
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Ruby
> ```ruby
> puts("Hello World!") # prints Hello World!
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

##### Scala
> ```scala
> object HelloWorld {
>     def main(args: Array[String]): Unit = {
>         println("Hello, world!")  // prints Hello World!
>     }
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

## Declare Variables

##### C
> ```c
> #include<stdio.h>
>
> main()
> {
>     int integer = 0;
>     float pi = 3.14;
>     char[] str = "Hello World";
>     bool boolean = true;
>     bool boolean2(false);
>
>     printf("%d %f %s",integer, pi, str);
>     return 0;
>
> }
> ```

##### C++
> ```cpp
> #include <iostream>
> #include <string>
>
> using namespace std;
> 
> int main() 
> {
>   int x = 42;
>   double pi = 3.14;
>   char y = "Z";
>   bool isOnline = true;
>   char firstName[] = "David";
>   string middleName = "Sebastian";
>   std::string lastName = "Murdoch";
>   return 0;
> }
> ```

##### C#
> ```c#
> using System;
> 
> class Program
> {
>   static void Main(string[] args)
>   {
>     int x = 42;
>     double pi = 3.14;
>     char y = 'Z';
>     bool isOnline = true;
>     string firstName = "David";
>   }
> }
> ```

##### Java
> ```java
> public class Main {
>
>   public static void main(String[] args) {
>
>     int x = 42;
>     double pi = 3.14;
>     char y = 'Z';
>     boolean isOnline = true;
>     String firstName = "David";
>   }
> }
> ```

##### Javascript
> ```javascript
> var x = 42;
> var pi = 3.14;
> var y = 'Z';
> var isOnline = true;
> var firstName = "David";
> ```

##### Pascal
> ```
> Program program;
>
> Uses
>   SysUtils;
>
> Var
>   x: Integer;
>   pi: Real;
>   y: Char;
>   isOnline: Boolean;
>   firstName: String;
> Begin
>   x:= 42;
>   pi:= 3.14;
>   y:= 'Z';
>   isOnline:= True;
>   firstName:= 'David';
> End.
> ```


##### PHP
> ```php
> <?php
>   $x = 42;
>   $pi = 3.14;
>   $y = 'Z';
>   $isOnline = True;
>   $firstName = "David";
> ?>
> ```

##### Python
> ```python
> x = 42;
> pi = 3.14;
> y = 'Z';
> isOnline = True;
> firstName = "David";
> ```

##### Ruby
> ```ruby
> x = 42 
> pi = 3.14
> y = 'Z'
> isOnline = true
> firstName = "David"
> ```

##### Scala
> ```scala
> object Main {
>   def main(args: Array[String]): Unit = {
>     var x = 42
>     var pi = 3.14
>     var y = 'Z'
>     var isOnline = true
>     var firstName = 'David'
>   }
> }
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

## Type Conversions

##### C
> ```c

> ```

##### C++
> ```cpp
string str = obj->ToString();
> ```

##### C#
> ```c#
string str = obj.ToString();
> ```

##### Java
> ```java
int num = Integer.parseInt(str);

String str= String.valueOf(num);

boolean bool = Boolean.parseBoolean(str);

String str = String.valueOf(bool);
> ```

##### Javascript
> ```javascript
var num = parseInt(str);

var str = num.toString();

var str = bool.toString();
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

https://www.w3schools.com/js/js_type_conversion.asp

##### Pascal
> ```

> ```

##### PHP
> ```php

> ```

##### Python
> ```python
type(variable)
str = str(number)
> ```

##### Ruby
> ```ruby

> ```

##### Scala
> ```scala

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## If Statements

##### C
> ```c

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### C++
> ```cpp

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### C#
> ```c#
> if (conditional) {
>   ...
> }
> else if (conditional) {
>   ...
> }
> else {
>   ...
> }
> ```
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### Java
> ```java
> if (conditional){
>   ...
> }
> else if (conditional) {
>   ...
> }
> else {
>   ...
> }
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### Javascript
> ```javascript
> if (conditional) {
>   ...
> }
> else if (conditional) {
>   ...
> }
> else {
>   ...
> }
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### Pascal
> ```
> If conditional
>   Then
>     Begin
>       ...
>     End
>   Else
>     Begin
>       ...
>     End;
>
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

##### PHP
> ```php
> <?php
>   if (conditional) {
>     ...
>   } 
>   elseif (conditional) {
>     ...
>   } 
>   else {
>     ...
>   }
> ?>
> ```

##### Python
> ```python
> if (conditional):
>   ...
> elif (conditional):
>   ...
> else:
>   ...
> ```

##### Ruby
> ```ruby
> if conditional
>   ...
> elsif conditional
>   ...
> else
>   ...
> end
> ```

##### Scala
> ```
> 
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

## Switch Statements

##### C
> ```c
> 
> ```

##### C++
> ```cpp
> 
> ```

##### C#
> ```c#
> switch (variable) {
>   case 0:
>     ...
>     break;
>   case 1:
>     ...
>     break;
>   default:
>     ...
>     break;
> }
> ```

##### Java
> ```java
> switch (variable) {
>   case 1:
>     ...
>     break;
>   case 2:
>     ...
>     break;
>   case 1:
>     ...
>     break;
>   default:
>     ...
>     break;
> }
> ```

##### Javascript
> ```javascript
> switch (variable) {
>   case 1:
>     ...
>     break;
>   case 2:
>     ...
>     break;
>   case 3:
>     ...
>     continue;
>   default:
>     ...
>     break;
> }
> ```

##### Pascal
> ```
> Case variable Of
>   1: Begin
>        ...
>      End;
>   2: Begin
>        ...
>      End;
>   3: Begin
>        ...
>      End;
> End;
> ```

##### PHP
> ```php
>  
> ```

##### Python
> ```python
> N/A
> ```

##### Ruby
> ```ruby
> case (variable) 
>   when 0
>     ...
>   when 1
>     ...
>   unless
>     ...    
> end
> ```

##### Scala

##### [Back to Top](#subtle-changes-in-programming-languages)

## Arrays

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#
int[] arr = new int[10];

Console.WriteLine(arr.Length);
> ```

##### Java
> ```java
int[] arr = new int[10];

int[] arrNumbers = new int[]{ 1, 2, 3, 4, 5};

System.out.println(arr.length);
> ```

##### Javascript
> ```javascript
var arr = [];

var arrNumbers = [ 1, 2, 3, 4, 5];

console.log(arr.length);
> ```

##### Pascal
> ```
> 
> ```

##### PHP
> ```php
>
> ```

##### Python
> ```python
arr = []

print(len(arr))
> ```

##### Ruby
> ```ruby
arr = []

puts(arr.length)
> ```

##### [Back to Top](#subtle-changes-in-programming-languages)

## For Loops

##### C
> ```c

> ```

##### C++
> ```cpp
for (int i = a; i < b; i++) {
  ...
}
> ```

##### C#
> ```c#
for (int i = a; i < b; i++) {
  ...
}
> ```

##### Java
> ```java
for (int i = a; i < b; i++) {
  ...
}
> ```

##### Javascript
> ```javascript
for (var i = a; i < b; i++) {
  ...
}
> ```

##### Pascal
> ```
For i := a To b
  Do ...
> ```

##### PHP
> ```php

> ```

##### Python
> ```python
> for i in range(a,b):
>   ...
> ```

##### Ruby
> ```ruby
>
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## While Loops

##### C
> ```c
>
> ```

##### C++
> ```cpp
>
> ```

##### C#
> ```c#
> while (comparator) {
>   ...
> }
> ```

##### Java
> ```java
while (comparator) {
    ...
}
> ```

##### Javascript
> ```javascript
while (comparator) {
    ...
}

do {
    ...
}
while (comparator);
> ```

##### Pascal
> ```
> While comparator
>   Do
>     Begin
>       ...
>     End;
> ```

##### PHP
> ```php

> ```

##### Python
> ```python
> while (comparator):
>   ...
> ```

##### Ruby
> ```ruby
> 
> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## RegExp

##### C
> ```c
> 
> ```

##### C++
> ```cpp
> 
> ```

##### C#
> ```c#
> 
> ```

##### Java
> ```java
>
> ```

##### Javascript
> ```javascript
str.match(/[a-z]/gi);
str.replace(/\bword\b/gi);
str.replace(/!$/, '');
> ```

##### Pascal
> ```
>
> ```

##### PHP
> ```php
>
> ```

##### Python
> ```python
>
> ```

##### Ruby
> ```ruby
>
> ```

##### Scala
> ```scala
>
> ```

## Functions

##### C
> ```c
>
> ```

##### C++
> ```cpp
>
> ```

##### C#
> ```c#
>
> ```

##### Java
> ```java
public static int func(int a, int b) {
    ...
    return 0;
}
> ```

##### Javascript
> ```javascript
> function func(a,b) {
>   ...
> }
> ```

##### Pascal
> ```
> 
> ```

##### PHP
> ```php

> ```

##### Python
> ```python
def func(a,b):
    ...
> ```

##### Ruby
> ```ruby

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Objects

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#

> ```

##### Java
> ```java
public class obj {
    String name = "David";
    int age = 24;
}
> ```

##### Javascript
> ```javascript
var obj = {
    name: "David",
    age: 24
}

var obj2 = {}
obj2.name = "David";
obj2.age = 24;
> ```

##### Pascal

##### PHP
> ```php

> ```

##### Python
> ```python

> ```

##### Ruby
> ```ruby

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Inheritance

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#

> ```

##### Java
> ```java
public class Child extends Parent {}

public class Car extends Vehicle {
    ...
}
> ```

##### Javascript
> ```javascript

> ```

##### Pascal

##### PHP
> ```php

> ```

##### Python
> ```python

> ```

##### Ruby
> ```ruby

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Constructors

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#

> ```

##### Java
> ```java

public class Vehicle {
  String make;
  String model;
    public Vehicle(String mak, String mode) {
        make = mak;
        model = mode;
    }
}

Vehicle Car = new Vehicle("BMW", "M5");
> ```

##### Javascript
> ```javascript

> ```

##### Pascal

##### PHP
> ```php

> ```

##### Python
> ```python

> ```

##### Ruby
> ```ruby

> ```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Exception Handlers

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#

> ```

##### Java
> ```java

> ```

##### Javascript
> ```javascript

> ```

##### Pascal

##### PHP
> ```php

> ```

##### Python
> ```python

> ```

##### Ruby
> ```ruby

> ```

## Nonsense

##### C
> ```c

> ```

##### C++
> ```cpp

> ```

##### C#
> ```c#

> ```

##### Java
> ```java

> ```

##### Javascript
> ```javascript

> ```

##### Pascal
> ```

> ```

##### PHP
> ```php

> ```

##### Python
> ```python

> ```

##### Ruby
> ```ruby

> ```

##### Scala
> ```scala

> ```


##### [Back to Top](#subtle-changes-in-programming-languages)
