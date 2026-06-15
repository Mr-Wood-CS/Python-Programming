# :material-language-python: Python Outputs, Inputs and Variables

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
          <li>Learn how to display outputs in Python.</li>
          <li>Learn how to collect inputs from the user.</li>
          <li>Understand how variables store data in a program.</li>
          <li>Build simple Python programs using outputs, inputs and variables.</li>
        </ul>
      </td>
      <td>
        <p>By the end of this lesson you will be able to:</p>
        <ul>
          <li>Use <code>print()</code> to display messages.</li>
          <li>Use <code>input()</code> to ask the user questions.</li>
          <li>Store information in variables.</li>
          <li>Create a simple Python program using inputs and outputs.</li>
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
      <td>Output</td>
      <td>Information displayed by a program.</td>
    </tr>
    <tr>
      <td>Input</td>
      <td>Information sent from the user to the computer.</td>
    </tr>
    <tr>
      <td>Variable</td>
      <td>A named storage place for data in a program.</td>
    </tr>
    <tr>
      <td>Value</td>
      <td>The data stored inside a variable.</td>
    </tr>
  </tbody>
</table>

---

## :material-language-python: What is Python?

Python is a powerful programming language.

It is used to create:

- Games
- Websites
- Apps
- Data tools
- Artificial intelligence programs


Python is popular because it is easier to read than many other programming languages.

In this lesson, you will use Python to:

- Display outputs using `print()`
- Ask the user questions using `input()`
- Store answers in variables

---

## :material-monitor: What is an Output?

An output is information displayed by the computer.

Programs use outputs to show messages, instructions, answers and results.

In Python, we display outputs using `print()`.

Example:

```python
print("Hello World")
```

This program displays the words:

```text
Hello World
```

---

## :material-format-list-checks: Task One

!!! question "Start at Level 1 and go as far as you can!"

    === "Level 1"

        In Thonny, type the following lines of code:

        ```python
        print("Hello World")
        print("My name is ____")
        print("I enjoy Computing Science")
        ```

    === "Level 2"

        Create your own program that displays:

        - Your favourite game
        - Your favourite food
        - A message to your class

    === "Level 3"

        Create a program that displays:

        - A title
        - Three different messages
        - A blank line between sections

    === "Level 4"

        Create a welcome screen for a game.

        Your welcome screen must include:

        - A title
        - Instructions using multiple `print()` statements

---

## :material-keyboard: What is an Input?

An input is information sent from the user to the computer.

Programs often need information from the user to work properly.

Examples of inputs:

- Typing on a keyboard
- Clicking a mouse
- Speaking into a microphone
- Tapping a touchscreen

In Python, we ask for inputs using `input()`.

Example:

```python
input("What is your name? ")
```

This program:

1. Displays a question.
2. Waits for the user to type an answer.

---

## :material-variable: What is a Variable?

A variable is a named storage place used to store data in a program.

Programs use variables to remember information.

Examples of information a program might store:

- A player score in a game
- A username
- A password
- A high score

Example:

```python
name = "Mr Wood"
```

In this program:

| Part | Meaning |
|-----------|-----------|
| `name` | The variable name |
| `"Mr Wood"` | The value being stored |


You can think of a variable like a labelled box that stores information.

```text
Variable Name: name

┌────────────┐
│ Mr Wood    │
└────────────┘
```

The label on the box is the variable name and the information inside the box is the value.

!!! warning "Common Mistakes"

    * Forgetting speech marks around text.
    * Misspelling a variable name.
    * Using a different variable name in `print()` than the one used to store the value.
    * Forgetting brackets after `print()` or `input()`.

---

## :material-call-merge: Combining Inputs and Variables

Inputs become much more useful when we store them in variables.

Example:

```python
name = input("What is your name? ")
print(name)
```

**What Happens Here?**

1. Python asks the user a question.
2. The user types an answer.
3. The answer is stored in the variable called `name`.
4. The program displays the stored answer.

Programs become much more useful when we combine:

- Inputs
- Variables
- Outputs

---

## :material-lightbulb-on: Worked Example

Create a program that asks for the user's name and displays a greeting.

```python
name = input("What is your name? ")

print("Hello", name)
```

**Step-by-Step**

1. The program asks the user for their name.
2. The answer is stored in the variable called `name`.
3. The program displays a greeting.
4. The stored name is displayed as part of the output.

---

## :material-format-list-checks: Task Two

!!! question "Start at Level 1 and go as far as you can!"

    === "Level 1"

        Write a program that asks the user for their name.

    === "Level 2"

        Write a program that asks a user for:

        - Their name
        - Their favourite colour

    === "Level 3"

        Write a program that asks a user for:

        - Their name
        - Their favourite colour

        Then display both answers.

    === "Level 4"

        Create a small interview program.

        Ask at least four questions and display all answers.

---

## :material-clipboard-check-outline: Reflection

Before moving on, make sure you can:

- Explain the difference between an output, input and variable.
- Use `print()` to display information.
- Use `input()` to ask a question.
- Store user input in a variable.
- Combine inputs, variables and outputs in one program.
