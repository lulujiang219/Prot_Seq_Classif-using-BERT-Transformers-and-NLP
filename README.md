# Protein Sequence Classification using BERT and NLP

## Overview
This repository contains the code and datasets for a project focused on the classification of protein sequences using BERT (Bidirectional Encoder Representations from Transformers) and NLP (Natural Language Processing) techniques. The project aims to apply advanced machine learning methods to bioinformatics, specifically for the classification of protein sequences based on their locations and characteristics.

## Contents
- Data preprocessing and analysis scripts
- Jupyter notebooks for exploratory data analysis
- Scripts for training classification models using BERT and NLP
- Utility scripts for data manipulation and processing

## Data
The data used in this project includes protein sequences with annotated subcellular locations. The data is processed and divided into training and testing sets.

- `deeploc_data.fasta`: Original dataset in FASTA format.
- `deeploc_per_protein_train.csv`: Processed training dataset.
- `deeploc_per_protein_test.csv`: Processed testing dataset.

## Setup and Installation
To run the scripts and notebooks in this repository, you need to have Python installed along with the following libraries:
- Pandas
- NumPy
- BioPython
- Matplotlib
- Seaborn
- AWS SageMaker SDK

You can install these packages using pip:
```bash
pip install pandas numpy biopython matplotlib seaborn sagemaker
