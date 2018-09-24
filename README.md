# Tut-03

## WHAT WE'RE DOING

Getting practice with

- relational operators
- logical operators
- Boolean variables

---

## GET READY

1. Get on INS
1. Make a directory `tut-03`
1. Inside that directory, make a file `LogicalPractice.java`
1. Follow the steps in the next section to get the "plumbing" in place for this practice

---

## GETTING THE PLUMBING TOGETHER

1. Create the usual boilerplate code (**class**, **main**, **run**). You can look at one of the REPL drills (like `lab-02 : sentence shifter`) if you need a reminder.
1. Make a **private** method called `displayWhetherCorrect`:
   1. It takes in an **int** and two **Booleans**
   1. When called, it displays the following message to the console: `number [x] matches my expectations: [true/false]`
      - In this message `[x]` is the integer passed in, while `[true/false]` will display `true` if the two Boolean inputs match and false otherwise
      - For example, `displayWhetherCorrect(4, true, true)` would display `number 4 matches my expectations: true`; `displayWhetherCorrect(10, false, true)` would display `number 10 matches my expectations: false`

---

## PRACTICE: RELATIONAL OPERATORS, LOGICAL OPERATORS, BOOLEAN VARIABLES

In this practice, you will be writing code that uses relational operators, logical operators and Boolean variables. You will also be checking whether you're able to evaluate logical statements correctly in your head or not.

1. Create 8 constants, 2 each of **int**, **double**, **char**, and **String**. Name them however you like and give them whatever values you want. Follow Java conventions.

All remaining code that you do from this point should be in your **run**.

1. Initialize 4 variables, 1 each of **int**, **double**, **char**, and **String**. Name them however you like and give them whatever values you want. Follow Java conventions.
1. Declare 12 Boolean variables `num01` through `num12`.
   - Initialize each of these variables with a logical expression that uses your constants, int/double/char/String variables, or literals. For example, `boolean num01 = numEggs > MAX_EGG_LIMIT` or `boolean num10 = SAFE_WORD.charAt(2) == 'a' && firstChoice != BAD_CHOICE`
   - You must use all 6 Java comparison operators and the 3 main Java logical operators (&&, ||, !) at least once in your work.
1. For each Boolean variable, figure out in your head what the result **should** be. Write it in a comment next to the variable.
1. Call `displayWhetherCorrect` for each Boolean variable to check whether you were correct.

For example, let's say I have the following, and assume that I initialized `numEggs` with 3 and `MAX_EGG_LIMIT` with 7:

<pre>
boolean num01 = numEggs > MAX_EGG_LIMIT; // my guess: false
</pre>

Then I can check my work like by calling

<pre>
displayWhetherCorrect(1, num01, false);
</pre>

And it should display the following to the console:

<pre>
number 10 matches my expectations: true
</pre>

How many did you get correct? If you got any wrong, do you see what went wrong?

---

## SUBMIT

Please submit the `tut-03` folder as **tut03** using `submit1501`.

---

## YOUR SKILL DRILLS

Do the following drills on REPL.IT:

- tut-03 : Knowitall-5000

**Remember**: this is due October 2 @ 9:00am
