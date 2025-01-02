# Dart Index Out of Bounds Error

This repository demonstrates a common error in Dart: an index out of bounds exception.  The `bug.dart` file contains code that attempts to access an element in a list using an index that is greater than or equal to the length of the list.  The `bugSolution.dart` file shows how to prevent this error using proper bounds checking.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `dart bug.dart`

You should see an error message indicating an index out of range exception.

## Solution

The solution involves checking if the index is within the valid range of the list before attempting to access the element. The `bugSolution.dart` demonstrates this best practice.