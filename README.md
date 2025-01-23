# ActionScript 3: 1061: Call to a possibly undefined method

This repository demonstrates a common ActionScript 3 error: `1061: Call to a possibly undefined method`.  The error occurs when attempting to access a property or call a method of an object that has not been properly initialized or might be null.

The `bug.as` file contains the problematic code.  The `bugSolution.as` file provides a corrected version.

## Problem

The issue arises from calling `trace(myVariable)` without ensuring `myVariable` is defined and properly initialized.

## Solution

The solution involves adding a check to verify `myVariable` exists before accessing it.  This prevents the error and allows the code to execute gracefully, even if `myVariable` is null or undefined.