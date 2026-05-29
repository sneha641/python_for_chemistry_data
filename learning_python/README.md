========================================
  Python Scripting for Computational Molecular Science
========================================

This folder contains Python practice notebooks (1-6) from a computational molecular sciences (CMS) workshop.
Each notebook covers a different Python concept applied to chemistry data.

----------------------------------------
NOTEBOOKS (Learning Progression)
----------------------------------------

1. Basic Syntax (1_basic_syntax.ipynb)
   - Variables, data types, type conversion
   - Lists, slicing, and basic operations

2. File Parsing (2_fileparsing.ipynb)
   - Reading output files
   - String splitting and searching for specific data
   - Extracting energies from computational chemistry output

3. Multiple Files (3_multiple_files.ipynb)
   - Using os.path and glob modules
   - Looping over multiple .out files
   - Extracting data and writing results

4. Tabular Data (4_tabulardata.ipynb)
   - Reading CSV files with NumPy
   - Array indexing and slicing
   - Computing statistics (mean) on columns

5. Plotting & Visualization (5_plot and visualize.ipynb)
   - Using matplotlib to create plots
   - Labeling axes and adding legends
   - Saving figures as PNG images

6. Functions (6_funtions.ipynb)
   - Defining and calling functions
   - calculate_distance and bond_check functions
   - Geometry analysis of molecular XYZ files

----------------------------------------
OTHER FILES
----------------------------------------

geometry_analysis.py
   - Standalone Python script for molecular geometry analysis
   - Functions: calculate_distance, bond_check, open_xyz
   - Reads XYZ files and identifies bonded atom pairs

Etot.txt
   - Total energy values extracted from data/03_Prod.mdout
   - Saved from Notebook 5 (Plot and Visualize)

----------------------------------------
SAVED IMAGES (from Notebook 5)
----------------------------------------

THR4_ASP.png  - Distance plot for THR4 vs ASP residues
THR4_ATP.png  - Distance plot for THR4 vs ATP residues
TYR6_ASP.png  - Distance plot for TYR6 vs ASP residues
TYR6_ATP.png  - Distance plot for TYR6 vs ATP residues

----------------------------------------
DATA FOLDER (data/)
----------------------------------------

03_Prod.mdout             - Amber molecular dynamics simulation output
benzene.xyz               - XYZ coordinates for benzene molecule
buckminsterfullerene.xyz  - XYZ coordinates for C60 (buckyball)
distance_data_headers.csv - CSV with distance measurements (used in notebooks 4 & 5)
water.xyz                 - XYZ coordinates for water molecule

data/outfiles/            - Alcohol molecule output files:
   butanol.out, decanol.out, ethanol.out, heptanol.out,
   hexanol.out, methanol.out, nonanol.out, octanol.out,
   pentanol.out, propanol.out

========================================
