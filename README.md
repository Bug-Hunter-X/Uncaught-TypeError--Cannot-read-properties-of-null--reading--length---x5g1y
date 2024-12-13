# Uncaught TypeError: Cannot read properties of null (reading 'length')

This repository demonstrates a common JavaScript error: `Uncaught TypeError: Cannot read properties of null (reading 'length')`.  This error occurs when you try to access the `length` property of a variable that holds a `null` value.  The provided code shows the problematic code snippet and a solution to prevent the error. 

## Problem

The `foo` function attempts to access the `length` property of the input `x`. If `x` is `null`, this will throw the error.

## Solution

The solution involves explicitly checking for `null` before accessing `length`, providing a default value or handling the case appropriately.
