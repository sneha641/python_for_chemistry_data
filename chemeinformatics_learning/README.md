# Chemeinformatics Learning

This folder contains my learning and practice work in chemeinformatics using Python, RDKit, pandas, seaborn, and scikit-learn.

## Notebooks

### 1. `01_molecule_representation.ipynb`
This notebook introduces digital representations of molecules.
It covers:
- SMILES notation
- atoms, bonds, branches, and rings in SMILES
- examples such as ethanol, cyclopentane, and pyridine
- simple SMILES exercises for molecules like water, benzene, carbon dioxide, and amide-containing structures
- overview of common molecular file formats such as SMILES, InChI, MOL/SDF, PDB, XYZ, CIF, PQR, PDBQT, and MOL2

### 2. `02_rdkit_intro.ipynb`
This notebook gives a basic introduction to RDKit.
It includes:
- importing RDKit
- creating molecules from SMILES strings
- examples such as methane, ethane, propane, ethene, cyclohexane, benzene, acetic acid, and ethyne
- print atom element or atom hybridization and loop to give information about each atom
- editing atoms with RDkit
- Molecular Sanitization to set aromaticity
- combine molecules

### 3. `03_molecular_similarity.ipynb`
This notebook focuses on molecular similarity and fingerprints.
It includes:
- substructure search
- SMARTS for specifying substructures in molecules.
- RDKit fingerprints
- Tanimoto similarity
- similarity comparison examples using benzene, aspirin, pyridine, and aniline
- interpretation of structural similarity results
- Molecular descriptors

### `04_rdkit_database.ipynb`
Using RDkit to Build dataset
It includes:
- Read SMILES from a text file.
- Make an RDKit molecule for each SMILES.
- Get the number of heavy atoms, molecular weight, and LogP descriptor
- Write a file with the data in csv

### `05_pandas_seaborn.ipynb`
This notebook uses pandas and seaborn for chemical data analysis and visualization.  
It includes working with tabular data, exploring dataset patterns, and creating plots for interpretation.

### `06_sklearn_fitting.ipynb`
This notebook introduces machine learning model fitting using scikit-learn.  
It focuses on using prepared molecular or chemical data for prediction and model evaluation, such as linear regression and RandomForestRegressor.

### `data/`
Contains supporting datasets used in the notebooks, including text and CSV files.

### `images/`
Contains images used in the notebooks for explanation and reference.