# Beyond the Diagnosis

![Beyond the Diagnosis — Machine Learning for Diabetes Progression Prediction](Beyond%20the%20Diagnosis%20\(cover\).png)

## 🇬🇧 English

### Overview

Beyond the Diagnosis explores how Machine Learning can be used to analyze clinical data and predict diabetes progression one year ahead.

Using the Diabetes dataset from scikit-learn, the project develops an interpretable regression workflow that moves from exploratory data analysis to model validation, regularization, and clinical feature interpretation.

Rather than focusing exclusively on maximizing predictive performance, the project emphasizes methodological robustness and interpretability, particularly relevant in healthcare, where understanding how a model reaches its predictions can be as important as the predictions themselves.

### Machine Learning Workflow

The project includes:

- Exploratory Data Analysis (EDA) of disease progression and clinical features
- Analysis of feature relevance and multicollinearity
- Linear Regression as an interpretable baseline model
- Ridge Regression for regularization and coefficient stability
- Hyperparameter optimization using GridSearchCV
- Cross-validation for more robust performance assessment
- Evaluation using MAE, RMSE, and R²
- Residual analysis to investigate prediction errors
- Model coefficient interpretation to identify influential clinical variables

The analysis highlights body mass index and triglyceride-related measurements among the strongest predictors while showing that regularization can improve model stability without necessarily improving every performance metric simultaneously.

### Presentation

> 🇬🇧 [View the Presentation in English](Beyond%20the%20Diagnosis%20(ENG).pdf)
> 
> 🇮🇹 [View the Presentation in Italian](Beyond%20the%20Diagnosis%20(ITA).pdf)

### Notebook

The Jupyter Notebook contains the complete Machine Learning workflow, from data exploration and preprocessing to model training, regularization, validation, evaluation, and interpretation.

> 📓 [Open the Notebook](BeyondtheDiagnosisMLI.ipynb)

### Dataset

The project uses the Diabetes dataset available through scikit-learn, containing 442 observations and 10 standardized clinical features used to predict disease progression one year after baseline.

> 📊 [Open the Dataset](diabetes_dataset.csv)

### Technologies

`Python` · `Jupyter Notebook` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn`

---

## 🇮🇹 Italiano

### Panoramica

Beyond the Diagnosis esplora come il Machine Learning possa essere utilizzato per analizzare dati clinici e prevedere la progressione del diabete a un anno di distanza.

Utilizzando il Diabetes dataset di scikit-learn, il progetto sviluppa un workflow di regressione interpretabile che parte dall'analisi esplorativa dei dati e arriva alla validazione del modello, alla regolarizzazione e all'interpretazione delle variabili cliniche.

Più che concentrarsi esclusivamente sulla massimizzazione delle performance predittive, il progetto pone particolare attenzione alla robustezza metodologica e all'interpretabilità, aspetti particolarmente rilevanti in ambito sanitario.

### Workflow di Machine Learning

Il progetto comprende:

- Exploratory Data Analysis (EDA) della progressione della malattia e delle variabili cliniche
- Analisi della rilevanza delle feature e della multicollinearità
- Linear Regression come modello baseline interpretabile
- Ridge Regression per la regolarizzazione e la stabilità dei coefficienti
- Ottimizzazione degli iperparametri tramite GridSearchCV
- Cross-validation per una valutazione più robusta delle performance
- Valutazione tramite MAE, RMSE e R²
- Analisi dei residui per individuare gli errori di previsione
- Interpretazione dei coefficienti per identificare le variabili cliniche più influenti

L'analisi evidenzia l'indice di massa corporea e le misurazioni legate ai trigliceridi tra i predittori più rilevanti, mostrando inoltre come la regolarizzazione possa migliorare la stabilità del modello senza necessariamente migliorare ogni metrica di performance.

### Presentazione

> 🇬🇧 [Visualizza la presentazione in Inglese](Beyond%20the%20Diagnosis%20(ENG).pdf)
> 
> 🇮🇹 [Visualizza la presentazione in Italiano](Beyond%20the%20Diagnosis%20(ITA).pdf)

### Notebook

Il Jupyter Notebook contiene l'intero workflow di Machine Learning, dall'esplorazione e preparazione dei dati fino al training, alla regolarizzazione, alla validazione, alla valutazione e all'interpretazione del modello.

> 📓 [Apri il Notebook](BeyondtheDiagnosisMLI.ipynb)

### Dataset

Il progetto utilizza il Diabetes dataset disponibile in scikit-learn, composto da 442 osservazioni e 10 feature cliniche standardizzate utilizzate per prevedere la progressione della malattia a un anno di distanza.

> 📊 [Apri il Dataset](diabetes_dataset.csv)

### Tecnologie

`Python` · `Jupyter Notebook` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn`
