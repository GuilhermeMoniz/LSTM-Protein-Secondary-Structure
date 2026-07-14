# LSTM Model for Protein Secondary Structure Prediction

This repository contains the materials for a deep learning project focused on predicting protein secondary structure directly from amino acid sequences using LSTM-based architectures.

## Overview

The project explores the use of Long Short-Term Memory (LSTM) networks for protein secondary structure prediction using CASP12 data. Different model configurations, preprocessing strategies, and regularization techniques were tested to improve predictive performance for both 3-state and 7-state secondary structure classification.

## Project contents

- `report/` — full written report describing the background, methods, experiments, and conclusions.
- `notebooks/` — final Jupyter notebooks used for the main experiments:
  - `LSTM_3_final.ipynb` for 3-state prediction.
  - `LSTM_7_final.ipynb` for 7-state prediction.
- `figures/` — result images with training and validation curves, plus final evaluation metrics.

## Methods

The workflow included:
- preprocessing protein sequence data from CASP12,
- encoding amino acid sequences and structural labels,
- training stacked LSTM architectures,
- testing techniques such as dropout, batch normalization, early stopping, learning rate scheduling, and attention mechanisms to improve generalization and reduce overfitting.

## Results

The project achieved strong results for 3-state prediction, with final experiments reporting accuracy near 80%, AUC around 0.89, and F1 score around 0.76 in the best-performing setup. The workflow was also adapted to 7-state prediction, where performance remained promising but highlighted the increased complexity of finer-grained structure classification.

## Notes

This repository is organized as a research portfolio project and includes the final report, notebooks, and result figures available from the original work.
