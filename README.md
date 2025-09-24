# PythonBasics

This project is a collection of beginner-to-intermediate Python exercises. They cover different aspects of Python language

What’s Inside
1. Working with Lists

Functions that filter, transform, and reshape lists.

Examples:

- extract_and_apply(l, p, f) – filter elements with a condition and apply a function.

- concatenate(seqs) – flatten nested sequences.

- transpose(matrix) – compute the transpose of a matrix.

2. Sequence Slicing

Simple functions using Python slicing:

- copy(seq) – shallow copy.

- all_but_last(seq) – drop the last element.

- every_other(seq) – take every second element.

3. Combinatorial Algorithms

- Generator-based algorithms:

- prefixes(seq) and suffixes(seq) – all prefixes/suffixes of a sequence.

- slices(seq) – all non-empty slices.

4. Text Processing

String utilities for preprocessing:

- normalize(text) – clean up whitespace and lowercase.

- no_vowels(text) – remove vowels.

- digits_to_words(text) – convert digits into words.

- to_mixed_case(name) – convert snake_case → mixedCase.

5. DataFrames (pandas practice)

Read and manipulate CSV files with pandas.

Key tasks:

- Load a file: read_file(file).

- Work with worker IDs and timestamps.

- Compute how much time workers spent on tasks.

- Compare “naive” vs. “corrected” work times.

Bonus: analyze and wrangle a Wikipedia dataset on 2010 films.
