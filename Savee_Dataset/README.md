# **Emotion Classification Using SAVEE Dataset**

## **Overview**
This project classifies emotions (e.g., angry, happy, sad) from audio files using the **SAVEE dataset**. It employs **audio feature extraction** and a **deep learning model** (Conv1D and Dense layers) to predict emotions.

---

## What We Are Doing
1. **Extract Features**:
   - MFCC (Mel-Frequency Cepstral Coefficients)
   - RMS Energy
   - Chroma Features
   - Spectral Contrast  
2. **Data Augmentation**:
   - Pitch Shifting, Time Stretching, and Noise Injection.
3. **Train a Neural Network**:
   - Conv1D model for time-series audio data.
4. **Evaluate**:
   - Accuracy, confusion matrix, and classification report.

---

## **Requirements**
- **Dataset**: Download the **SAVEE dataset** [here](http://kahlan.eps.surrey.ac.uk/savee/) and place it in a folder named `data/`.
- **Libraries**: Install the required libraries:
   ```bash
   pip install librosa tensorflow scikit-learn matplotlib seaborn
   ```

---

## **How to Run**
1. Download the SAVEE dataset and place it in the `data/` directory.
2. Run the `main.ipynb` file in Google Colab or Jupyter Notebook.
3. The script will:
   - Preprocess audio data.
   - Train and validate a neural network model.
   - Display evaluation metrics and visualizations.

---
## **Output**
- Training and testing accuracy.
- Confusion matrix.
- Classification report.
