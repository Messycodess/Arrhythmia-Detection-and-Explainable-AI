# Arrhythmia-Detection-and-Explainable-AI

## 🫀 ECG Beat Classification using Deep Learning

### 📌 Project Overview
This project focuses on automated **ECG heartbeat classification** using the **MIT-BIH Arrhythmia Dataset**, following the **AAMI 5-class scheme**. Multiple deep learning architectures were implemented and compared to identify the most accurate and interpretable model for arrhythmia detection.

---

### 🧠 Models Evaluated
The following models were trained and evaluated:

- ResNet18-1D  
- 1D Convolutional Neural Network (1D-CNN)  
- InceptionTime  
- MiniXception1D  

---

### 📊 Results
| Model | Accuracy (%) |
|------|--------------|
| **ResNet18-1D** | **99.01** |
| 1D-CNN | 98.61 |
| InceptionTime | 96.16 |
| MiniXception1D | 93.35 |

**ResNet18-1D achieved the highest accuracy**, attributed to its strong feature extraction capability enabled by residual connections.

---

### 🔍 Model Explainability (Grad-CAM)
To enhance interpretability, **Gradient-weighted Class Activation Mapping (Grad-CAM)** was applied to the best-performing model.

**Key insights:**
- The model focuses on **clinically meaningful ECG regions**, including:
  - QRS complex
  - Abnormal ventricular waveforms
- This confirms that predictions are driven by relevant physiological patterns rather than noise.

---

### 🏆 Conclusion
- Residual learning in **ResNet18-1D** significantly improves ECG feature representation.
- Grad-CAM visualizations validate the clinical relevance of the learned features.
- The combination of **high accuracy and explainability** makes ResNet18-1D the most effective model among those evaluated.

---
