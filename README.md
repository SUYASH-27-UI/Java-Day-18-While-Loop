# Java-Day-18-While-Loop
# Java Day 18 - While Loop

## Description

This program uses a `while` loop to print numbers from 1 to 10.

A `while` loop repeatedly executes a block of code as long as the given condition is true.

## Example Output

```text
1
2
3
4
5
6
7
8
9
10
```

## Code

```java
public class Main
{
    public static void main(String[] args)
    {
        int number = 1;

        while (number <= 10)
        {
            System.out.println(number);
            number++;
        }
    }
}
```

## Concepts Used

* `while` loop
* Variables
* Conditions
* Increment operator `++`
* `System.out.println()`

## How It Works

1. The variable `number` starts with the value `1`.
2. The `while` loop checks whether `number` is less than or equal to `10`.
3. If the condition is true, the number is printed.
4. `number++` increases the value by 1.
5. The loop continues until the condition becomes false.
6. When `number` becomes `11`, the loop stops.

## File Name

`Main.java`

## Goal

The goal of this program is to understand the basic working of a `while` loop in Java.
