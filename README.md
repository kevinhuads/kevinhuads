# Data Science & MLOps portfolio

## Deep Learning

### [End-to-end deep vision workflow (Food-101)](https://github.com/kevinhuads/deepvision-workflow)

Deep learning computer vision workflow on the Food-101 dataset, from exploratory analysis to deployment, built with an MLOps-first mindset.

- Multi-class image classification on 101 food categories (~101 000 images).
- Systematic benchmark of modern architectures (CNNs and Vision Transformers) under frozen and fine-tuning regimes.
- MLOps stack with MLflow integration, a Streamlit inference application, Docker/Docker Compose and CI/CD with GitHub Actions.
- Reproducible, production-oriented structure (configs, src, tests, pinned dependencies).

## Classic Machine Learning

Smaller but complete Kaggle competition workflows covering EDA, modeling and interpretation.

- [Bank term-deposit classification (binary)](https://github.com/kevinhuads/classification-bank-deposit): Predicts whether a customer subscribes to a term deposit using campaign, demographic and behavioral features, with stratified cross-validation, feature engineering and SHAP-based interpretation.

- [Podcast listening time regression](https://github.com/kevinhuads/regression-podcast-time): Regression pipeline to predict podcast listening time from episode and show metadata, using K-fold CV, compact model ensembles and diagnostic analysis (residuals, SHAP, calibration).
