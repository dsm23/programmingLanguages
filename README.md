# Subtle Changes in Programming Languages

### by David Murdoch

## Contents

|Statements			| C | C++ | C# | Java | Javascript | Pascal | PHP | Python | Ruby |
|:---:				|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Hello World! 		| ➤ | ➤ | ➤ | [➤](#user-content-java) | [➤](#user-content-javascript) | ➤ | ➤ | ➤ | ➤ |
| Declare Variable 	| ➤ | ➤ | ➤ | [➤](#user-content-java-1) | [➤](#user-content-javascript-1) | ➤ | ➤ | ➤ | ➤ |
| Type Conversions	| ➤ | ➤ | ➤ | [➤](#user-content-java-2) | [➤](#user-content-javascript-2) | ➤ | ➤ | ➤ | ➤ |
| If/Else 			| ➤ | ➤ | ➤ | [➤](#user-content-java-3) | [➤](#user-content-javascript-3) | ➤ | ➤ | ➤ | ➤ |
| Switch Cases 		| ➤ | ➤ | ➤ | [➤](#user-content-java-4) | [➤](#user-content-javascript-4) | ➤ | ➤ | ➤ | ➤ |
| Arrays 			| ➤ | ➤ | ➤ | [➤](#user-content-java-5) | [➤](#user-content-javascript-5) | ➤ | ➤ | ➤ | ➤ |
| For Loops 		| ➤ | ➤ | ➤ | [➤](#user-content-java-6) | [➤](#user-content-javascript-6) | ➤ | ➤ | ➤ | ➤ |
| While Loops 		| ➤ | ➤ | ➤ | [➤](#user-content-java-7) | [➤](#user-content-javascript-7) | ➤ | ➤ | ➤ | ➤ |
| Functions 		| ➤ | ➤ | ➤ | [➤](#user-content-java-8) | [➤](#user-content-javascript-8) | ➤ | ➤ | ➤ | ➤ |
| Objects 			| ➤ | ➤ | ➤ | [➤](#user-content-java-9) | [➤](#user-content-javascript-9) | ➤ | ➤ | ➤ | ➤ |
| Inheritance 		| ➤ | ➤ | ➤ | [➤](#user-content-java-10) | [➤](#user-content-javascript-10) | ➤ | ➤ | ➤ | ➤ |
| Constructors 		| ➤ | ➤ | ➤ | [➤](#user-content-java-11) | [➤](#user-content-javascript-11) | ➤ | ➤ | ➤ | ➤ |
| Exception Handlers | ➤ | ➤ | ➤ | [➤](#user-content-java-12) | [➤](#user-content-javascript-12) | ➤ | ➤ | ➤ | ➤ |

## Hello World!

##### C
```c
#include<stdio.h>

main()
{
	printf("Hello World\n");

}
```

##### C++
```cpp
#include <iostream>

int main() 
{
    std::cout << "Hello, World!\n";
    return 0;
}
```

##### C#
```c#
using System;

class Program
{
	static void Main(string[] args)
	{
		Console.WriteLine("Hello World!");
	}
}
```

##### Java
```java
public class Main {
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

##### Javascript
```javascript
alert("Hello World!");
console.log("Hello World!");
document.write("Hello World!");
```

##### Pascal

##### PHP
```php
echo "Hello World!\n";
```

##### Python
```python
print("Hello World!")
```

##### Ruby
```ruby
puts("Hello World!")
```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Declare Variables

##### C
```c

```

##### C++
```cpp
int integer = 0;
string string = "Hello World";
bool boolean = true;
bool boolean2(false);
```

##### C#
```c#
int x = 42;
double pi = 3.14;
char y = 'Z';
bool isOnline = true;
string firstName = "David";
```

##### Java
```java
int x = 42;
double pi = 3.14;
char y = 'Z';
boolean isOnline = true;
String firstName = "David";
```

##### Javascript
```javascript
var x = 42;
var pi = 3.14;
var y = 'Z';
var isOnline = true;
var firstName = "David";
```

##### Pascal

##### PHP

##### Python
```python
x = 42;
pi = 3.14;
y = 'Z';
isOnline = True;
firstName = "David";
```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Type Conversions

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
int num = Integer.parseInt(str);

String str= String.valueOf(num);
```

##### Javascript
```javascript
var num = parseInt(str);

var str = num.toString();
```
https://www.w3schools.com/js/js_type_conversion.asp

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```

## If Statements

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
if (comparator){
	...
}
else if {
	...
}
else {
	...
}
```

##### Javascript
```javascript
if (comparator){
	...
}
else if {
	...
}
else {
	...
}
```

##### Pascal

##### PHP
```php

```

##### Python
```python
if (operator):
	...
elif:
	...
else:
	...
```

##### Ruby
```ruby

```

##### [Back to Top](#subtle-changes-in-programming-languages)

## Switch Statements

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#
switch (variable) {
    case 0:
		...
		break;
    case 1:
		...
		break;
	default:
		...
		break;
}
```

##### Java
```java

```

##### Javascript
```javascript
switch (variable) {
	case 1:
		...
		break;
	case 2:
		...
		break;
	case 3:
		...
		continue;
	default:
		...
		break;
}
```

##### Pascal

##### PHP
```php

```

##### Python
```python
N/A
```

##### Ruby
```ruby
case (variable) 
    when 0
		...
    when 1
		...
	unless
		...    
end
```

##### [Back to Top](#subtle-changes-in-programming-languages)

## Arrays

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#
int[] arr = new int[10];

Console.WriteLine(arr.Length);
```

##### Java
```java
int arr[] = new int[10];

System.out.println(arr.length);
```

##### Javascript
```javascript
var arr = [];

console.log(arr.length);
```

##### Pascal

##### PHP
```php

```

##### Python
```python
arr = []

print(len(arr))
```

##### Ruby
```ruby
arr = []

puts(arr.length)
```

##### [Back to Top](#subtle-changes-in-programming-languages)

## For Loops

##### C
```c

```

##### C++
```cpp
for (int i = a; i < b; i++) {}
```

##### C#
```c#

```

##### Java
```java
for (int i = a; i < b; i++) {}
```

##### Javascript
```javascript
for (var i = a; i < b; i++) {}
```

##### Pascal

##### PHP
```php

```

##### Python
```python
for i in range(a,b):
```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## While Loops

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
while (comparator) {
	...
}
```

##### Javascript
```javascript
while (comparator) {
	...
}

do {
    ...
}
while (comparator);
```

##### Pascal

##### PHP
```php

```

##### Python
```python
while (comparator):
	...
```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Functions

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
public static int func(int a, int b) {
	...
	return 0;
}
```

##### Javascript
```javascript
function func(a,b) {
	...
}
```

##### Pascal

##### PHP
```php

```

##### Python
```python
def func(a,b):
	...
```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Objects

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
public class obj {
	String name = "David";
	int age = 24;
}
```

##### Javascript
```javascript
var obj = {
	name: "David",
	age: 24
}

var obj2 = {}
obj2.name = "David";
obj2.age = 24;
```

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Inheritance

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java
public class Child extends Parent {}

public class Car extends Vehicle {
	...
}
```

##### Javascript
```javascript

```

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Constructors

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java

public class Vehicle {
  String make;
  String model;
	public Vehicle(String mak, String mode) {
		make = mak;
		model = mode;
	}
}

Vehicle Car = new Vehicle("BMW", "M5");
```

##### Javascript
```javascript

```

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```
##### [Back to Top](#subtle-changes-in-programming-languages)

## Exception Handlers

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java

```

##### Javascript
```javascript

```

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```

## Nonsense

##### C
```c

```

##### C++
```cpp

```

##### C#
```c#

```

##### Java
```java

```

##### Javascript
```javascript

```

##### Pascal

##### PHP
```php

```

##### Python
```python

```

##### Ruby
```ruby

```


##### [Back to Top](#subtle-changes-in-programming-languages)

|Statements			| C | C++ | C# | Java | Javascript | Pascal | PHP | Python | Ruby |
|:---:				|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Hello World! 		| ➤ | ➤ | ➤ | [➤](#user-content-java) | [➤](#user-content-javascript) | ➤ | ➤ | ➤ | ➤ |
| Declare Variable 	| ➤ | ➤ | ➤ | [➤](#user-content-java-1) | [➤](#user-content-javascript-1) | ➤ | ➤ | ➤ | ➤ |
| If/Else 			| ➤ | ➤ | ➤ | [➤](#user-content-java-2) | [➤](#user-content-javascript-2) | ➤ | ➤ | ➤ | ➤ |
| Switch Cases 		| ➤ | ➤ | ➤ | [➤](#user-content-java-3) | [➤](#user-content-javascript-3) | ➤ | ➤ | ➤ | ➤ |
| Arrays 			| ➤ | ➤ | ➤ | [➤](#user-content-java-4) | [➤](#user-content-javascript-4) | ➤ | ➤ | ➤ | ➤ |
| For Loops 		| ➤ | ➤ | ➤ | [➤](#user-content-java-5) | [➤](#user-content-javascript-5) | ➤ | ➤ | ➤ | ➤ |
| While Loops 		| ➤ | ➤ | ➤ | [➤](#user-content-java-6) | [➤](#user-content-javascript-6) | ➤ | ➤ | ➤ | ➤ |
| Functions 		| ➤ | ➤ | ➤ | [➤](#user-content-java-7) | [➤](#user-content-javascript-7) | ➤ | ➤ | ➤ | ➤ |
| Objects 			| ➤ | ➤ | ➤ | [➤](#user-content-java-8) | [➤](#user-content-javascript-8) | ➤ | ➤ | ➤ | ➤ |
| Inheritance 		| ➤ | ➤ | ➤ | [➤](#user-content-java-9) | [➤](#user-content-javascript-9) | ➤ | ➤ | ➤ | ➤ |
| Constructors 		| ➤ | ➤ | ➤ | [➤](#user-content-java-10) | [➤](#user-content-javascript-10) | ➤ | ➤ | ➤ | ➤ |
| Exception Handlers | ➤ | ➤ | ➤ | [➤](#user-content-java-11) | [➤](#user-content-javascript-11) | ➤ | ➤ | ➤ | ➤ |


