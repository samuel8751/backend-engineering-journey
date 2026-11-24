# Day 1 — JavaScript Knowledge Check and Coding Challenges

**Week:** 1 — JavaScript Foundations  
**Date:** November 24, 2026  
**Topics:** Variables, data types, operators, conditions, and loops  
**Rule:** Attempt every question before checking external solutions. Explain your reasoning in your own words.

---

## Part A — Concept questions

Answer in your own words. Use a short code example where requested.

1. What is a variable, and why do programs need variables?
2. Explain the difference between `let` and `const`. Give one appropriate use case for each.
3. What happens if you try to reassign a variable declared with `const`?
4. Explain the difference between a string, number, and boolean. Give an example of each.
5. What is the difference between `null` and `undefined`?
6. What is the difference between `=`, `==`, and `===`?
7. What does the modulo operator (`%`) return? Give a practical example.
8. Explain the purpose of an `if...else` statement.
9. What is a loop? Describe one situation in a Student Information System where a loop would be useful.
10. What is the difference between a `for` loop and a `while` loop?
11. What is an infinite loop, and how can a programmer prevent one?
12. Predict the output below and explain why:

```javascript
let score = 45;
score = score + 10;

if (score >= 50) {
    console.log("Pass");
} else {
    console.log("Fail");
}
```

---

## Part B — Coding challenges

Create a separate file named `day-01-challenges.js` and complete these challenges.

### Challenge 1 — Student profile
Declare variables for a student:
- Full name
- Admission number
- Age
- Course
- Whether the student is currently active

Print a readable student profile to the console. Choose suitable data types and use `const` or `let) appropriately.

### Challenge 2 — Examination calculator
Store marks for Mathematics, English, and Computer Studies.
- Calculate the total.
- Calculate the average.
- Print the total and average.
- Print "Pass" if the average is at least 50; otherwise print "Fail".

Do not hardcode the total or average.

### Challenge 3 — Even or odd
Create a variable containing an integer.
Use the modulo operator and a conditional statement to determine whether the number is even or odd.
Test at least four different numbers, including zero.

### Challenge 4 — Student fee balance
Create variables for:
- Total fees required
- Amount already paid

Calculate the outstanding balance. Then print:
- "Fees cleared" if the balance is zero or less.
- "Partially paid" if some amount is still outstanding.
- "No payment made" if the amount paid is zero.

Test your program with at least three different payment situations.

### Challenge 5 — Count and total
Use a `for` loop to:
1. Print numbers from 1 to 20.
2. Calculate the sum of numbers from 1 to 20.
3. Print the final sum.

Then modify your program to calculate the sum from 1 to a different ending number.

### Challenge 6 — Multiplication table
Store a number in a variable. Use a loop to print its multiplication table from 1 to 12.
For example, if the number is 5, print results such as `5 x 1 = 5`.

---

## Part C — Debugging challenge

The following code contains mistakes. Do not simply rewrite it. Identify each mistake, explain why it is a problem, and then correct it.

```javascript
const studentName = "Mary";
studentName = "Mary Wanjiku";

let age = "20";

if (age = 18) {
    console.log("Adult");
} else {
    console.log("Not an adult");
}

for (let i = 1; i <= 5; i--) {
    console.log(i);
}
```

Questions:
1. Which line causes a reassignment problem?
2. Is the age stored using the most suitable data type?
3. What is wrong with the condition inside the `if` statement?
4. Why is the loop unsafe? What would happen when it runs?
5. Provide a corrected version and explain every change.

---

## Part D — Explain your code

After completing the challenges, answer these reflection questions:

1. Which challenge took you the longest, and why?
2. Which error did you encounter? How did you locate and fix it?
3. Explain how your program calculates an average.
4. Explain how your loop knows when to stop.
5. Which concept can you now explain without referring to notes?
6. Which concept still needs practice?

---

## Submission checklist

- [ ] Answer all 12 concept questions in `day-01-answers.md`.
- [ ] Complete all 6 coding challenges in `day-01-challenges.js`.
- [ ] Correct the debugging challenge and explain the mistakes.
- [ ] Run the code with different test values.
- [ ] Add comments where they clarify your reasoning.
- [ ] Commit your work with a meaningful commit message.

**Suggested commit message:** `Complete Day 1 JavaScript foundations challenges`

**Assessment standard:** Correct output matters, but so does your ability to explain your decisions, test edge cases, and debug independently. Do not copy a complete solution.
