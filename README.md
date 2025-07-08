# Arrhythmia Prediction in AMI Patients

This project implements a 1-D CNN model to predict the likelihood of life-threatening ventricular arrhythmias in patients recovering from acute myocardial infarction (AMI), based on short-term ECG signal analysis. The model is trained and validated on publicly available PhysioNet datasets (MIT-BIH, PTB-XL) and aims to assist in early intervention through data-driven cardiac risk stratification.

## Highlights
- Uses single-lead ECG segments (2s windows)
- Binary classification: Arrhythmia in next 30 mins (yes/no)
- Preprocessing pipeline for MIT-BIH dataset
- CNN-based architecture with 90%+ AUC
- Ready for extension to PTB-XL and HRV-based models
