
pip install pyfatiguepro

# PyFatiguePro-libaray
PyFatiguePro integrates experimental fatigue data and FEA-derived stress fields with physics-based models (Basquin, Coffin–Manson, Paris Law) and machine learning to enable accurate, explainable, and deployable fatigue life prediction systems.

# 🚀 PyFatiguePro
### Physics-Informed Fatigue Life Prediction Library

A production-ready Python library integrating **fatigue mechanics + machine learning + FEA + deployment**

---

## ⚠️ Problem
Fatigue failure is a critical issue in aerospace and structural engineering.

- Classical models → limited for complex materials  
- ML models → lack physical interpretability  

---

## ✅ Solution
PyFatiguePro combines:

- Physics-based fatigue models  
- Machine learning  
- Real experimental data workflows  

---

## 🔧 Features

- Basquin S-N model  
- Coffin–Manson fatigue  
- Paris Law crack growth  
- Goodman / Gerber corrections  
- Multiaxial fatigue (von Mises)  
- FEA stress ingestion  
- ML models (RF, GPR)  
- SHAP explainability  
- Uncertainty estimation  
- FastAPI REST API  
- Docker deployment  

---

## 📊 Results


## ⚡ Installation

```bash
pip install pyfatiguepro


1. DATA SOURCES
   ├── Experimental fatigue data
   ├── Proprietary test data
   ├── Literature datasets
   └── FEA simulation output
              ↓

2. DATA INGESTION
   ├── CSV / Excel loading
   ├── Abaqus / ANSYS stress export loading
   ├── Standard column mapping
   └── Unit consistency checks
              ↓

3. DATA VALIDATION
   ├── Required-column check
   ├── Missing-value check
   ├── Duplicate removal
   ├── Non-physical value removal
   └── Data provenance tagging
              ↓

4. DATA SECURITY
   ├── Specimen ID anonymization
   ├── Project/customer masking
   ├── Batch ID hashing
   └── Safe proprietary-data workflow
              ↓

5. FEA FEATURE EXTRACTION
   ├── S11, S22, S33, S12, S23, S13
   ├── Von Mises stress calculation
   ├── Hotspot stress extraction
   ├── vm_max, vm_mean, vm_p95, vm_p99
   └── Merge with fatigue-test data
              ↓

6. PHYSICS FEATURES
   ├── Stress amplitude
   ├── Mean stress
   ├── R-ratio
   ├── Temperature
   ├── Grain size
   ├── Goodman correction
   ├── Gerber correction
   └── log10(cycles)
              ↓

7. CLASSICAL FATIGUE MODELS
   ├── Basquin S-N model
   ├── Coffin–Manson strain-life model
   ├── Paris Law crack-growth model
   └── Von Mises multiaxial fatigue input
              ↓

8. MACHINE LEARNING MODELS
   ├── Random Forest
   ├── HistGradientBoosting
   ├── Gaussian Process Regression
   ├── Train/test split
   ├── Batch-aware validation
   └── Model comparison
              ↓

9. VALIDATION & BENCHMARKING
   ├── MAPE
   ├── R²
   ├── RMSE
   ├── MAE
   ├── Parity plot
   └── ML vs Basquin benchmark
              ↓

10. EXPLAINABILITY & UNCERTAINTY
    ├── SHAP feature importance
    ├── Sensitivity analysis
    ├── Prediction intervals
    └── Confidence bounds
              ↓

11. DEPLOYMENT
    ├── Save model.joblib
    ├── FastAPI REST API
    ├── Batch CSV prediction
    ├── Docker container
    └── GitHub Actions CI/CD
              ↓

12. USER OUTPUT
    ├── Predicted fatigue life
    ├── Lower / upper 95% bounds
    ├── Key controlling features
    ├── Validation report
    └── Engineering decision support

    
