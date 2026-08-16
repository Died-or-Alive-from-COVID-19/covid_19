# COVID-19 Mortality Prediction

Machine learning project that predicts whether a patient in the COVID-19 dataset died.

> **For learning only.** This project is intended for educational use and experimentation, not for real-world clinical decision-making or deployment.

![COVID-19 illustration](images/covid.webp)

## Dataset

The data is the [COVID-19 Dataset on Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data).
The notebook creates a binary target named `DIED`:


## Project structure

```text
.
├── data/
│   └── covid.csv
├── images/
│   ├── covid.webp
│   ├── earth.webp
├── model/
└── README.md
└── requirements.txt
```

## Setup & Run locally

```bash
git clone https://github.com/ahmed4mohamed4/covid_19.git
cd covid_19
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt 
```
