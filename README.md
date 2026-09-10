# portfolio-DS-ML-AI
project portfolio

1. Repository Folder Structure
Set up a clean, modular repository named laser-defect-inspection-ml
:
laser-defect-inspection-ml/
├── data/
│   ├── raw/                      # Original LMD sensor CSV
│   └── processed/                # Feature-engineered dataset
├── notebooks/
│   └── 01_exploratory_analysis.ipynb
├── src/
│   ├── __init__.py
│   ├── data_pipeline.py          # Ingestion, validation & physical feature engineering
│   ├── train.py                  # Model training (XGBoost / Random Forest) & CV
│   └── evaluate.py               # SHAP feature importance calculation
├── app/
│   └── main.py                   # Interactive Streamlit dashboard
├── tests/
│   └── test_pipeline.py          # Automated PyTest unit tests
├── models/
│   └── defect_classifier_v1.pkl  # Trained model binary
├── Dockerfile                    # Container configuration
├── requirements.txt              # Dependency versions
└── README.md                     # Executive summary & execution guide
