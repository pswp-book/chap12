# Problem Solving with Python — Chapter 12: Divide and Conquer

This repository contains the chapter and active-learning exercise code associated with this chapter in the book *Problem Solving with Python: Using Computational Thinking in Everyday Life* by Michael D. Smith (2026), which is available from [MIT Press](https://mitpress.mit.edu/9780262383677/problem-solving-with-python/) and [Amazon](https://www.amazon.com/Problem-Solving-Python-Computational-Thinking/dp/0262552841/).

## Getting started

You will need:

- an integrated development environment (IDE)
- Python 3.10 or newer
- `pip` (usually included with Python)

If you need help getting started with an IDE, please read [my short introduction to "Understanding and Selecting an IDE"](https://ctps.io/select_ide.html).

## Cloning this repository

If you're using GitHub Codespaces, click the green "Code" button on this repo's page, select the tab "Codespaces," and click the "Create codespace on main."

Otherwise, in your IDE's terminal window, type the following commands:

```bash
git clone https://github.com/pswp-book/chap12.git
cd chap12
```

## (Optional) Create and activate a virtual environment

```bash
python -m venv .venv
# Windows
.\.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate
```

## Install dependencies

```bash
pip install -r requirements.txt
```

If there is no file `requirements.txt`, the code in this repository uses only the Python standard library.

## Reporting issues

If you find a problem in this chapter’s code (typo, bug, or mismatch with the book):

1.  Check the issues for this repo to see if it’s already reported.

2.  Open a new issue and include:
    *   The chapter number and section title (e.g., “Chapter 5, The game loop”)
    *   The filename, line number(s), and a short description of the problem.
    *   If something's wrong with the code's execution, please describe how you ran the program and the exeuction result.

## Short description of the repo's files

`unsort.py`: A module to import that makes it easy to create
and unsort a collection of three different lists.

`sorting.py`: Examples illustrating how you can use the two
sorting primitives in Python.

`sorting_names.py`: An answer to one of the You-Try-It exercises
in this chapter.

`insertion_sort.py`: An implementation of insertion sort.

`guess.py`: Basically `chap05/guess32.py`, where you guess the
computer's secret number.

`guesses.py`: A game in which the computer guesses your secret
number using binary search.

`merge.py`: A merge function that works with lists. It includes
test cases involving lists of integers.

`imerge_sort.py`: An iterative implementation of merge sort.

`merge_sort.py`: A recursive implementation of merge sort.

`factorial.py`: A recursive implementation of factorial.

`ffactorial.py`: An iterative implementation of factorial using
a for-statement.

`wfactorial.py`: An iterative implementation of factorial using
a while-statement.

`beckett0.py`: A solution to Beckett's challenge with no actors.

`beckett1.py`: A solution to Beckett's challenge with 0 or 1 actors.

`beckett32.py`: A complete solution to Beckett's challenge.

`ale01`: Folder with files for ALE 12.1 in textbook.

`ale02.py`: Script used in ALE 12.2 in textbook.

`ale03.py`: Script used in ALE 12.3 in textbook.
