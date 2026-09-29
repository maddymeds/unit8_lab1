# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Madelyn Aideloje

## GitHub Repository URL
https://github.com/maddymeds/unit8_lab1

---

# Commit 1: Initial Commit

## What did you include in this commit?
- The starter BuggyProgram.java file, JUnit test classes, README.md, and the project configuration files.

## What was the purpose of this commit?
- The purpose was to establish the starting project and set up the files needed for the lab.

---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
- The tests that checked the getGrade performance level boundaries were failing.

## What was the issue in the code?
- The conditional logic did not correctly handle the required score boundaries.

## What change did you make to fix it?
- I corrected the conditional statements so that scores are assigned to the correct performance level.

## How did the tests help guide your fix?
- The failing tests showed which score ranges were producing incorrect results, which helped me identify and correct the boundary conditions.

---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
- The tests that checked the sum of even numbers in an array were failing.

## What was the issue in the code?
- The loop did not correctly identify and add only the even numbers in the array.

## What change did you make to fix it?
- I corrected the loop logic so that only even numbers are added to the sum.

## How did the tests help guide your fix?
- The tests showed the expected sums for different arrays and helped me verify that the method was correctly handling even and off numbers.

---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
- The testSumRangeReverseOrder test was failing.

## What was the issue in the code?
- The loop did not correctly handle the range of values required by the tests.

## What change did you make to fix it?
- I corrected the loop so that it uses the correct starting and ending bounds when calculating the sum.

## How did the tests help guide your fix?
- The tests showed the expected results for different ranges, including the reverse order case, which helped me identify the problem with the loop bounds.

---

# Overall Reflection

## Which task was the easiest to fix? Why?
- Task 2 was the easiest to fix because the problem was straightforward once I identified that the method needed to add only even numbers.

## Which task was the most difficult? Why?
- Task 1 was the most difficult because I had to pay close attention to the score boundaries and conditional statements.

## How did Git help you track your progress through the debugging process?
- Git helped me track each change separately through commits. I could see the progress from the initial project through each task and push the changes to GitHub.

## Why is it important to make small, frequent commits when debugging code?
- Small, frequent commits make it easier to track changes, identify problems, and return to an earlier version if something goes wrong.

## What did you learn about using JUnit tests to guide debugging?
- I learned that JUnit tests can identify specific problems and help verify that changes produce the expected results.

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
- I completed Tasks 1, 2, and 3, verified that the JUnit tests passed, updated the README.md, and pushed my changes to GitHub.

## Why is it useful to document your work after completing a programming task?
- Documenting my work helps explain what I changed, why I made the changes, and what I learned from the process. It also makes the project easier to understand and review later.