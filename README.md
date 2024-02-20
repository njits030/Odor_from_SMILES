# Odor_from_SMILES
Predicting odor with a SMILES. This repository contains the code and data used for my thesis called 'Predicting Odor with a SMILES'. 

The original pyrfume data downloaded at 29-10-2022 is located in the Pyrfume_data/ folder.
The train and test split, mordred features and other data can be found in the folder Data_set/.
The Packages folder contains a patched version of Mordred.

Data is collected from Pyrfume_data/ in the assemble_data notebook.
Umbrella terms are added in the add_umbrella_terms notebook.
Recursive feature elimination on the Mordred features is done in the mordred_features-2d notebook.
The models are evaluated in the analyze_classifier notebook, contains plots and code to create plots for the most part.
