# Yusuf Abdulbaqi Onaopemipo

**Machine Learning Engineer** focused on building complete, deployable ML systems from data cleaning and rigorous model comparison through to production-ready APIs and applications.

My approach emphasizes **evidence based model selection over assumption**: several projects below document cases where a simpler model outperformed a more complex one, or where a deeper investigation uncovered a labeling or data-quality issue that no amount of tuning could fix. I treat that kind of finding as a deliverable in itself, not a shortcoming.

---

## Featured Projects

### [Opay Review Sentiment Classifier](https://github.com/baqius/opay-sentiment-bert-vs-rf)
Sentiment classification system for fintech app reviews, comparing a fine-tuned BERT model against a TF-IDF + Random Forest baseline. Identified and documented a labeling-scheme limitation (star ratings conflating "neutral" with "mixed sentiment") that explained a performance ceiling neither model could overcome through tuning alone. Deployed as a Streamlit application and a FastAPI service with automated tests, containerized with Docker.

**Live demo:** https://opay-sentiment-bert-vs-rf.streamlit.app/
**Stack:** PyTorch, Transformers, scikit-learn, FastAPI, Docker, pytest

---

### [Abeokuta 7-Day Weather Forecast](https://github.com/baqius/abeokuta-weather-forecast)
Multi-step temperature forecasting system using a GRU neural network trained on nine years of historical weather data. Outperformed both a persistence baseline and a rolling-mean baseline on mean absolute error, with a deployed dashboard providing live forecasts and seasonally-aware recommendations.

**Live demo:** https://opay-sentiment-bert-vs-rf.streamlit.app/
**Stack:** PyTorch, Streamlit, Visual Crossing API

---

### [AnimalPedia](https://github.com/baqius/animalpedia)
Image classification system identifying 90 animal species via a fine-tuned EfficientNet-B1 model (87% test accuracy), combined with a searchable reference database. Includes a documented breakdown of model strengths and failure modes by species category.

**Live demo:** https://opay-sentiment-bert-vs-rf.streamlit.app
**Stack:** PyTorch, torchvision, Streamlit

---

### [Fitness Predictor](https://github.com/baqius/baqius-fitness-predictor)
End-to-end health classification system predicting individual fitness status from biometric and lifestyle data, with SHAP-based explainability behind every prediction and a personalized recommendation engine. Model selection was driven by ROC-AUC and generalization behavior rather than raw accuracy, given the asymmetric cost of false negatives in a health context.

**Live demo:** https://baqiusfitnesspredictor.streamlit.app/
**Stack:** scikit-learn, XGBoost, SHAP, Streamlit

---

### [Face Detection and Recognition Pipeline](https://github.com/baqius/face-recognition-celebrities)
Few-shot face recognition system built on MTCNN for detection and a VGGFace2-pretrained embedding model for identity matching — achieving working recognition from as few as five reference images per identity, with no model training required.

**Stack:** PyTorch, facenet-pytorch, OpenCV

---

### [Credit Card Customer Segmentation](https://github.com/baqius/credit-card-clustering)
Unsupervised segmentation of approximately 9,000 credit card holders into four behavioral clusters using K-Means, with each segment translated into a concrete business recommendation (retention, re-engagement, upsell strategy).

**Stack:** scikit-learn, Plotly

---

## Technical Skills

| Category | Tools |
|---|---|
| Languages | Python, SQL |
| Machine Learning | scikit-learn, XGBoost, SHAP |
| Deep Learning | PyTorch, Hugging Face Transformers, torchvision |
| Deployment | Streamlit, FastAPI, Docker |
| Data | pandas, NumPy |
| Testing | pytest |

## Approach

- Compare multiple modeling approaches before committing to one, and report results honestly including when the simpler model wins
- Investigate root causes behind model limitations rather than treating metrics as final answers
- Ship working, interactive deliverables (live apps, documented APIs) rather than notebooks alone
- Write clear documentation aimed at both technical and non-technical stakeholders

## Contact

**Email:** abdulbaqionaopemipo@gmail.com
**LinkedIn:** www.linkedin.com/in/abdulbaqi-onaopemipo
