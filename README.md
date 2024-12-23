# 🎧 Heart Sound Classification for Early Detection of Cardiovascular Diseases

🔍 **Heart Sound Classification** is an innovative project that leverages machine learning and deep learning techniques to detect cardiovascular diseases early. By analyzing heart sound recordings, we classify conditions such as:
- **Aortic Stenosis (AS)**
- **Mitral Stenosis (MS)**
- **Mitral Regurgitation (MR)**
- **Mitral Valve Prolapse (MVP)**
- **Normal**

💡 This system bridges the gap between advanced medical diagnostics and accessible technology, enabling timely interventions for life-threatening conditions.

---

## ✨ Key Features

✅ **Comprehensive Classification**: Detects 5 distinct heart sound categories.  
✅ **Advanced Feature Extraction**:
   - Log Mel, MFCC, Discrete Wavelet Transform (DWT), Chroma, Zero-Crossing Rate, and more.
   - Transformer-based Wav2Vec for deep feature learning.  
✅ **Cutting-Edge Models**:
   - A hybrid CNN + LSTM model for temporal and spatial analysis.
   - XGBoost for structured feature-based classification.  
✅ **Robust Validation**: K-Fold and Monte Carlo cross-validation ensure accuracy and reliability.

---

## 🛠️ Methodology

1. **🎼 Feature Extraction**:
   - **Log Mel & MFCC**: Capture the essence of sound frequency.
   - **Delta & Delta-Delta**: Analyze changes and acceleration over time.
   - **Wav2Vec**: Transformer model for capturing high-level representations.

2. **🤖 Models Used**:
   - **CNN + LSTM**: Combines convolutional layers for spatial features and LSTM for sequential data.
   - **XGBoost**: A powerful tree-based algorithm optimized for structured datasets.

3. **📊 Data Splitting**:
   - 80% Training, 20% Testing & Validation.
   - K-Fold cross-validation ensures reliability.

---

## 📈 Results

Our models achieved state-of-the-art performance:  

| Approach                          | Accuracy |
|-----------------------------------|----------|
| Wav2Vec + Hybrid Model            | 94%      |
| Wav2Vec + XGBoost                 | 94%      |
| **Regular Features + Hybrid Model** | **98%**  |
| **Regular Features + XGBoost**    | **99%**  |

🚀 **XGBoost with Regular Features** outperformed all other methods, achieving near-perfect classification.  

---

## 🧑‍💻 Requirements

- Python 3.x  
- Libraries: `tensorflow`, `xgboost`, `numpy`, `librosa`, `sklearn`, `pytorch`, etc.

---

## ⚙️ Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/heart-sound-classification.git
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
### 🏃‍♂️ Run Jupyter Notebook

Launch Jupyter Notebook to run the `.ipynb` files:

```bash
jupyter notebook
```
## 🎯 Conclusion

This project demonstrates the potential of machine learning and deep learning in medical diagnostics. By combining advanced feature extraction techniques and state-of-the-art models, we provide a reliable system for detecting heart sound abnormalities with **up to 99% accuracy**. 🌟

💡 With further data and refinement, this approach can revolutionize non-invasive cardiovascular disease diagnosis.
