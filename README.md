# LaTeX-Math-Homework-Template

A simple set of custom LaTeX commands and a template file for typesetting math homework

## Command Guides

```tex
\ruledtitle{}
```

Used to create specific sections for grouping similar types of problems or exercises that share a format or other prerequisite information.

```tex
\mathquestion{}
```

Adds a new question whose input is automatically formatted as math (No \[ \] needed).

```tex
\wordquestion{}
```

Adds a new question whose input is formatted as text.

```tex
\answer{}
```

Boxes input. Same as `\boxed{}` command. Only exists for better readability in the context of homework.

```tex
\questionpart{}
```

Same as `\wordquestion`. Used in nested enumerate environments for better readability.

```tex
\begin{amatrix}{2}
\end{amatrix}
```
Custom environment for augmented matrices. The argument denotes which column the constants are placed after.
