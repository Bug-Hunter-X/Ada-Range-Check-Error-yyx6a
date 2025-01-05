# Ada Range Check Bug

This repository demonstrates a common error in Ada programming: an incorrect range check.  The `Check_Range` function incorrectly determines whether an integer falls within a specified range, leading to a logical error in the program's execution.

The `bug.ada` file contains the erroneous code.  The corrected code is in `bugSolution.ada`

**To reproduce:** Compile and run `bug.ada`.  The output will incorrectly indicate that the number 15 is within the range of 1 to 10.

**Solution:** The solution corrects the range check within the `Check_Range` function to accurately determine if a number falls within the desired range.