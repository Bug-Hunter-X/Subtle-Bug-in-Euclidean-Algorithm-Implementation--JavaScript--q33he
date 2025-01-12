# Subtle Bug in Euclidean Algorithm Implementation (JavaScript)

This repository demonstrates a subtle bug in a JavaScript implementation of the Euclidean algorithm for finding the greatest common divisor (GCD) of two non-negative integers. The bug manifests when one or both inputs are zero.

## Bug Description

The provided JavaScript function `myFunction` aims to calculate the GCD using recursion.  However, it contains a flaw in its handling of zero inputs, leading to incorrect results in some cases.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.js`.
3. Run the code. Observe the output for various input pairs, including cases with zero inputs.

## Solution

The solution is provided in `bugSolution.js`. This revised implementation correctly handles zero inputs, ensuring the accurate calculation of the GCD for all non-negative integer pairs.

## Learning Points

This example highlights the importance of thorough edge case testing.  Even seemingly straightforward algorithms can have unexpected behavior when edge cases (like zero inputs) are not explicitly considered and properly handled.