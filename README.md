# Generative Molecular Property Prediction

A machine learning project that leverages generative models to design novel molecules and predict their physicochemical or biological properties. Integrates molecular representation learning, property prediction, and generative chemistry techniques to accelerate drug discovery and material science research.

## Project Organization

```
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── deployment         <- Serving, Docker, API, CI/CD, etc.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         generative_molecular_property_prediction and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── generative_molecular_property_prediction   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes generative_molecular_property_prediction a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    |
    ├── pipelines               <- End-to-end training / inference pipelines
    │   ├── __init__.py 
    │   ├── test_pipeline.py             
    │   └── train_pipeline.py   
    |
    ├── utils                   <- Helpers: logging, metrics, etc.
    │   ├── __init__.py 
    |   ├── model
    |   │   ├── __init__.py 
    │
    └── plots.py                <- Code to create visualizations
```

--------

