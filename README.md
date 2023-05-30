SkyDefender: Advanced Object Detection for Military Aircrafts
==============================
### Overview
SkyDefender is an impressive computer vision project developed as part of our Advanced Programming in Artificial Intelligence course. It serves as a comprehensive exploration of the field, allowing us to delve deep into various aspects of computer vision and gain valuable insights. With SkyDefender, we aimed to accomplish the following key objectives:

- **Data Analysis Libraries:** SkyDefender provided us with a unique opportunity to enhance our skills in data manipulation, with a specific focus on utilizing popular libraries like pandas. We honed our abilities in handling datasets by performing crucial tasks such as:
    - Removing null values from the dataset
    - Understanding the dataset we have
    - Value-type conversion
    - Data split in a balanced way (for train and test purposes)

- **Data Representation:** SkyDefender empowered us to represent our dataset in a highly accurate and insightful manner. We extensively explored different techniques to visualize and analyze the data, enabling us to gain a deeper understanding of how to train our models effectively and identify areas for improvement.

- **A Marvelous Solution:** SkyDefender boasts meticulously trained deep learning models that have been fine-tuned to deliver exceptional performance. This ensures that our object detection capabilities remain robust and reliable even in the face of challenging environments, including low-light conditions, adverse weather, and complex backgrounds.


The project can be executed localy or in <a href="https://colab.research.google.com/github/marcgj/sky-defender/blob/main/notebooks/SkyDefender.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Google Colab"></a>

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
