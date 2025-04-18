# EEG Emotion Recognition using DEAP Dataset

This project focuses on processing EEG signals from the [DEAP dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/) to recognize human emotions. The pipeline includes feature extraction, and classification using deep learning and machine learning models.

## 🧠 Dataset

The [DEAP]([https://www.eecs.qmul.ac.uk/mmv/datasets/deap/](https://www.kaggle.com/datasets/manh123df/deap-dataset)) dataset is a multimodal dataset for the analysis of human affective states, containing EEG and peripheral physiological signals recorded from 32 participants while watching 40 one-minute music videos.

## 🛠️ Features

- Signal segmentation and normalization
- Feature extraction (statistical, frequency-based)
- Emotion labeling based on arousal/valence scores
- Deep learning models for emotion classification
- Visualization of results

## 🧠 EEG Frequency Bands

In this project, we focus on specific EEG frequency bands that are known to be associated with different mental states:

- **Alpha (8–12 Hz)**: Associated with relaxed, calm, and restful states. Often seen when the eyes are closed.
- **Beta (12–30 Hz)**: Linked to active thinking, focus, and concentration.
- **Gamma (30–64 Hz)**: Related to high-level cognitive functioning, perception, and consciousness.

These bands are extracted from the EEG signals to serve as features for emotion classification.




