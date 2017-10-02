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


Java
```java
int integer = 0;
String string = "Hello World";
boolean bool = true;
```

Javascript
```javascript
var variable = 0;
```

Pascal

PHP

Python
```python
variable = 0;
boolVariable = True;
```

Ruby

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

## Arrays

C

C++

C#

Java
int arr[] = new int[10];

Javascript
```javascript
arr = [];

console.log(arr.length);
```

Pascal

PHP

Python
```python
arr = []

print(len(arr))
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

Javascript

Pascal

PHP

Python

Ruby

## Constructors

C

C++

C#

Java

Javascript

Pascal

PHP

Python

Ruby

|Statements| C | C++ | C# | Java | Javascript | Pascal | PHP | Python | Ruby |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Declare Variable | - | - | - | - | `var variable` | - | - | - | - |
| Array Length | - | - | - |`array.length` | `array.length` | - | - | - | - |
| If/Else | - | - | - | - | - | - | - | - | - |
| Switch Cases | - | - | - | - | - | - | - | - | - |
| - | - | - | - | - | - | - | - | - | - |



```c++
int variable;
string variable;
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