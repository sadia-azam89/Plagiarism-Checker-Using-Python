# Plagiarism-Checker-Using-Python
This project is a simple plagiarism checker implemented in Python. It compares the textual similarity between two files and outputs a similarity ratio that indicates how closely the contents match.

**How It Works **
The program uses Python’s built-in difflib library, specifically the SequenceMatcher class, to measure similarity between two text files.

**Step-by-step process: **
Reads the contents of two text files (demo1.txt and demo2.txt).
Normalizes the text by converting it to lowercase and removing extra spaces.
Compares both texts character by character.
Calculates a similarity score between 0 and 1.
Displays the similarity as a percentage and flags high similarity.
