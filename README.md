# RNA Secondary Structure Prediction

A dynamic programming-based approach for predicting RNA secondary structures using optimal base-pairing interactions.

## Project Overview

This project predicts RNA secondary structures by identifying the maximum number of valid, non-overlapping base pairs in an RNA sequence.

## Key Features

- Implemented a dynamic programming algorithm for RNA structure prediction
- Applied biological pairing rules for A-U and G-C interactions
- Identified optimal RNA base-pairing patterns
- Generated dot-bracket notation for predicted structures
- Tested the model on multiple RNA sequences
- Visualized predicted RNA secondary structures

## Workflow

RNA Sequence → Valid Base-Pair Detection → Dynamic Programming → Traceback → Base Pairs → Dot-Bracket Structure

## Example

**Input Sequence:**
`GGGAAAUCC`

**Predicted Structure:**
`.((..()))`

**Optimal Base Pairs:** 3

## Technologies

- Python
- NumPy
- Matplotlib
- Dynamic Programming

## Files

- `RNA_Secondary_Structure_Prediction.ipynb` — Complete implementation
- `requirements.txt` — Required Python packages

## Note

The implementation focuses on canonical A-U and G-C base pairing and maximizes the number of non-overlapping base pairs.
