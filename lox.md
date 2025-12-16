# Spec

## Overall
* dynamic typing

## Data Types
* boolean: `true` or `false`
* number: IEE754 double float
* string
* nil

## Expressions
* arithmetic
  * infix and prefix
  * only work on numbers
    * exception is `+` operator for string concatenation
* comparison and equality
* logical operators: `!`, `and`, `or`
* standard precedence

## Statements
* expression main job is to produce a value, statement's job is to produce an effect
* An expression followed by a semicolon (;) promotes the expression to statement-hood. This is called (imaginatively enough), an expression
statement.
* pack multiple statements in a block

## Variables
* declare variables using `var`
* variable's value defaults to `nil` if you omit initializer

## Control flow
* `if`, `while`, `for`

## Functions
* define using `fun`
* **argument** is the actual value you pass to a function when you call it
* **parameter** is a variable that holds the value of the argument inside the body of the function

## Closures
* functions are first class

## Classes
* classes are first class 
* class itself is a factory function for instances
* assigning to a field creates it if it doesn't already exist
* access field or method on current object using `this`
* `init()` automatically called when object is constructed
* single inheritance, using `<` operator
  * use `super` to call methods in parent class

## Standard library
* `print`
* `clock`