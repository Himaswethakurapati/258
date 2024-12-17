# **Emotion Classification Using SAVEE Dataset**

## **Overview**
This project classifies human emotions from audio signals using the **SAVEE dataset**. It employs audio feature extraction, data augmentation, and a **1D Convolutional Neural Network (Conv1D)** for emotion recognition.

---

## **Key Steps**
1. **Feature Extraction**:
   - Extracted features include **MFCC**, **RMS Energy**, **Chroma Features**, and **Spectral Contrast** using `librosa`.

2. **Data Augmentation**:
   - Techniques: **Pitch Shifting**, **Time Stretching**, and **Noise Injection** to improve model robustness.

3. **Neural Network**:
   - **Model**: 1D Convolutional Neural Network (Conv1D).
   - **Input**: Extracted audio features.
   - **Output**: Multi-class emotion classification.

4. **Evaluation**:
   - **Metrics**: Accuracy, Confusion Matrix, and Classification Report.

---

## **Setup**
- **Dataset**: Download the SAVEE dataset from the [official source](http://kahlan.eps.surrey.ac.uk/savee/).
- **Dependencies**:
   ```bash
   pip install librosa tensorflow scikit-learn matplotlib seaborn
   ```

---

## **Run the Project**
1. Place the SAVEE dataset in the `data/` folder.
2. Run `main.ipynb` in Google Colab or Jupyter Notebook.

---

## **Output**
- Model performance metrics (accuracy, confusion matrix).
- Visualizations of training results and evaluation metrics.
