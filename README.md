# Kaggle-Stanford-RNA-3D-Folding

Kaggle competition solution<br>
Public Score:<br> 
Private Score:<br>
This repository contains my solution for the Kaggle competition "Stanford RNA 3D Folding".The goal of the competition is to develop machine learning models that can predict the 3D structure of RNA molecules from their sequences, thereby advancing our understanding of biological processes and contributing to progress in medicine and biotechnology.

## Competition overview

Predicting the 3D structure of Ribonucleic Acid (RNA) is like solving a puzzle without knowing the final picture. Instead of relying on a reference, one must use patterns and logic to understand how RNA folds into its functional structures. In this competition, the challenge is to develop machine learning models that can predict an RNA molecule’s 3D structure directly from its sequence. Achieving this will not only deepen our understanding of biological processes but also open the door to new advancements in medicine and biotechnology.

## Competition goal

The goal of this competition is to build machine learning models that predict the 3D structure of RNA molecules from their sequences, advancing our understanding of biological processes and enabling progress in medicine and biotechnology.

## Evaluation

Submissions are evaluated using TM-score (0.0–1.0, higher is better), which measures structural similarity between predicted and experimental RNA structures. Predictions are aligned with reference structures using US-align in a sequence-independent manner. For each RNA sequence, you must submit 5 predicted structures, and the best TM-score among them is used. The final score is the average best-of-5 TM-score across all targets. If multiple experimental structures exist, the best score against them is considered.

## Submission

For each RNA sequence in the test set, you must predict five 3D structures.
Your notebook should read test_sequences.csv and output submission.csv, which contains the x, y, z coordinates of the C1' atom for every residue in each of the five predicted structures.
```csv
ID,resname,resid,x_1,y_1,z_1,... x_5,y_5,z_5
R1107_1,G,1,-7.561,9.392,9.361,... -7.301,9.023,8.932
R1107_2,G,1,-8.02,11.014,14.606,... -7.953,10.02,12.127
etc.
```
You must submit five sets of coordinates.

## Data and model
Train and test dataset: [link](https://www.kaggle.com/competitions/stanford-rna-3d-folding/data)
DRfold2 model: [link](https://github.com/leeyang/DRfold2)
Protenix model: [link](https://github.com/bytedance/Protenix)

## Citation
Shujun He, CASP16 organizers, CASP16 RNA experimentalists, RNA-Puzzles consortium, VFOLD team, Rachael Kretsch, Alissa Hummer, Andrew Favor, Walter Reade, Maggie Demkin, Rhiju Das, et al. Stanford RNA 3D Folding. https://kaggle.com/competitions/stanford-rna-3d-folding, 2025. Kaggle.

