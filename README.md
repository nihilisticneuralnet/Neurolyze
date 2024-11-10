# **Neurolyze**: : Harmful Brain Activity Classification

**Abstract**: This code is implementing a deep learning solution for classifying harmful brain activity from EEG (electroencephalogram) signals in [HMS - Harmful Brain Activity Classification *(Kaggle Competition)*](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification/overview). It processes EEG data from different electrodes placed on the brain, using a combination of ResNet (a type of convolutional neural network) and GRU (Gated Recurrent Unit) architectures to detect six different types of brain activity patterns: seizures, LPD (Lateralized Periodic Discharges), GPD (Generalized Periodic Discharges), LRDA (Lateralized Rhythmic Delta Activity), GRDA (Generalized Rhythmic Delta Activity), and other patterns. The code includes preprocessing steps like bandpass filtering to focus on relevant frequency ranges, data normalization, and creates differential features between electrode pairs. The model architecture processes these features through parallel convolutional layers with different kernel sizes, followed by residual blocks and a bidirectional GRU layer, ultimately producing probability scores for each type of brain activity.

## Description
### Goal of the Competition
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.

Your work may help rapidly improve electroencephalography pattern classification accuracy, unlocking transformative benefits for neurocritical care, epilepsy, and drug development. Advancement in this area may allow doctors and brain researchers to detect seizures or other brain damage to provide faster and more accurate treatments.

### Dataset

![image](https://github.com/user-attachments/assets/ba6907ee-9374-49dc-acdb-230a861ca426)

![image](https://github.com/user-attachments/assets/bdef97d3-ef17-4318-afca-b4902fe43e02)
