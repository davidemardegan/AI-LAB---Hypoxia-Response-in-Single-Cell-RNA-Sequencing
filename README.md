# Hypoxia Response in Single-Cell RNA Sequencing

University group project completed for **AI Lab** at Bocconi University (2026).

**Authors:** Davide Mardegan, Giovanni Mazzi, Ascanio Schena, Arturo Zecchina

## Overview

This project studies the transcriptional response to **hypoxia** in single-cell RNA sequencing data from the **HCC1806** and **MCF7** breast cancer cell lines, using both **SmartSeq** and **DropSeq** technologies.

The aim was to understand how oxygen condition, sequencing technology, cell line identity and latent biological structure interact, and to evaluate how well hypoxia can be detected from gene-expression profiles.

## Methods

The workflow combines:

- exploratory data analysis and quality control
- PCA, t-SNE and UMAP
- deterministic and variational autoencoders
- hierarchical clustering, K-Means and Gaussian mixture models
- pathway-level analysis and cell-cycle scoring
- engineered latent representations
- linear and non-linear classification
- stratified cross-validation and randomized hyperparameter tuning

## Key findings

The analysis found a strong transcriptional hypoxia signal across datasets, but the difficulty of the classification problem depended strongly on sequencing technology.

- **SmartSeq** produced denser and more informative representations of the hypoxia signal.
- **DropSeq** data were substantially sparser and benefited more from non-linear classifiers.
- Autoencoder representations were particularly informative for SmartSeq data.
- Unsupervised low-dimensional visualisations alone were generally insufficient to cleanly separate hypoxia from normoxia at cell level.

## Technologies

Python · pandas · NumPy · scikit-learn · PyTorch · UMAP · PCA · clustering · deep learning · single-cell RNA-seq

## Course context

**AI Lab — Bocconi University, 2026**

This repository is intended as a compact portfolio version of the full university project.
