# Lab Reflection: Unit 8 Lab 1 - Git Version Control + Debugging (BuggyProgram)

## Student Name
Harrison 

## GitHub Repository URL
Paste your GitHub repository URL here.
https://github.com/hlondeen/unit8_lab1
---

# Commit 1: Initial Commit

## What did you include in this commit?
- What the directions said....

## What was the purpose of this commit?
- 
create a baseline.
---

# Commit 2: Task 1 (getGrade)

## Which tests in Task1Test were failing before your fix?
-
java.lang.ArrayIndexOutOfBoundsException: Index 0 out of bounds for length 0
at BuggyProgram.sumEvenNumbers(BuggyProgram.java:21)
at Task2Test.testEmpty(Task2Test.java:21)
at java.base/java.lang.reflect.Method.invoke(Method.java:565)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)

## What was the issue in the code?
-
swapped lables and wrong > // >=

## What change did you make to fix it?
-
fixed the labels and added >=
## How did the tests help guide your fix?
-
Always
---

# Commit 3: Task 2 (sumEvenNumbers)

## Which tests in Task2Test were failing before your fix?
-
java.lang.ArrayIndexOutOfBoundsException: Index 0 out of bounds for length 0
at BuggyProgram.sumEvenNumbers(BuggyProgram.java:21)
at Task2Test.testEmpty(Task2Test.java:21)
at java.base/java.lang.reflect.Method.invoke(Method.java:565)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)



java.lang.ArrayIndexOutOfBoundsException: Index 3 out of bounds for length 3
at BuggyProgram.sumEvenNumbers(BuggyProgram.java:21)
at Task2Test.testOddNumbers(Task2Test.java:15)
at java.base/java.lang.reflect.Method.invoke(Method.java:565)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)

java.lang.ArrayIndexOutOfBoundsException: Index 4 out of bounds for length 4
at BuggyProgram.sumEvenNumbers(BuggyProgram.java:21)
at Task2Test.testSumEvenNumbers(Task2Test.java:9)
at java.base/java.lang.reflect.Method.invoke(Method.java:565)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)
at java.base/java.util.ArrayList.forEach(ArrayList.java:1604)

## What was the issue in the code?
-
sum at 1 not 0, <= instead of <
## What change did you make to fix it?
-
sum = 0, swapped <= to <
## How did the tests help guide your fix?
-
tell ya what function to look at
---

# Commit 4: Task 3 (sumRange)

## Which tests in Task3Test were failing before your fix?
-

## What was the issue in the code?
-

## What change did you make to fix it?
-

## How did the tests help guide your fix?
-

---

# Overall Reflection

## Which task was the easiest to fix? Why?
-

## Which task was the most difficult? Why?
-

## How did Git help you track your progress through the debugging process?
-

## Why is it important to make small, frequent commits when debugging code?
-

## What did you learn about using JUnit tests to guide debugging?
-

---

# Commit 5: Final Reflection

## What did you complete or update before making this final commit?
-

## Why is it useful to document your work after completing a programming task?
-