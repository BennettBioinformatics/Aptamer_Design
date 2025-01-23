**# Aptamer_Design **
This study explores the potential of AI and machine learning in designing aptamers for targeted drug delivery and diagnostics in healthcare. Aptamers are single-stranded oligomers that can specifically bind to targets, playing vital roles in drug discovery, bioimaging, and precision medicine.
**Key Features:**
Objective: Optimize aptamers for enhanced stability, binding affinity, and therapeutic applications.
Approaches: ML/AI based tools for virtual screeening and binding afinity prediction
Applications: Cancer treatment, infectious diseases, precision medicine, and targeted therapies.

—We have utlized some already existed machine learning and deep learning based tools to prepare a novel pipeline to design new modified aptamers.

**Requirements**
1- Databases: PDB database, AptaDB, UTexas Aptamer Database, RNAapt3D
2- Tools and Software
  (a) Screening Tools: AptaNet, PredPRBA
  (b) Library generation using python script
      #import csv
      #import itertools
  (b) Structure Analysis: UCSF ChimeraX, PyMOL, CHIMERA_NA, 
  (c) Simulation Tools: AMBER, GROMACS, Schrodinger for Molecular Dynamics Software
Feature Prediction: UnaFold, RNAFold, OligoAnalyzer
2- AptaNet script for features extraction and prediction
  (a) Languages: Python (for script generation and sequence analysis)
  (b) Libraries: NumPy, SciPy, Matplotlib, Pandas, repDNA
         #sklearn.model_selection import train_test_split
         #sklearn.preprocessing import StandardScaler
         #sklearn.neural_network import MLPClassifier
         #sklearn.metrics import accuracy_score, classification_report
3- System Requirements
  (a) Processor: Minimum quad-core processor
  (b) Memory: At least 8 GB RAM
  (c) Storage: 10 GB free disk space
  (d) Operating System: Windows 10, macOS, or Linux

  ##### Case Study results
  1- Aptamer library generation : 16384 sequnces have been generated of 3HSB RNA aptamer sequence 'AGAGAGA'.
  2- Virtual screening: AptaNet has been used for virtual screening. 
     (a) Features extraction and prediction: Features has been extracted on the basis of interaction features such as AAX 9Amino acid composition), k-3mer, PseAAC (Pseudo Amino Acid Composition)  
                                                           will be extracted. ces having Class 1 and highest interaction probability percentage will be selected for CHIMERA_NA mutation.
     (b) 
                    
