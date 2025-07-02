# Prediction of Polish Holstein’s Economical Index & Calving Interval

This repository contains all data, analysis scripts, and results associated with:

> **Wełeszczuk J., Kosińska‑Selbi B., & Cholewińska P. (2022).** Prediction of Polish Holstein’s economical index and calving interval using machine learning. *Livestock Science*, 264, 105039.  
> doi:10.1016/j.livsci.2022.105039 :contentReference[oaicite:0]{index=0}

---

## 📖 Paper Summary

Machine learning models can help predict key economic indicators in livestock without the need for lengthy individual records. In this study, we:

- Collected data on the 1 000 best Polish Holstein heifers and 1 000 best cows using a custom Python scraper (BeautifulSoup 4.9.3 + Selenium 3.141.0). :contentReference[oaicite:1]{index=1}  
- Compared **white‑box** algorithms (Linear Regression, Decision Tree, KNN) vs. **black‑box** algorithms (Random Forest, Gradient Boosting, XGBoost, Neural Network). :contentReference[oaicite:2]{index=2}  
- Selected features via Recursive Feature Elimination with Cross‑Validation (REFCV) and evaluated using 5‑fold CV. :contentReference[oaicite:3]{index=3}  
- Achieved best EI predictions with a Neural Network (MAE 20.72; RMSE 29.35) and best CI predictions with Gradient Boosting (MAE 0.79; RMSE 1.27). :contentReference[oaicite:4]{index=4}

---

Python ≥ 3.8

pandas, scikit-learn, xgboost, tensorflow (or torch), selenium, beautifulsoup4

See requirements.txt for exact versions.

📝 Citation
If you use any part of this work, please cite:

Wełeszczuk J., Kosińska‑Selbi B., & Cholewińska P. (2022). Prediction of Polish Holstein’s economical index and calving interval using machine learning. Livestock Science, 264, 105039. doi:10.1016/j.livsci.2022.105039

