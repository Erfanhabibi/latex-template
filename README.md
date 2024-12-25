
# LaTeX Template for Mathematical Exercises and Reports

This LaTeX template is designed for writing mathematical exercises and reports, particularly for the Department of Mathematics and Computer Science at Amirkabir University of Technology. The template includes predefined sections and commands to streamline the writing process for students and researchers.

## Table of Contents

- [LaTeX Template for Mathematical Exercises and Reports](#latex-template-for-mathematical-exercises-and-reports)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
  - [Template Overview](#template-overview)
    - [Key Features:](#key-features)
  - [Setup Instructions](#setup-instructions)
  - [Writing Exercises and Solutions](#writing-exercises-and-solutions)
    - [Problem Environment](#problem-environment)
    - [Solution Environment](#solution-environment)
    - [Proof Environment](#proof-environment)
  - [Adding Programming Code](#adding-programming-code)
  - [Examples](#examples)
    - [Problem Example:](#problem-example)
    - [Solution Example:](#solution-example)
    - [Proof Example:](#proof-example)

## Getting Started

1. Clone or download the repository to your local machine.
2. Ensure that you have LaTeX installed on your system (e.g., TeX Live, MiKTeX, or Overleaf).
3. Open the template in your preferred LaTeX editor.
4. Compile the `main.tex` file to generate the PDF output.

## Template Overview

This template contains a variety of custom environments and commands to structure your mathematical exercises and solutions efficiently.

### Key Features:

- Customizable header for course, student, and instructor information.
- Predefined environments for exercises (`prob`), solutions (`sol`), proofs (`proof`), and custom environments (`customEnv`).
- Built-in code formatting for programming examples using `lstlisting`.

## Setup Instructions

Before using the template, edit the `configs.tex` file to personalize the details of your project:

1. **Your Name**: Update the `\myname` command with your name.
2. **Student ID**: Update the `\mystdID` command with your student ID.
3. **Course and Instructor Info**: Set the course name, semester, and instructor details in the relevant fields.
4. **Header Customization**: The header section of the document is automatically populated using the data in `configs.tex`.

## Writing Exercises and Solutions

### Problem Environment

To add a new exercise, use the `prob` environment:

```latex
\begin{prob}
    Write your problem here.
\end{prob}
```

### Solution Environment

To add the solution for an exercise, use the `sol` environment:

```latex
\begin{sol}
    Write your solution here.
\end{sol}
```

### Proof Environment

For mathematical proofs, use the `proof` environment:

```latex
\begin{proof}
    Write your proof here.
\end{proof}
```

## Adding Programming Code

To include programming code in your document, use the `lstlisting` environment. For example, here's how to display a Python function:

```latex
\begin{lstlisting}[language=Python]
def solve_integral():
    return 1 / 3
\end{lstlisting}
```

The code will be formatted with syntax highlighting for better readability.

## Examples

Below is an example of a mathematical problem, its solution, and the proof of the solution:

### Problem Example:

```latex
\begin{prob}
    Calculate the following integral:
    \[
        \int_{0}^{1} x^2 \, dx
    \]
\end{prob}
```

### Solution Example:

```latex
\begin{sol}
    The solution to this integral is computed using the formula:
    \[
        \int_{0}^{1} x^2 \, dx = \left[ \frac{x^3}{3} \right]_{0}^{1} = \frac{1}{3} - 0 = \frac{1}{3}
    \]
\end{sol}

```

### Proof Example:

```latex
\begin{proof}
    The proof follows directly from the standard rule for integrating power functions.
\end{proof}
```


