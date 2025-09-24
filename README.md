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
