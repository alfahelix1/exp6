##1. Aim

To implement various decision-making programs using conditional statements such as if, elif, and else in Python and to understand logical evaluation in different real-life problems.

## 2. Functions Used

- print() – To display output
- input() – To take input from the user
- int() – To convert input into integer
- float() – To convert input into float
- split() – To separate date values
- Arithmetic operators (+, -, *, /, %)
- Logical operators (and, or, not)
- Conditional statements (if, elif, else)

## 3. Theory

Decision-making statements in Python allow execution of specific blocks of code based on conditions. The if statement evaluates a condition and executes the block if it is true. The elif statement checks multiple conditions sequentially. The else statement executes when all conditions fail.
These programs demonstrate practical applications of conditional logic such as number classification, grading systems, salary calculation, tax calculation, and date validation.

## 4. Algorithms (Problem-wise)

### 1) Check Whether a Number is Positive, Negative or Zero

Algorithm:
1. Start
2. Input a number
3. If number > 0, print Positive
4. Else if number < 0, print Negative
5. Else print Zero
6. Stop

### 2): Check Whether a Number is Even or Odd

Algorithm:
1. Start
2. Input a number
3. If number % 2 equals 0, print Even
4. Else print Odd
5. Stop

### 3): Identify the Largest Number Among Three Numbers

Algorithm:
1. Start
2. Input three numbers a, b, and c
3. Compare a with b and c
4. If a is greater than both, print a
5. Else compare remaining numbers
6. Print the largest number
7. Stop

### 4): Calculate Grade Based on Marks

Algorithm:
1. Start
2. Input marks
3. If marks >= 90, print A Grade
4. Else if marks >= 75, print B Grade
5. Else if marks >= 60, print C Grade
6. Else if marks >= 40, print D Grade
7. Else print F Grade
8. Stop
   
### 5): Calculate Average of Three Subjects and Grade

Algorithm:
1. Start
2. Input marks of three subjects
3. Calculate average
4. Display average
5. Apply grading conditions based on average
6. Print grade
7. Stop

### 6): Check Whether a Year is a Leap Year

Algorithm:
1. Start
2. Input year
3. If year divisible by 400, it is leap year
4. Else if year divisible by 4 and not divisible by 100, it is leap year
5. Else it is not leap year
6. Stop

### 7): Increment a Given Date

Algorithm:
1. Start
2. Input day, month, year
3. Check whether year is leap year
4. Determine maximum days in the given month
5. Increment day by 1
6. If day exceeds maximum days:
   - Set day = 1
   - Increment month
7. If month exceeds 12:
   - Set month = 1
   - Increment year
8. Print incremented date
9. Stop

### 8): Check Whether a Character is Vowel or Consonant

Algorithm:
1. Start
2. Input a character
3. If character is in (a, e, i, o, u) in upper or lower case
4. Print Vowel
5. Else print Consonant
6. Stop

### Problem 1: Calculate Gross Salary of an Employee

Algorithm:
1. Start
2. Input basic salary
3. If basic <= 10000:
      HRA = 20% and DA = 80%
4. Else if basic <= 20000:
      HRA = 25% and DA = 90%
5. Else:
      HRA = 30% and DA = 95%
6. Calculate gross salary = basic + HRA + DA
7. Print gross salary
8. Stop

### Problem 2: Calculate Income Tax Based on Annual Income

Algorithm:
1. Start
2. Input annual income
3. If income <= 2,50,000:
      Tax = 0
4. Else if income <= 5,00,000:
      Tax = 5% of taxable amount
5. Else if income <= 10,00,000:
      Tax = previous slab tax + 20% of remaining income
6. Else:
      Tax = previous slab tax + 30% of remaining income
7. Print income tax
8. Stop

### Problem 3: Check Whether a Date is Valid and Print Incremented Date

Algorithm:
1. Start
2. Input date in dd/mm/yyyy format
3. Separate day, month, and year
4. Determine maximum days in month
5. Check if month is valid
6. Check if day is valid
7. If invalid, print Date is invalid
8. Else increment the date
9. Print incremented date
10. Stop

## 5. Conclusion
All the decision-making programs were successfully implemented using conditional statements in Python. The experiment helped in understanding logical operations, real-life problem solving, and structured programming techniques. The objectives of the experiment were achieved successfully.
