# Neuroformal ( Natural Language Understanding Project) 

This project aims to create a model to classify
the formality of a given piece of text at the sequence level using a neural network. Therefore,
the project can be classified as a sequence classification task. The model would use a sequence
(a series of tokens) as input, and it would output
the level of formality within a range of -3 (most
informal) to 3 (most formal).The purpose of the
model is to classify a sequence into 7 possible labels based on the seven-point Likert scale. The
possible labels are; -3 (most informal), -2 (considerably informal), -1 (slightly informal), 0 (neutral),
1 (slightly formal), 2 (considerably formal), and
3 (most formal). Furthermore, the project will explore various neural network architectures trained
on a balanced training dataset and evaluate their
performance as a formality classifier by comparing the F-score (weighted harmonic mean). F-score
was selected for the evaluation metric, as the testing
dataset contains imbalanced data.
