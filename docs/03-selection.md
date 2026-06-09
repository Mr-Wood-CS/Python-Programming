# :material-language-python: Python Selection

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
          <li>Remember how inputs, outputs, variables and data types are used in Python.</li>
          <li>Understand how programs make decisions.</li>
          <li>Learn how to use selection with <code>if</code> and <code>else</code>.</li>
          <li>Use comparison operators to test conditions.</li>
        </ul>
      </td>
      <td>
        <p>By the end of this lesson you will be able to:</p>
        <ul>
          <li>Write a program that makes a decision.</li>
          <li>Use <code>if</code> and <code>else</code> correctly.</li>
          <li>Convert user input into an integer before comparing numbers.</li>
          <li>Indent code correctly inside selection statements.</li>
          <li>Use comparison operators such as <code>&gt;</code>, <code>&lt;</code> and <code>==</code>.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

## :material-key-variant: Today's Keywords

<table class="keywords-table">
  <thead>
    <tr>
      <th>Keyword</th>
      <th>Meaning</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Selection</td>
      <td>A control structure that allows a program to make a decision.</td>
    </tr>
    <tr>
      <td>Condition</td>
      <td>A test that can be either true or false.</td>
    </tr>
    <tr>
      <td>If</td>
      <td>Runs code only when a condition is true.</td>
    </tr>
    <tr>
      <td>Else</td>
      <td>Runs code when the <code>if</code> condition is false.</td>
    </tr>
    <tr>
      <td>Comparison Operator</td>
      <td>A symbol used to compare two values.</td>
    </tr>
    <tr>
      <td>Indentation</td>
      <td>Spaces at the start of a line that show which code belongs inside a statement.</td>
    </tr>
  </tbody>
</table>

---

## :material-source-branch: What is Selection?

Selection is when a program makes a decision.

Programs often need to choose what to do next based on information they have been given.

Examples of selection:

- If a player has no lives left, end the game.
- If a password is correct, allow the user to log in.
- If a customer is old enough, allow them to buy a ticket.
- If a score is high enough, display a pass message.

In Python, selection is written using `if` and `else`.

---

## :material-ray-start-arrow: A Simple If Statement

An `if` statement checks a condition.

If the condition is true, the indented code runs.

```python
age = 15

if age > 12:
    print("You can watch this film")
```

**What Happens Here?**

1. The variable `age` stores the value `15`.
2. Python checks if `age > 12`.
3. The condition is true.
4. The message is displayed.

---

## :material-call-split: If and Else

An `else` statement gives the program another option.

The `else` code runs when the `if` condition is false.

```python
age = 10

if age > 12:
    print("You can watch this film")
else:
    print("You are not old enough")
```

**What Happens Here?**

1. Python checks if `age > 12`.
2. The condition is false because `10` is not greater than `12`.
3. The code inside `else` runs instead.

---

## :material-compare-horizontal: Comparison Operators

Comparison operators are used to compare values.

| Operator | Meaning | Example |
|-----------|-----------|-----------|
| `>` | Greater than | `age > 17` |
| `<` | Less than | `score < 50` |
| `==` | Equal to | `answer == "yes"` |
| `>=` | Greater than or equal to | `age >= 18` |
| `<=` | Less than or equal to | `score <= 100` |
| `!=` | Not equal to | `password != "python"` |

!!! warning "Important"

    Use one equals sign to store a value:

    ```python
    name = "Alex"
    ```

    Use two equals signs to compare values:

    ```python
    if name == "Alex":
        print("Welcome Alex")
    ```

---

## :material-format-indent-increase: Indentation and Colons

Python uses indentation to show which lines belong inside an `if` or `else` statement.

A colon `:` is needed at the end of the `if` and `else` lines.

```python
age = int(input("What is your age? "))

if age > 17:
    print("You are old enough")
else:
    print("You are not old enough")
```

The indented lines are the instructions that run after the decision has been made.

---

## :material-lightbulb-on: Worked Example

Create a virtual barman program.

The program should ask the user for their age.

If the user is over 17, the program should display:

```text
What can I get you?
```

Otherwise, the program should display:

```text
You are not old enough.
```

```python
age = int(input("What is your age? "))

if age > 17:
    print("What can I get you?")
else:
    print("You are not old enough.")
```

**Step-by-Step**

1. The program asks the user for their age.
2. `int()` converts the input into an integer.
3. Python checks if the age is greater than `17`.
4. If the condition is true, the first message is displayed.
5. If the condition is false, the `else` message is displayed.

---

## :material-format-list-checks: Programming Tasks

!!! question "Start at Level 1 and go as far as you can!"
    === "Level 1"

        **Task 1**

        Ask the user for their age.

        If their age is greater than `10`, display:

        ```text
        You are older than 10.
        ```

        **Task 2**

        Ask the user for a number.

        If the number is greater than `100`, display:

        ```text
        That is a big number.
        ```

    === "Level 2"

        **Task 3**

        Create a virtual barman program.

        Ask the user for their age.

        If they are over `17`, display:

        ```text
        What can I get you?
        ```

        Otherwise, display:

        ```text
        You are not old enough.
        ```

        **Task 4**

        Ask the user for a test score.

        If the score is greater than or equal to `50`, display:

        ```text
        You passed.
        ```

        Otherwise, display:

        ```text
        Try again next time.
        ```

    === "Level 3"

        **Task 5**

        Ask the user for a password.

        If the password is equal to `python`, display:

        ```text
        Access granted.
        ```

        Otherwise, display:

        ```text
        Access denied.
        ```

        **Task 6**

        Ask the user for their name.

        If their name is equal to your name, display:

        ```text
        We have the same name.
        ```

        Otherwise, display a greeting using their name.

    === "Level 4"

        **Task 7**

        Create a cinema age checker.

        Ask the user for their age.

        If they are greater than or equal to `15`, display:

        ```text
        You can watch this film.
        ```

        Otherwise, display:

        ```text
        You are too young for this film.
        ```

        **Task 8**

        Ask the user for a number.

        If the number is less than `0`, display:

        ```text
        This is a negative number.
        ```

        Otherwise, display:

        ```text
        This is zero or a positive number.
        ```

    === "Challenge"

        Create a simple quiz question.

        Your program should:

        - Ask the user a question.
        - Store their answer in a variable.
        - Use selection to check whether the answer is correct.
        - Display a correct or incorrect message.
        - Use a comment to explain what your `if` statement does.

---

## :material-clipboard-check-outline: Reflection

Before moving on, make sure you can:

- Explain what selection means.
- Use `if` and `else` in a Python program.
- Convert input into an integer using `int()`.
- Use comparison operators correctly.
- Explain why indentation and colons are important in selection.
