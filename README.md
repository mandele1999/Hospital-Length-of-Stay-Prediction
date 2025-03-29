# Hospital-Length-of-Stay-Prediction
This project leverages machine learning to predict the length of hospital stays for admitted patients based on patient data.

📁 hospital-length-of-stay-prediction
│── 📜 README.md                     # Project Overview & Instructions
│── 📜 requirements.txt               # Python Dependencies
│── 📜 .gitignore                     # Files to ignore in GitHub
│
├── 📁 data
│   ├── raw/                          # Original Dataset (DO NOT EDIT)
│   ├── processed/                     # Cleaned & Preprocessed Data
│
├── 📁 notebooks
│   ├── 01_EDA.ipynb                   # Exploratory Data Analysis
│   ├── 02_Feature_Engineering.ipynb    # Feature Selection & Transformation
│   ├── 03_Model_Training.ipynb         # Model Training & Evaluation
│   ├── 04_Hyperparameter_Tuning.ipynb  # Model Optimization
│
├── 📁 src
│   ├── data_preprocessing.py          # Script for cleaning data
│   ├── train_model.py                 # Model training pipeline
│   ├── inference.py                    # Model inference script
│
├── 📁 app
│   ├── app.py                         # Flask/Streamlit Web App
│   ├── static/                         # CSS, JS for UI
│   ├── templates/                      # HTML Files (if Flask)
│
├── 📁 reports
│   ├── project_report.pdf              # Business Report
│   ├── presentation.pdf                 # Slide Deck
│
└── 📁 models
    ├── final_model.pkl                 # Saved ML Model
    ├── model_metadata.json             # Model Details (Metrics, Features)
