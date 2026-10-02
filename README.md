# Loops and Functions

This Jupyter notebook contains hands-on Python exercises on loops and functions. It demonstrates how to repeat tasks using while and for loops, control loop flow with break, continue and else, and write reusable code with functions.

## Concepts Used

### Importing Modules
The `import` statement brings in external code. Here, the `random` module is imported to generate random values.

### random.randint()
Returns a random integer between two given values, both inclusive. It is used to generate the secret number.

### Variables and Counters
A variable such as `attempts` stores the number of guesses remaining and is decreased after each valid guess to control the loop.

### User Input and Type Conversion
`input()` reads text from the user, and `int()` or `float()` converts it to a number so it can be compared or used in calculations.

### while Loop
Repeats a block of code as long as a condition is true. It is used to keep asking for guesses until the user succeeds or runs out of attempts.

### Comparison and Logical Operators
Operators such as `>`, `<`, `==` and `and` are used to check whether a guess is too high, too low, correct or out of range.

### if-elif-else Statements
Execute different blocks of code depending on which condition is true. They give the user the right feedback for each guess.

### continue Statement
Skips the rest of the current iteration and moves to the next one. It is used when the guess is out of range, so the attempt is not counted.

### break Statement
Exits the loop immediately. It is used to end the game when the guess is correct.

### else with while Loop
The `else` block runs only if the loop finishes without hitting `break`. It displays "Better luck next time!" when all attempts are used.

### for Loop
Iterates over a sequence of values. It is used to go through the numbers 1 to 10 for the multiplication table.

### range() Function
Generates a sequence of numbers. `range(1, 11)` produces 1 to 10, since the stop value is excluded.

### Arithmetic Operators
`*` multiplies, `/` divides and `**` raises to a power. These are used to compute products and the BMI formula.

### String Formatting (f-strings)
Embeds variables directly inside text, e.g. `f"{num} x {i} = {num * i}"`, to print results in a clean format.

### Functions
A reusable block of code defined with `def`. Functions take parameters, perform a task and send back a result.

### Parameters and Return Values
`calculate_bmi(weight, height)` receives weight and height as parameters and uses `return` to send the calculated BMI back to the caller.

### Rounding Output
`round(value, 2)` or the `:.2f` format limits the BMI to two decimal places.

### print() Function
Displays labelled output for readability.

## Running the Code

Open the notebook in Jupyter Notebook or JupyterLab and run the cells in order.

To run it from a terminal instead, execute the notebook with:

```bash
jupyter nbconvert --to notebook --execute "Python3.Loops_and_Functions.ipynb"
```
