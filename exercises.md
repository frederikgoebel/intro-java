## If & Loops

### Stars

#### Line
Write a program that, given a number as input, prints a line with that many stars.
```
input: 4
output: * * * *
```
Change your program so that it accepts two numbers and prints a square of stars.
```
input: 4
input: 3
output: 
* * * *
* * * *
* * * *
```

#### Triangle
Write a program that, given a number as input, prints a triangle with that many stars.
```
input: 4
output: 
* * * *
* * *
* *
*
```

### Fizzbuzz
Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”.

### Loops and Math

#### Dec2Bin
Write a method that prints a given decimal numer in binary form.
```
input: 42
output: 101010
```

#### Intervallhalbierungsverfahren or Bisection method
Write a method that calculates the square root of a given numer by using the bisection method.
```
Input: 9
Output:
Iteration 1: mid=5 5*5=25 error=16
Iteration 2: mid=3 3*3=9 error=0
```

#### Calculator
Write a program that emulates a calculator. 
It should support:
- ```+``` (addition)
- ```-``` (subtraction)
- ```*``` (multiplication)
- ```/``` (division)

It accepts the operants and the operation on multiple lines.
```
Input:
3
*
2
Output: 3 * 2 = 6
```
Hint:
```Java
// String comparison works like this:
Scanner scanner = new Scanner(System.in);
String a = scanner.next();

if(a.equals("hello")){
    System.out.println("Are equal");
}

if("hello".equals(a)){
    System.out.println("Are equal");
}
```
More features: 
1. Add looping to the calculator. Instead of exiting after the calculation it should ask the user if they want to continue or quit. If the user enters `quit` the program stops. 
2. Handle division by zero. As you might have noticed an input of 2/0 crashes the program. Handle that case.
3. (EXTRA/HARDER) Give the user the possibility to use the last result as one of the values in the next calculation.
```
Input:
3
*
2
Output: 3 * 2 = 6
Input:
last
*
2
Output: 12
```


## Recursion

### Towers of hanoi
Write a program that solves the towers of hanoi game.

### Fibonacci
Write a method that, given an input n, calculates the first n numbers of the fibonacci sequence.
The fibonacci sequence is defines as: 
```
fib(1) = 1
fib(2) = 1
fib(n) = f(n-1) + f(n-2)
```

## Projects

### Text adventure
Write a text adventure game. If you need inspiration ask ssomebody with a mac to run this line in the terminal:

```emacs -batch -l dunnet```


## Arrays

### Tower hopping
### longest reoccurring character
### Find 
### Sort


