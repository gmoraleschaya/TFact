# TFact: A Computational Tool for Transcription Factor Activity Prediction

## Overview

TFact is a computational tool designed to predict transcription factor (TF) activity in different cell types using single-cell RNA sequencing (scRNA-seq) data. By analyzing gene expression patterns, TFscope infers whether a TF acts as an activator, repressor, or functions in combination with other TFs to regulate gene expression.

## Features

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Required Python packages: Scanpy

### Setup


## Usage

### Input

TFact takes scRNA-seq .h5ad objects as an input.

### Running the Analysis

### Output

The output includes predicted TF activity scores for each cell type, identifying key activators and repressors.

## Example Workflow

1. Preprocess scRNA-seq data (e.g., normalization, feature selection).
2. Run TFscope to predict TF activity.
3. Visualize results.

## Contributing

This project was developed by Gonzalo Morales Chaya, Sebastian Jaramillo and Fan Huang

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

For questions or feedback, please open an issue or contact gonzalom@uoregon.edu
