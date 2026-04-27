# 🚀 GEBiLSTM-Attn: Novel Architecture for RUL Prediction

## 📌 Overview
This repository presents **GEBiLSTM-Attn**, a novel deep learning architecture designed for **Remaining Useful Life (RUL) prediction** using the NASA CMAPSS dataset.

The model combines the strengths of:

- **Bidirectional LSTM (BiLSTM)** → Captures forward & backward temporal dependencies  
- **Attention Mechanism** → Focuses on the most important time steps  
- **Gated Enhancements (Proposed)** → Improves feature selection and information flow  

👉 Traditional sequence models often fail to prioritize critical temporal features.  
👉 Our architecture addresses this using **attention-driven learning and enhanced gating mechanisms**.  

BiLSTM processes sequences in both directions, improving context understanding, while attention assigns higher importance to relevant inputs, boosting performance.

---

## 🧠 Proposed Architecture: GEBiLSTM-Attn

<p align="center">
  <img width="800" src="https://github.com/user-attachments/assets/1072d249-5a0b-4f48-8ad5-ea914bf78400" />
</p>

### 🔹 Key Idea
We introduce a **Gated Enhanced BiLSTM with Attention (GEBiLSTM-Attn)** that improves:

- Feature extraction  
- Temporal dependency modeling  
- Interpretability  

---

## 🔹 Architecture Flow

```

Input Time-Series Data
↓
3 Parallel Branches (LSTM, GRU, CNN)
↓
Data Preprocessing & Normalization
↓
Gated Feature Enhancement Layer (Proposed)
↓
BiLSTM Layer (Bidirectional Temporal Learning)
↓
Attention Layer (Feature Importance Weighting)
↓
Fully Connected Layers
↓
RUL Prediction (Regression Output)

```

---

## ⚙️ Why This Architecture?

### 🚫 Problems with Existing Models
- Standard LSTM → Struggles with long-term dependencies  
- BiLSTM → Treats all time steps equally  
- Lack of focus on critical degradation signals  

### ✅ Our Improvements
- **Gated Enhancement Layer** → Filters noisy sensor data  
- **Attention Mechanism** → Prioritizes important degradation patterns  
- **BiLSTM** → Captures bidirectional dependencies  

👉 Hybrid architectures combining BiLSTM and attention significantly improve sequence modeling and prediction accuracy.

---

## 📊 Dataset

- **Dataset:** NASA CMAPSS (Commercial Modular Aero-Propulsion System Simulation)  
- **Type:** Multivariate time-series  
- **Task:** Predict Remaining Useful Life (RUL) of engines  

---

## 🧪 Methodology

### 🔹 Steps
1. Data preprocessing & normalization  
2. Sequence generation  
3. Model training  
4. Evaluation using regression metrics  

### 🔹 Model Training
- **Loss Functions:** MAE, RMSE  
- **Optimizer:** Adam  
- **Framework:** TensorFlow  

---

## 📈 Results

✔ Improved prediction accuracy compared to baseline models  
✔ Better handling of long-term dependencies  
✔ Enhanced interpretability via attention  

### 🔹 Performance Metrics

| Dataset | MAE (cycles) | RMSE (cycles) | R² Score |
|---------|-------------|--------------|---------|
| FD001   | 10.73       | 14.63        | 0.8726  |
| FD002   | 13.82       | 21.03        | 0.8346  |
| FD003   | 9.80        | 13.51        | 0.8893  |
| FD004   | 14.65       | 21.02        | 0.8355  |

---

## 🔬 Novel Contributions

⭐ Proposed **GEBiLSTM-Attn architecture**  
⭐ Introduced **Gated Feature Enhancement Layer**  
⭐ Improved RUL prediction performance on CMAPSS dataset  
⭐ Built end-to-end pipeline from preprocessing to evaluation  

---

## 👩‍💻 Author Contribution

- Designed and proposed **GEBiLSTM-Attn architecture**  
- Built complete deep learning pipeline from scratch  
- Implemented preprocessing, training, and evaluation  
- Conducted experiments and performance analysis  

---

## 🔗 Future Work

- Extend architecture with **Transformer-based hybrid models**  
- Build **real-time predictive maintenance systems**  
- Deploy as scalable API for industrial applications
