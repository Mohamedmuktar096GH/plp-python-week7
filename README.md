# Week 7 Assignment: My Notes & The Report Builder

## Files in This Repository
* **`my_notes.py`** - Writes, appends, reads, and counts lines in a text file.
* **`my_notes.txt`** - The generated text file containing four notes.
* **`hubs.csv`** - The input CSV file storing learner names, hubs, and scores.
* **`report_builder.py`** - Reads learner data from the CSV file and generates a summary report.
* **`report.txt`** - The generated report showing total learners, pass/fail counts, and the average score.
* **`assignment_output.png`** - Screenshot showing the programs running in the terminal.

## Reflection: Changing `"a"` to `"w"` in Question 1
If you changed `"a"` (append mode) to `"w"` (write mode), Python would erase the first three notes and overwrite `my_notes.txt` with only `"I added this later"`. As a result, the final file would only have 1 line instead of 4.
