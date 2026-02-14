## Intro
This project implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method to rank alternatives based on multiple criteria. It helps identify the best option by comparing each alternative’s distance from an ideal best and ideal worst solution.

## Methodology
The algorithm normalizes the data, applies user-defined weights, determines ideal best and worst values based on impacts, computes distances from these ideals, calculates a performance score, and assigns ranks accordingly.

## Data
Input is a CSV file with at least three columns. The first column contains alternative names, and the remaining columns contain numeric criteria values. Weights and impacts are provided as comma-separated inputs.

## Results
The program generates a CSV file containing the original data along with TOPSIS score and rank for each alternative. Higher scores indicate better performance.

## Inferences
TOPSIS provides an objective ranking based on multiple criteria and helps decision-making by identifying the alternative closest to the ideal solution.
