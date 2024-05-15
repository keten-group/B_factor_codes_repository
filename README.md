# B_factor_codes_repository
The published paper for this code can be found here: https://www.cell.com/patterns/pdf/S2666-3899(23)00160-5.pdf

We have converted the data from PDB to input (x) and output (y) file. Using the link below, .npy files can be downloaded and directly be used to run the training and testing codes.

.npy file link:
https://drive.google.com/drive/folders/1uNgl5bi6Wc7Np_BN3PkVGyqr4U6pNTng?usp=share_link

The **one-hot encoding** for amino acids is generated based on the following sequence: 

['A', 'V', 'F', 'I', 'L','D','E','K','S','T','Y','C','N','Q', 'P','M', 'R', 'H', 'W', 'G', 'X']

**Training files:**

1) Training_35.py : Code which uses all features
2) Training_35_only_primary_seq.py: Code which uses only primary sequence

**Test files:**

1) test_all_features.ipynb: Code which uses all features
2) test_only_primary_Sequence.ipynb: Code which uses only primary sequence

**Checkpoint:**

We have provided a model checkpoint in a folder named "checkpoint". 
- b_factor_all_features.pth: checkpoint when all the features are used.
- b_factor_model.pth: checkpoint when only the primary sequence is used as a feature. 

NOTE: 
1) Before running any code, please check all the paths
2) First run the training code to get the optimized model. Then use the optimized model in the test code.
