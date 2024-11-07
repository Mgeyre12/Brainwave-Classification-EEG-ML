# Brainwave-Classification-EEG-ML

## Project Structure

- data/
  - raw/
  - processed/
- src/
  - data_collection.py
  - preprocessing.py
  - feature_extraction.py
  - model.py
  - evaluate.py
- notebooks/
  - exploratory_analysis.ipynb
- requirements.txt
- README.md

## Key Steps

1. Data Collection/Loading
   - Collect EEG data using OpenBCI GUI
   - Alternatively, use publicly available datasets:
     - EEG Motor Movement/Imagery Dataset
     - DEAP Dataset

2. Data Preprocessing
   - Filtering (e.g., bandpass filter)
   - Artifact removal
   - Normalization

3. Feature Extraction
   - Power Spectral Density (PSD)
   - Band Power
   - Time-frequency analysis (STFT, wavelet transforms)

4. Model Training
   - Machine learning models:
     - Support Vector Machines (SVM)
     - Random Forest
   - Neural networks:
     - TensorFlow or Keras implementation

5. Model Evaluation
   - Metrics:
     - Accuracy
     - Confusion matrix
     - F1-score

## Setup

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run data collection script: `python src/data_collection.py`
4. Preprocess data: `python src/preprocessing.py`
5. Extract features: `python src/feature_extraction.py`
6. Train model: `python src/model.py`
7. Evaluate model: `python src/evaluate.py`

## Notes

- Ensure OpenBCI hardware is properly set up before data collection
- Experiment with different preprocessing techniques and feature extraction methods
- Try various machine learning models and hyperparameters for optimal performance