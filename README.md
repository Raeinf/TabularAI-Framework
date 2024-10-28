# TabularAI-Framework
## AI Competition and Tabular Data Analysis Framework

This project is a comprehensive framework for **AI competition and tabular data analysis**, designed to streamline the end-to-end machine learning workflow for structured data. It combines the capabilities of AutoML, manual model creation, ensemble methods, custom neural networks, and exploratory data analysis (EDA), making it adaptable for various machine learning tasks and competitions.

The framework is modular, with a clear directory structure (`input` for datasets, `working` for outputs), and includes everything from data loading and preprocessing to model evaluation. Key features include:

- **Data Loading & Preprocessing**: Utilities for loading datasets, handling missing values, encoding categorical features, and managing memory usage.
- **Exploratory Data Analysis (EDA)**: Tools for gaining insights into data distributions, visualizing relationships, detecting anomalies, and preparing data for modeling.
- **Feature Engineering**: Advanced techniques such as dimensionality reduction (PCA), recursive feature elimination (RFE), polynomial features, clustering, and geospatial distance calculations to enrich feature space.
- **Resampling**: Methods to address class imbalance using techniques like SMOTE, SMOTEENN, and under-sampling.
- **Model Training**:
  - **AutoML**: Integrated with AutoGluon’s `TabularPredictor` for automatic model selection and tuning.
  - **Manual Model Building**: Implements a variety of regression and classification algorithms, including Random Forest, XGBoost, LightGBM, and CatBoost.
  - **Custom Neural Networks**: Built with TensorFlow and tailored for both regression and classification tasks.
- **Model Ensembling & Stacking**: Combines model predictions through majority voting, averaging, and stacking methods, using a meta-learner to boost overall performance.
- **Hyperparameter Tuning**: Employs `Optuna` for efficient, automated hyperparameter optimization.
- **Evaluation Metrics**: Comprehensive evaluation across both classification (e.g., F1 Score, Precision, ROC AUC) and regression tasks (e.g., R2 Score, MSE, MAE).

This project provides flexibility, allowing users to quickly experiment with AutoML for fast prototyping or build custom models for more controlled experimentation. Its modular nature makes it ideal for competitions and rigorous data analysis, enabling streamlined workflows and high-performance modeling.

## Project Structure

```plaintext
├── input
│   └── data files and datasets (place your datasets here)
├── working
│   └── main.ipynb
├── requirements.txt
