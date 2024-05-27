# Balanced Bracket Checker

This project contains a Java implementation to check if a string of brackets is balanced. The brackets can be any of the following: `{}`, `[]`, `()`.

## Usage

The `BalancedBracket` class provides a method `isBalanced` which checks if the input string has balanced brackets. The class uses a stack to keep track of opening brackets and ensures that every closing bracket has a corresponding opening bracket.

### Method: isBalanced

```java
public static String isBalanced(String s)
