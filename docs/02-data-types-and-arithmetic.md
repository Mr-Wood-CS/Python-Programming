# Python Data Types and Arithmetic

<table>
  <thead>
    <tr>
      <th>Learning Intention</th>
      <th>Success Criteria</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <ul>
          <li>Understand the difference between strings, integers and real numbers.</li>
          <li>Understand why computers need to know the type of data being stored.</li>
          <li>Learn how to convert data from one type to another.</li>
          <li>Use arithmetic operators to perform calculations in Python.</li>
        </ul>
      </td>
      <td>
        <p>By the end of this lesson you will be able to:</p>
        <ul>
          <li>Identify whether data is a string, integer or real number.</li>
          <li>Explain why data types are important.</li>
          <li>Convert user input into an integer or real number.</li>
          <li>Create Python programs that perform calculations.</li>
          <li>Solve programming challenges using arithmetic operators.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

## Today's Keywords

<table class="keywords-table">
  <thead>
    <tr>
      <th>Keyword</th>
      <th>Meaning</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data Type</td>
      <td>The kind of data being stored, such as text or a number.</td>
    </tr>
    <tr>
      <td>String</td>
      <td>Text that is surrounded by speech marks.</td>
    </tr>
    <tr>
      <td>Integer</td>
      <td>A whole number.</td>
    </tr>
    <tr>
      <td>Float</td>
      <td>A number that contains a decimal point.</td>
    </tr>
    <tr>
      <td>Arithmetic</td>
      <td>Using maths operations such as add, subtract, multiply and divide.</td>
    </tr>
    <tr>
      <td>Convert</td>
      <td>Change data from one type into another type.</td>
    </tr>
  </tbody>
</table>

---

## Comments

Comments are notes written by programmers.

Python ignores comments when the program runs.

```python
# This is a comment
```

Comments can be used to:

- Explain code.
- Leave reminders.
- Make programs easier to understand.

---

## What is a Data Type?

A data type tells the computer what kind of information is being stored.

Different types of data are stored and used in different ways.

<table>
  <thead>
    <tr>
      <th>Data Type</th>
      <th>Meaning</th>
      <th>Examples</th>
      <th>Python Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>String</td>
      <td>Text that must be surrounded by speech marks.</td>
      <td>
        <code>name = "Dave"</code><br>
        <code>favourite_game = "Minecraft"</code>
      </td>
      <td><code>str</code></td>
    </tr>
    <tr>
      <td>Integer</td>
      <td>A whole number that can be used in calculations.</td>
      <td>
        <code>age = 14</code><br>
        <code>score = 250</code>
      </td>
      <td><code>int</code></td>
    </tr>
    <tr>
      <td>Real Number</td>
      <td>A number that contains a decimal point.</td>
      <td>
        <code>height = 1.72</code><br>
        <code>price = 4.99</code>
      </td>
      <td><code>float</code></td>
    </tr>
  </tbody>
</table>

---

## Why Are Data Types Important?

Look at the following code:

```python
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")

answer = num1 + num2
print(answer)
```

If the user enters:

```text
10
20
```

The output will be:

```text
1020
```

This happens because Python treats inputs as strings.

Instead of adding the numbers together, it joins the text.

---

## Converting Data Types

We can convert data into an integer using int().

```python
num1 = int(input("Enter a number: "))
num2 = int(input("Enter another number: "))

answer = num1 + num2
print(answer)
```

Output:

```text
30
```

We can convert data into a real number using float().

```python
temperature = float(input("Enter a temperature: "))
```

---

# Arithmetic Operators

| Operator | Meaning | Example |
|-----------|-----------|-----------|
| + | Add | 5 + 2 = 7 |
| - | Subtract | 5 - 2 = 3 |
| * | Multiply | 5 * 2 = 10 |
| / | Divide | 5 / 2 = 2.5 |

---

## Worked Example

Create a program that asks for two numbers and displays the total.

```python
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

total = num1 + num2

print("The total is", total)
```

### Step-by-Step

1. The user enters two numbers.
2. int() converts the inputs into integers.
3. The numbers are added together.
4. The answer is stored in a variable called total.
5. The result is displayed.

---

# Programming Tasks

=== "Level 1"

    ### Task 1

    Ask the user for two whole numbers.

    Add the numbers together and display the answer.

    **Example output:** `The total is 15`

    ### Task 2

    Ask the user for two whole numbers.

    Subtract the second number from the first number and display the answer.

    **Example output:** `The difference is 4`

=== "Level 2"

    ### Task 3

    Ask the user for two whole numbers.

    Multiply the numbers together and display the answer.

    **Example output:** `The product is 24`

    ### Task 4

    Ask the user for two numbers.

    Divide the first number by the second number and display the answer.

    **Remember:** Use `float()` if the answer might include a decimal.

=== "Level 3"

    ### Task 5

    Ask the user for the length and width of a rectangle.

    Calculate and display the area.

    **Formula:** `Area = Length x Width`

    ### Task 6

    Ask the user for the price of an item and the quantity bought.

    Display the total cost.

    **Formula:** `Total cost = Price x Quantity`

=== "Level 4"

    ### Task 7

    Create a calculator that asks the user for two numbers.

    Calculate and display:

    - The total
    - The difference

    ### Task 8

    A cinema ticket costs £7.50.

    Ask the user how many tickets they would like.

    Calculate and display:

    - The ticket total
    - The final cost with a £1.50 booking fee added

=== "Challenge"

    A teacher enters three test scores.

    Ask the user to enter all three scores.

    Calculate and display:

    - Total score
    - Average score

    **Hint:** `Average = Total / 3`

---

## Reflection

Before moving on, make sure you can:

- Explain the difference between a string, integer and float.
- Convert inputs using int() and float().
- Use arithmetic operators correctly.
- Complete all Level 4 tasks independently.
