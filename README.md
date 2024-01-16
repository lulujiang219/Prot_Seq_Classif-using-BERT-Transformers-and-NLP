# Protein Sequence Classification using BERT and NLP

## Overview
This repository contains the code and datasets for a project focused on the classification of protein sequences using BERT (Bidirectional Encoder Representations from Transformers) and NLP (Natural Language Processing) techniques. The project aims to apply advanced machine learning methods to bioinformatics, specifically for the classification of protein sequences based on their locations and characteristics.

## Contents
- Data preprocessing and analysis scripts
- Jupyter notebooks for exploratory data analysis
- Scripts for training classification models using BERT and NLP
- Utility scripts for data manipulation and processing

## Data Source
We are using an open-source public dataset of protein sequences, which can be found at [DeepLoc-1.0 Dataset](https://services.healthtech.dtu.dk/services/DeepLoc-1.0/). The dataset is a FASTA file composed of a header and a protein sequence. The header includes the accession number from Uniprot, the annotated subcellular localization, and possibly a description field indicating if the protein was part of the test set. The subcellular localization includes an additional label, where 'S' indicates soluble, 'M' for membrane, and 'U' for unknown[9].

A sample of the data is as follows:

```
>Q9SMX3 Mitochondrion-M test
MVKGPGLYTEIGKKARDLLYRDYQGDQKFSVTTYSSTGVAITTTGTNKGSLFLGDVATQVKNNNFTADVKVST
DSSLLTTLTFDEPAPGLKVIVQAKLPDHKSGKAEVQYFHDYAGISTSVGFTATPIVNFSGVVGTNGLSLGTDV
AYNTESGNFKHFNAGFNFTKDDLTASLILNDKGEKLNASYYQIVSPSTVVGAEISHNFTTKENAITVGTQHAL
DPLTTVKARVNNAGVANALIQHEWRPKSFFTVSGEVDSKAIDKSAKVGIALALKP
```

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
