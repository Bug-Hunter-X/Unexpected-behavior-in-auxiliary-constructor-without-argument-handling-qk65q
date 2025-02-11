# Scala Auxiliary Constructor Bug

This repository demonstrates a potential issue with auxiliary constructors in Scala when not explicitly providing default values or handling the cases when no values are provided to the auxiliary constructor.

The `bug.scala` file shows the initial code that demonstrates the issue. The `bugSolution.scala` file demonstrates the correct way to address this issue. 

## Bug Description

The issue arises in the auxiliary constructor of the `MyClass` class.  If you instantiate `MyClass` without any arguments, unexpected behavior may occur if no default value is handled properly.

## Solution

The solution involves ensuring that the auxiliary constructor explicitly handles the missing arguments by providing sensible defaults.