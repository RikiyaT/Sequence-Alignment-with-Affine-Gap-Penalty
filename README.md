# Sequence Alignment with Affine Gap Penalty

This repository contains the Jupyter notebook `main.ipynb`, which implements a sequence alignment algorithm using the Needleman-Wunsch approach with affine gap penalties.

## Features

- Accepts DNA sequences in FASTA format.
- Implements sequence alignment using the Needleman-Wunsch algorithm.
- Incorporates affine gap penalties, with separate penalties for gap opening and extension.
- Outputs alignment score and the aligned sequences.

## Technologies Used

- Python
- Jupyter Notebook
- Biopython's SeqIO for parsing FASTA files
- Tabulate for formatting output

## Code Example

Here is a sneak peek of what you can find in `main.ipynb`:

```python
# Importing required libraries
from Bio import SeqIO
from tabulate import tabulate

# Parse sequences using SeqIO
seq1 = SeqIO.read('sequence1.fasta', 'fasta')
seq2 = SeqIO.read('sequence2.fasta', 'fasta')

# Define gap penalties
gap_open_penalty = -2
gap_extension_penalty = -1

# More code follows to implement the sequence alignment...
