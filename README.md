# Purpose

Written as part of a submission for [CleanTech Challenege (2025)](https://www.instagram.com/ncec_ntu/p/DG2JyFhxrHW/), this set of Jupyter notebooks uses [Long Short Term Memory](https://www.geeksforgeeks.org/deep-learning-introduction-to-long-short-term-memory/) to predict future [irradiance](https://en.wikipedia.org/wiki/Irradiance) values from past data

Find the full presentation [here!](https://www.canva.com/design/DAGi_88RTd0/zn4wtPOmw7bppFR03nttXA/edit?utm_content=DAGi_88RTd0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

# Breakdown

* LSTM_V1 is written as a simple proof-of-concept, to conduct basic data-preprocessing and test out baseline LSTM effectiveness 

* LSTM_v2 is a refinement, using more features (10 instead of 6) and adding cyclical time encoding to the model 

* Checkpoints have been included intentionally so that users can observe the difference in performance between the 2 notebooks

# Getting Started

1. Clone the repository 
```bash
$ git clone https://github.com/Ava-Vispilio/irradiance-prediction
$ cd irradiance-prediction
```

2. Create a virtual environment
```bash
$ python -m venv venv
source venv/bin/active # macOS
venv\Scripts\activate # Windows
```

3. Install dependencies
```bash
$ pip install -r requirements.txt 
```

4. Launch Jupyterlab
```bash
$ jupyter lab
```

# Reference

[AI-based solar photovoltaic power forecasting (Wang Yichen, 2022)](https://dr.ntu.edu.sg/entities/publication/1f418460-63a6-4aac-8567-217fff621ea1)
