# ⚡ Power System Fault Detection and Classification

This project aims to **detect and classify power system faults** using machine learning algorithms, with implementation and deployment on **IBM Watson Studio**. It leverages voltage and current phasor data to train classification models for reliable and real-time fault identification.

## 📁 Dataset

- **Source**: Kaggle – Power System Faults Dataset
- **Features**: Voltage and current measurements
- **Labels**: Fault types – LG, LL, DLG, 3Φ, and Normal
- **Preprocessing**:
  - Null handling
  - Feature scaling
  - Label encoding

## 🧠 Machine Learning Approach

- **Algorithms Used**: 
  - Random Forest
  - Logistic Regression
- **Pipeline Optimization**: 
  - Hyperparameter Tuning (HPO)
  - Feature Engineering
- **Best Pipeline**:
  - Random Forest Classifier (Pipeline 8)
  - Accuracy: 40.9% via cross-validation

## 🛠️ Tools & Technologies

- IBM Watson Studio
- IBM Watson Machine Learning
- IBM Cloud Object Storage
- Python (Pandas, Sklearn, Matplotlib)
- Jupyter Notebook

## 🚀 Deployment

- Model deployed via **IBM Watson Machine Learning**
- Real-time predictions enabled through REST API
- Notebook interface used for training, testing, and visualization

## 📊 Results

- Total Pipelines Generated: 8
- Insights: Further improvement possible via binary classification or enhanced feature selection.

## 🔮 Future Scope

- Include additional signal features
- Expand to fault **location** prediction
- Explore deep learning models (e.g., LSTM, CNN)
- Integrate edge computing for on-site fault detection


