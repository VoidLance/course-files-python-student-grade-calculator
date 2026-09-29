# Student Grade Calculator

A small Python learning project that calculates an average from a predefined list of test scores, assigns a grade, and demonstrates several Python operators.

## Features

- Calculates the average using floor division.
- Assigns a grade and adds a `+` when the average's ones digit is at least 5.
- Prompts you to search for a score in the list.
- Demonstrates object identity and bitwise AND/OR operations.

The score list and grading rules are defined in the script. This is an introductory example, not a configurable or production grading tool.

## Getting started

### Requirements

- Python 3.6 or later
- No third-party packages

### Run the program

Clone the repository, change into its directory, and run:

```bash
python3 "Student Grade Calculator.py"
```

When prompted, enter an integer score to search for. For the scores currently in the script (`34, 60, 56, 95, 82`), the average is `65`. For example, entering `56` reports that the score is present and displays the resulting average and grade.

To try different scores or grading rules, edit the `scores` list or the grade conditions in `Student Grade Calculator.py`.

## Help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-python-student-grade-calculator/issues).

## Maintenance and contributions

The project is maintained in the [VoidLance repository](https://github.com/VoidLance/course-files-python-student-grade-calculator). Contributions are welcome: open an issue to discuss a change, or submit a pull request with a focused improvement.

There is no separate contribution guide or automated test suite in this repository. Run the script with Python to check your change.
