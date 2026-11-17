# Multi-Sequence GC Content Explorer

## Overview
The Multi-Sequence GC Content Explorer is a beginner-level bioinformatics project developed using Python. It analyzes multiple DNA sequences and compares their GC content.

## Objective
To calculate and compare the GC content of different DNA sequences and understand variations in their nucleotide composition.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Workflow
1. Read multiple DNA sequences from a CSV file using Pandas.
2. Calculate the length of each DNA sequence.
3. Count the G and C nucleotides.
4. Calculate the GC percentage for each sequence.
5. Calculate the average GC content using NumPy.
6. Visualize the results using a Matplotlib bar chart.

## Formula
GC Content (%) = ((G + C) / (A + T + G + C)) × 100

## Results
- Number of sequences analyzed: 5
- Average GC content: 47%
- Highest GC content: Seq_3 (90%)
- Lowest GC content: Seq_2 (10%)

## Files
- `gc_content_explorer.ipynb` – Project code and analysis.
- `sequences.csv` – Input DNA sequences.
- `README.md` – Project documentation.