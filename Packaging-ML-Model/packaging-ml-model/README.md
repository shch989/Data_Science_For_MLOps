## Directory structure
```
prediction_model

├── MANIFEST.in
├── prediction_model
│   ├── config
│   │   ├── config.py
│   │   └── __init__.py
│   ├── datasets
│   │   ├── __init__.py
│   │   ├── test.csv
│   │   └── train.csv
│   ├── __init__.py
│   ├── pipeline.py
│   ├── predict.py
│   ├── processing
│   │   ├── data_handling.py
│   │   ├── __init__.py
│   │   └── preprocessing.py
│   ├── trained_models
│   │   ├── classification.pkl
│   │   └── __init__.py
│   ├── training_pipeline.py
│   └── VERSION
├── README.md
├── requirements.txt
├── setup.py
└── tests
    ├── pytest.ini
    └── test_prediction.py
```
```
set PYTHONPATH=%PYTHONPATH%;C:\Users\user\Desktop\project\test\mlops\Packaging-ML-Model\packaging-ml-model
```
```
pip freeze > requirements.txt
```
```
python -m pip install virtualenv
```
```
virtualenv --version
```
```
virtualenv ml_package
```
```
/* Linux/Mac */
source ml_package/bin/activate
```
```
/* Windows */
ml_package\Scripts\activate
```
```
pip install -r requirements.txt
```