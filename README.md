
# Parkinson’s Disease Prediction using Echo State Network (ESN)

This project demonstrates the use of **Echo State Networks (ESN)** to classify individuals as having Parkinson's disease or not, based on biomedical voice measurements.

---

## 🧠 Overview

- **Model**: Echo State Network (Reservoir Computing)
- **Dataset**: Parkinson’s Telemonitoring dataset (`status` as target)
- **Features**: 4 selected features from the full dataset ([0, 18, 19, 21])
- **Library**: [easyesn](https://github.com/kalekiu/easyesn)

---

## 📁 Dataset

The dataset includes biomedical voice measurements from people with and without Parkinson’s Disease.

| Column | Description |
|--------|-------------|
| `status` | 1 = Parkinson's, 0 = Healthy |
| `MDVP:Fo(Hz)` | Fundamental frequency |
| `spread1`, `spread2`, `D2`, etc. | Signal processing features |
