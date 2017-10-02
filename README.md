# Subtle Changes in Programming Languages

### by David Murdoch

## Contents

* [Hello World](#hello-world)

* [Declare Variables](#declare-variables)

* [If Statements](#if-statements)

* [Switch Statements](#switch-statements)

* [Arrays](#arrays)

* [For Loop](#for-loop)

* [While Loop](#while-loop)

* [Functions](#functions)

## Hello World!

C
```c
#include<stdio.h>

main()
{
	printf("Hello World\n");

}
```

C++
```cpp
#include <iostream>

int main() 
{
    std::cout << "Hello, World!\n";
    return 0;
}
```

C#
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

Java
```java
public class Main {
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

Javascript
```javascript
alert("Hello World!");
console.log("Hello World!");
document.write("Hello World!");
```

Pascal

PHP
```php
echo "Hello World!\n";
```

Python
```python
print("Hello World!")
```

Ruby
```ruby
puts("Hello World!")
```

## Declare Variables

C

C++
```cpp
int integer = 0;
string string = "Hello World";
bool boolean = true;
bool boolean2(false);
```

C#
```c#
int x = 42;
double pi = 3.14;
char y = 'Z';
bool isOnline = true;
string firstName = "David";
```

Java
```java
int x = 42;
double pi = 3.14;
char y = 'Z';
boolean isOnline = true;
String firstName = "David";
```

Javascript
```javascript
var x = 42;
var pi = 3.14;
var y = 'Z';
var isOnline = true;
var firstName = "David";
```

Pascal

PHP

Python
```python
x = 42;
pi = 3.14;
y = 'Z';
isOnline = True;
firstName = "David";
```

Ruby
```ruby

```

## If Statements

C

C++

C#

Java
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

Javascript
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

Pascal

PHP

Python
```python
if (operator):
	...
elif:
	...
else:
	...
```

Ruby

## Switch Statements

C

C++

C#

Java

Javascript
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

Pascal

PHP

Python
```python
switch (variable):
	case 1:
		...
		break;
	case 2:
		...
		break;
	case 3:
		...
		continue;
	else:
		...
		break;
```

Ruby

## Arrays

C
```c

```

C++



C#

Java
```java
int arr[] = new int[10];

System.out.println(arr.length);
```

Javascript
```javascript
arr = [];

console.log(arr.length);
```

Pascal

PHP
```php

```

Python
```python
arr = []

print(len(arr))
```

Ruby

```ruby

```

## For Loops

C++
```cpp
for (int i = a; i < b; i++) {}
```

Java
```java
for (int i = a; i < b; i++) {}
```

Javascript
```javascript
for (var i = a; i < b; i++) {}
```

Python
```python
for i in range(a,b):
```

## While Loops

C

C++

C#

Java

Javascript
```javascript
while (comparator) {
	...
}
```

Pascal

PHP

Python
```python
while (comparator):
	...
```

Ruby

## Functions

C

C++

C#

Java
```java
public static int func(int a, int b) {
	...
	return 0;
}
```

Javascript
```javascript
function func(a,b) {
	...
}
```

Pascal

PHP

Python
```python
def func(a,b):
	...
```

Ruby

## Objects/Classes

C

C++

C#

Java
```java
public class obj {
	String name = "David";
	int age = 24;
}
```

Javascript
```javascript
var obj = {
	name: "David",
	age: 24
}

var obj2 = {}
obj2.name = "David";
obj2.age = 24;
```

Pascal

PHP

Python

Ruby

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

|Statements| C | C++ | C# | Java | Javascript | Pascal | PHP | Python | Ruby |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Declare Variable | - | - | - | - | `var variable` | - | - | - | - |
| Array Length | - | - | - |`array.length` | `array.length` | - | - | - | - |
| If/Else | - | - | - | - | - | - | - | - | - |
| Switch Cases | - | - | - | - | - | - | - | - | - |
| - | - | - | - | - | - | - | - | - | - |


