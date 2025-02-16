# Null Value Handling Bug in JavaScript Function

This repository demonstrates a common bug in JavaScript functions related to handling null values. The `foo` function does not gracefully handle null input, leading to unexpected behavior or errors.

## Bug Description

The `foo` function is designed to perform operations on two input parameters `a` and `b`.  However, it lacks robust error handling for the case where either `a` or `b` is null.  This can lead to unexpected behavior, such as unhandled exceptions or incorrect results.

## Solution

The improved `foo` function includes a check for null values at the start of the function and returns early or throws an error depending on whether this null value is expected. 