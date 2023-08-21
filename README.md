# Manual-Testing-02
# Test Cases Of Dice Testing

## Overview

This README provides a detailed description of the test cases for the dice-rolling application. The application's purpose is to simulate rolling a standard six-sided dice and generating random outcomes. This set of test cases covers various scenarios to ensure the correctness and reliability of the application's functionality.

## Test Cases

### Case 1: Single Roll

**Description:** Test a single roll of the dice to ensure random generation.

**Input:** N/A

**Expected Result:** Random number between 1 and 6.

**Actual Result:** 3

**Pass/Fail Status:** Pass

### Case 2: Single Roll

**Description:** Test another single roll of the dice.

**Input:** N/A

**Expected Result:** Random number between 1 and 6.

**Actual Result:** 6

**Pass/Fail Status:** Pass

### Case 3: Single Roll

**Description:** Test one more single roll of the dice.

**Input:** N/A

**Expected Result:** Random number between 1 and 6.

**Actual Result:** 1

**Pass/Fail Status:** Pass

### Case 4: Invalid Roll (0)

**Description:** Test rolling a dice with an invalid input (0).

**Input:** Input: 0

**Expected Result:** Error message: "Invalid input"

**Actual Result:** Error message: "Invalid input"

**Pass/Fail Status:** Pass

### Case 5: Invalid Roll (7)

**Description:** Test rolling a dice with an invalid input (7).

**Input:** Input: 7

**Expected Result:** Error message: "Invalid input"

**Actual Result:** Error message: "Invalid input"

**Pass/Fail Status:** Pass

### Case 6: Multiple Rolls

**Description:** Test rolling the dice multiple times and capturing the outcomes.

**Input:** Number of rolls: 5

**Expected Result:** List of random numbers between 1 and 6

**Actual Result:** [4, 2, 5, 1, 6]

**Pass/Fail Status:** Pass

### Case 7: Large Number of Rolls

**Description:** Test rolling the dice a large number of times and capturing outcomes.

**Input:** Number of rolls: 20

**Expected Result:** List of random numbers between 1 and 6

**Actual Result:** [3, 6, 2, 5, ...]

**Pass/Fail Status:** Pass

### Case 8: Performance Test (1000 Rolls)

**Description:** Test the performance of rolling the dice 1000 times.

**Input:** Number of rolls: 1000

**Expected Result:** List of 1000 random numbers between 1 and 6

**Actual Result:** List of 1000 random numbers between 1 and 6

**Pass/Fail Status:** Pass

### Case 9: Performance Test (10000 Rolls)

**Description:** Test the performance of rolling the dice 10000 times.

**Input:** Number of rolls: 10000

**Expected Result:** List of 10000 random numbers between 1 and 6

**Actual Result:** List of 10000 random numbers between 1 and 6

**Pass/Fail Status:** Pass

### Case 10: Performance Test (100000 Rolls)

**Description:** Test the performance of rolling the dice 100000 times.

**Input:** Number of rolls: 100000

**Expected Result:** List of 100000 random numbers between 1 and 6

**Actual Result:** List of 100000 random numbers between 1 and 6

**Pass/Fail Status:** Pass

## Conclusion

The above test cases provide comprehensive coverage of the dice-rolling application's functionality. By testing various scenarios, including single rolls, invalid inputs, multiple rolls, and performance tests, we ensure that the application performs as expected. Each test case's expected and actual results have been compared, resulting in a "Pass" for each case, indicating the successful validation of the application's functionality.

