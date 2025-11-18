# Moving a Shape

The [Problem](#Problem)

The [Requirements](#Requirements)

The [Milestones](#Milestones)

The [main.c](.src/main.c)

[Changes](#Changes) made.

Assingment: https://c-programming.aydos.de/week10.html 

# Learning goals

- Open, close, read and write to a file

# Problem

Implement a program that filters people by age from a dataset.

Input data is a comma-separated values (CSV) file. If there is a row which does not contain two columns, then output an error message.

# Milestones

1. First begin by processing people-with-age.csv line by line. If you encounter a blank line, then warn the user, but continue processing by printing the non-blank lines.

```
./main.exe 15 people-with-age.csv
```

2. Parse one line into tokens and filter by age

3. Recognize the three different malformed lines

   1. Whole line missing
   2. Age missing (no token)
   3. Age not recognized (token cannot be converted to a number)

4. Support output to a file

```
./main.exe people-with-age.csv out.csv
```

5. Also support reading the input from stdin as follows:

```
"Anna, 12" | ./main.exe 15
```

# Requirements

- Deliver a very general flowchart where at least the line by line processing is visible, but not how each error is recognized.

# Flowchart

Flowchart : ![Flowchart](FlowChart.png)


# Example

<video controls src="example.mp4" title="Title"></video>


# Changes

none this time