# **Neurolyze**: : Harmful Brain Activity Classification

**Abstract**: This code implements a machine learning pipeline for predicting protein functions using the CAFA-5 (Critical Assessment of Function Annotation) dataset in [CAFA 5 Protein Function Prediction *(Kaggle Competition)*](https://www.kaggle.com/competitions/cafa-5-protein-function-prediction). The pipeline first processes protein sequence data that has been pre-embedded using ProtBERT model to convert proteins into numerical vectors. It then trains a Multi-Layer Perceptron to predict which Gene Ontology (GO) terms are associated with each protein, essentially predicting protein functions. The training process uses cross-entropy loss and monitors F1 score performance on both training and validation sets. Finally, it generates predictions for a test set and combines these predictions with other pre-existing predictions (from BlastP, Sprof, QuickGo, and DeepGoZero) through a merge operation, taking the best confidence scores available for each protein-GO term pair. This ensemble approach likely improves the overall prediction accuracy by leveraging multiple prediction methods.

## Description
### Goal of the Competition
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.

Your work may help rapidly improve electroencephalography pattern classification accuracy, unlocking transformative benefits for neurocritical care, epilepsy, and drug development. Advancement in this area may allow doctors and brain researchers to detect seizures or other brain damage to provide faster and more accurate treatments.
