# AeroCare ✈️  
**Predictive Maintenance System for Aircraft Components**

AeroCare is a machine learning–based predictive maintenance project focused on **Remaining Useful Life (RUL) prediction** of aircraft engine components using multivariate time-series sensor data.

The goal of this repository is to analyze engine degradation patterns and accurately predict RUL using multiple machine learning and deep learning models trained on the **NASA C-MAPSS dataset**.

---

## 📌 Project Objective

- Predict **Remaining Useful Life (RUL)** of aircraft engines
- Utilize **sensor readings and operational settings**
- Compare performance of multiple ML & DL models
- Reduce unexpected failures through predictive maintenance

---

## 📊 Dataset

This project uses the **NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)** dataset.

**Dataset Characteristics:**
- Multivariate time-series data
- Operational settings
- Multiple sensor measurements
- Run-to-failure trajectories

📁 Dataset source:  
- [NASA C-MAPSS Dataset (Kaggle)](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)

---

## ⚙️ Methodology

The workflow followed in this project:

1. **Data Preprocessing**
   - Handling multiple engine units
   - Feature selection
   - Normalization & scaling

2. **Exploratory Data Analysis**
   - Sensor trend analysis
   - Degradation visualization

3. **Dimensionality Reduction**
   - Principal Component Analysis (PCA)

4. **Outlier Detection**
   - Identification of abnormal sensor behavior

5. **Model Training & Evaluation**
   - Regression-based ML models
   - Deep learning models (LSTM)
   - Performance comparison

---

## 🧠 Models Implemented

- Linear & Regression-based models
- Machine Learning algorithms
- **LSTM (Long Short-Term Memory)** networks for sequence learning
- PCA-enhanced models for dimensionality reduction

---

## 🛠 Skills & Tools Used

- **Python**
- **Data Analysis & Visualization**
- **Regression Analysis**
- **Machine Learning**
- **Deep Learning (LSTM)**
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 📈 Results & Insights

- Sensor degradation trends correlate strongly with RUL
- LSTM models capture temporal dependencies effectively
- PCA helps reduce dimensionality without major performance loss
- Predictive maintenance can significantly reduce failure risks

---

## 🔗 Acknowledgements

- [NASA C-MAPSS Dataset (Kaggle)](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps)
- [NASA Predictive Maintenance (RUL)](https://www.kaggle.com/code/wassimderbel/nasa-predictive-maintenance-rul)
- [Predictive Maintenance NASA Turbofan Regression](https://www.kaggle.com/code/carlkirstein/predictive-maintenance-nasa-turbofan-regression)

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Transformer-based sequence models
- Real-time RUL prediction pipeline
- Deployment using APIs or dashboards

---

## 👩‍💻 Author

**Hetvi**  
_Data Science & Machine Learning Enthusiast_
