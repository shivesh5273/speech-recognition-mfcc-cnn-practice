# Speech Recognition and Signal Processing Practice

This project explores foundational techniques in speech signal processing, including FFT analysis, MFCC extraction, CNN model training, and evaluation with a focus on speaker consistency and generalization.

---

## 🔍 Project Breakdown

### 🔊 1. FFT Analysis of Gaussian Function
- Plotted Gaussian curves for σ = 1, 2, 4.
- Computed and visualized real, imaginary, and magnitude of their FFTs.
- Compared how FFT shapes change with increasing σ.

### 🎙️ 2. MFCC Feature Extraction
- Extracted 40 MFCC vectors with 12 coefficients each per wav file.
- Dataset included 5 classes: "dog", "right", "follow", "learn", "three".
- Saved all processed data in `.npy` format and reported file sizes.

### 🧠 3. CNN-Based Audio Classification
- Trained a CNN model using extracted MFCC features.
- Held back a subset of audio samples from each class for manual testing.
- Evaluated and compared against benchmark accuracy from provided notebooks.

### 🗣️ 4. Speaker Split & Validation
- Identified overlapping speakers in training and validation sets.
- Re-split data ensuring speakers don’t appear in both sets.
- Re-trained and re-evaluated model to compare accuracy and curve inversion.

---

## 📁 Files Included

- `fft-gaussian-analysis.html`
- `mfcc-feature-extraction-speech.html`
- `cnn-training-speech-recognition.html`
- `speaker-split-validation-analysis.html`
- `speech-recognition-overview.docx`

---

## 🛠 Tools & Libraries

- Python 3.x  
- NumPy / SciPy (FFT)  
- TensorFlow / Keras  
- Librosa  
- Scikit-learn  
- Google Colab / Jupyter

---

> A comprehensive exploration of classical and modern techniques in speech recognition—from raw signal to CNN inference.
