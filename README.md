# Protein-structure-prediction-pytorch-

PREDICTING SECONDARY STRUCTURES OF PROTEINS: A Domain Theory

An important problem in molecular biology is that of predicting "protein
secondary structure." Briefly, the task is:

for each element in a protein sequence (drawn from a 20-letter alphabet),
assign it to one of three classes (alpha helix, beta sheet, or coil).

Qian and Sejnowski [3] produced a set of examples
protein-secondary-structure.[train,test] (this directory). Originally via
anonymous ftp from spice.cs.cmu.edu; cd to /afs/cs/project/connect/bench.

Our objective: try to improve the results got by Qian and Sejnowski! 


Implement and train an MLP model used with a sliding analysis window in order to predict the class of an element of the sequence;
