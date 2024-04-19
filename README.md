# Investigating the impact of Butina Clustering on Virtual Screening Effectiveness for Drug Discovery


## Overview:

This repository explores the impact of Butina clustering on virtual screening effectiveness for drug discovery in PIK3CA-mutated cancers. It serves as the capstone project for my Master's degree in Data Science at Northeastern University.

## Abstract:

This project investigates the potential of Butina clustering to enhance virtual screening outcomes for identifying drug candidates targeting PIK3CA mutations in cancers. We leverage a combination of computational methods and bioinformatics tools to assess how clustering techniques can improve the efficiency of virtual screening.

## Installation:

This project utilizes Python libraries like pandas, scikit-learn, and RDKit. Ensure you have these installed using '''pip install pandas scikit-learn rdkit'''.

## Usage:

Download the repository and navigate to the project directory.
Execute the Jupyter Notebooks in the following order:
*'''compound_data_aquisition.ipynb''' (Acquires compound data)
*'''Molecular_filtering.ipynb''' (Performs data pre-processing and filtering)
*'''Ligand_based_screening.ipynb''' (Conducts virtual screening with and without clustering)
*'''compound_clustering.ipynb''' (implements the butina clustering algorithm)

##R esults Visualization:

The '''Ligand_based_screening.ipynb''' notebook generates enrichment plots that visually depict the effectiveness of virtual screening with and without clustering.

## Future Work:

This project establishes a foundation for further exploration. Future work could involve:

*Evaluating alternative clustering algorithms and parameters.
*Incorporating machine learning techniques for improved virtual screening.
*Testing the approach with a broader range of datasets and cancer types.


## Contact:

Disleve Kanku
Khoury College of Computer Science, Northeastern University
kanku.d@northeastern.edu