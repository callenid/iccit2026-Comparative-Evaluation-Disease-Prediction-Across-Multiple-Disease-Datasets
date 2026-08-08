# Medical Classification Datasets

This repository organizes public datasets used for machine-learning experiments involving obesity, breast cancer, heart disease, general symptom-based disease prediction, thyroid disease, and COVID-19 symptoms.

> **Important:** These datasets are intended for research and educational use. They must not be treated as a substitute for professional medical diagnosis, clinical validation, or medical advice.

## Dataset Overview

| Folder | Dataset | Primary source | Credit / donor |
|---|---|---|---|
| `datasets/obesity/` | Estimation of Obesity Levels Based On Eating Habits and Physical Condition | UCI Machine Learning Repository | Fabio Mendoza Palechor; Alexis de la Hoz Manotas |
| `datasets/breast_cancer/` | Breast Cancer Wisconsin (Diagnostic) | UCI Machine Learning Repository | William H. Wolberg; W. Nick Street; Olvi L. Mangasarian. Donor: Nick Street |
| `datasets/heart_disease/` | Heart Disease | UCI Machine Learning Repository | Andras Janosi; William Steinbrunn; Matthias Pfisterer; Robert Detrano. Historical UCI donor attribution: David W. Aha |
| `datasets/general_disease/` | Disease Prediction Using Machine Learning | Kaggle | Published/uploaded by KAUSHIL268 |
| `datasets/thyroid/` | Thyroid Disease | UCI Machine Learning Repository | Garavan Institute; documentation/creator attribution: Ross Quinlan |
| `datasets/covid19/` | COVID-19 Symptoms Checker | Kaggle | Bilal Hungund |

## Download

A helper script is included so the datasets can be downloaded into the correct folders.

```bash
python scripts/download_datasets.py all
```

You can also download datasets one at a time:

```bash
python scripts/download_datasets.py obesity
python scripts/download_datasets.py breast_cancer
python scripts/download_datasets.py heart_disease
python scripts/download_datasets.py general_disease
python scripts/download_datasets.py thyroid
python scripts/download_datasets.py covid19
```

### Kaggle requirement

For the two Kaggle datasets, install and configure the Kaggle CLI first:

```bash
pip install kaggle
```

Then configure your Kaggle API credentials according to Kaggle's official instructions. The download script uses the Kaggle CLI only for Kaggle-hosted datasets.

## Official Sources

### 1. Obesity

**Dataset:** Estimation of Obesity Levels Based On Eating Habits and Physical Condition  
**Authors:** Fabio Mendoza Palechor and Alexis de la Hoz Manotas  
**Repository:** UCI Machine Learning Repository  
**UCI page:** https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition  
**UCI dataset DOI:** https://doi.org/10.24432/C5H31Z  
**Associated article DOI:** https://doi.org/10.1016/j.dib.2019.104344  
**License:** CC BY 4.0

Recommended attribution:

> Palechor, F. M., & de la Hoz Manotas, A. (2019). *Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico*. Data in Brief, 25, 104344. https://doi.org/10.1016/j.dib.2019.104344

UCI dataset citation:

> *Estimation of Obesity Levels Based On Eating Habits and Physical Condition* [Dataset]. (2019). UCI Machine Learning Repository. https://doi.org/10.24432/C5H31Z

### 2. Breast Cancer Wisconsin (Diagnostic)

**Creators:** William H. Wolberg, W. Nick Street, and Olvi L. Mangasarian  
**Donor:** Nick Street  
**Repository:** UCI Machine Learning Repository  
**UCI page:** https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic  
**DOI:** https://doi.org/10.24432/C5DW2B  
**License:** CC BY 4.0

Recommended citation:

> Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). *Breast Cancer Wisconsin (Diagnostic)* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B

### 3. Heart Disease

**Original contributors:** Andras Janosi, William Steinbrunn, Matthias Pfisterer, and Robert Detrano  
**Historical UCI donor:** David W. Aha  
**Repository:** UCI Machine Learning Repository  
**UCI page:** https://archive.ics.uci.edu/dataset/45/heart+disease  
**DOI:** https://doi.org/10.24432/C52P4X  
**License:** CC BY 4.0

Recommended citation:

> Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). *Heart Disease* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X

### 4. General Disease / Symptom Prediction

**Dataset:** Disease Prediction Using Machine Learning  
**Publisher/uploader:** KAUSHIL268  
**Platform:** Kaggle  
**Source:** https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning  
**Files described by source:** `Training.csv` and `Testing.csv`  
**License shown on Kaggle:** Database: Open Database; Contents: Database Contents

Suggested attribution:

> KAUSHIL268. *Disease Prediction Using Machine Learning* [Dataset]. Kaggle. https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning

**Provenance note:** The Kaggle dataset page does not clearly identify an original research publication or original data creator. For academic work, cite the Kaggle dataset page and avoid describing KAUSHIL268 as the original clinical-data author unless additional provenance is independently verified.

### 5. Thyroid Disease

**Dataset:** Thyroid Disease  
**Data source:** Garavan Institute, Sydney, Australia  
**Documentation / creator attribution:** Ross Quinlan  
**Repository:** UCI Machine Learning Repository  
**UCI page:** https://archive.ics.uci.edu/dataset/102/thyroid+disease  
**DOI:** https://doi.org/10.24432/C5D010  
**License:** CC BY 4.0

Recommended citation:

> Quinlan, R. (1986). *Thyroid Disease* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5D010

### 6. COVID-19 Symptoms Checker

**Dataset:** COVID-19 Symptoms Checker  
**Publisher/uploader:** Bilal Hungund  
**Platform:** Kaggle  
**Source:** https://www.kaggle.com/datasets/iamhungundji/covid19-symptoms-checker  
**License shown on Kaggle:** GPL 2  
**Dataset description:** The uploader states that the variables were constructed around symptom guidance from the World Health Organization (WHO) and the Ministry of Health and Family Welfare, India.

Suggested attribution:

> Hungund, B. *COVID-19 Symptoms Checker* [Dataset]. Kaggle. https://www.kaggle.com/datasets/iamhungundji/covid19-symptoms-checker

