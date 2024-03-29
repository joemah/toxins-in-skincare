# Toxins in Skincare

#### Project Status: [Development Status]

---
## Project Intro/Objective
Analysis of a [Skincare dataset](https://www.kaggle.com/code/kingabzpro/cosmetics-ingredients/data) from Kaggle & ML model of a recommendation machine.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies 
* Python
* Jupyter Notebook
* Libraries: Pandas, Statsmodels.api, Seaborn, Scikit, Matplotlib

## Project Description
<!-- (Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here) -->
This data science project uses a skincare dataset to find trends in the use of toxins in skincare products and builds a machine learning algorithm to recommend skincare products based on various factors. The algorithm takes into account the user's skin type, concerns, and allergies, as well as the ingredients in each product.
&rarr; **Research Notes:** [Notion](https://almondine-bedbug-4d3.notion.site/Toxins-in-Skincare-46051e770c60413f97ed509ea408dec6)

## Needs of this project

- Reference/help on [Github Issues](https://github.com/mahakanakala/toxins-in-skincare/issues)
- Explore more Ml models

## Getting Started
1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://github.com/mahakanakala/toxins-in-skincare/tree/main/data/raw)) within this repo.
3. Data processing/transformation scripts are being kept [here](https://github.com/mahakanakala/toxins-in-skincare/tree/main/data/processed) within this repo.
4. Data visuals are kept [here](https://github.com/mahakanakala/toxins-in-skincare/tree/main/reports/figures) within this repo.

*If the project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

<!-- 5. Follow setup [instructions](Link to file) -->

<!-- ## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link) -->

---

# Cookiecutter Modern Data Science (file structure manager)
[Cookiecutter] template for starting a Data Science project with modern, fast Python tools.

## Features
* [Pipenv] for managing packages and virtualenvs in a modern way.
* [Prefect] for modern pipelines and data workflow.
* [Weights and Biases] for experiment tracking.
* [FastAPI] for self-documenting fast HTTP APIs - on par with NodeJS and Go - based on [asyncio], [ASGI], and [uvicorn].
* Modern CLI with [Typer].
* Batteries included: [Pandas], [numpy], [scipy], [seaborn], and [jupyterlab] already installed.
* Consistent code quality: [black], [isort], [autoflake], and [pylint] already installed.
* [Pytest] for testing.
* [GitHub Pages] for the public website.

---

## Quickstart

Install the latest Cookiecutter and Pipenv:

    pip install -U pipenv cookiecutter

Generate the project structure:

    cookiecutter gh:crmne/cookiecutter-modern-datascience

Get inside the project:

    cd <repo_name>
    pipenv shell  # activates virtualenv

(Optional) Start Weights & Biases locally, if you don't want to use the cloud/on-premise version:

    wandb local

Start working:

    jupyter-lab

## Directory structure

This is our your new project will look like:

    ├── .gitignore                <- GitHub's excellent Python .gitignore customized for this project
    ├── LICENSE                   <- Your project's license.
    ├── Pipfile                   <- The Pipfile for reproducing the analysis environment
    ├── README.md                 <- The top-level README for developers using this project.
    │
    ├── data
    │   ├── 0_raw                 <- The original, immutable data dump.
    │   ├── 0_external            <- Data from third party sources.
    │   ├── 1_interim             <- Intermediate data that has been transformed.
    │   └── 2_final               <- The final, canonical data sets for modeling.
    │
    ├── docs                      <- GitHub pages website
    │   ├── data_dictionaries     <- Data dictionaries
    │   └── references            <- Papers, manuals, and all other explanatory materials.
    │
    ├── notebooks                 <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                                the creator's initials, and a short `_` delimited description, e.g.
    │                                `01_cp_exploratory_data_analysis.ipynb`.
    │
    ├── output
    │   ├── features              <- Fitted and serialized features
    │   ├── models                <- Trained and serialized models, model predictions, or model summaries
    │   └── reports               <- Generated analyses as HTML, PDF, LaTeX, etc.
    │       └── figures           <- Generated graphics and figures to be used in reporting
    │
    ├── pipelines                 <- Pipelines and data workflows.
    │   ├── Pipfile               <- The Pipfile for reproducing the pipelines environment
    │   ├── pipelines.py          <- The CLI entry point for all the pipelines
    │   ├── <repo_name>           <- Code for the various steps of the pipelines
    │   │   ├──  __init__.py
    │   │   ├── etl.py            <- Download, generate, and process data
    │   │   ├── visualize.py      <- Create exploratory and results oriented visualizations
    │   │   ├── features.py       <- Turn raw data into features for modeling
    │   │   └── train.py          <- Train and evaluate models
    │   └── tests
    │       ├── fixtures          <- Where to put example inputs and outputs
    │       │   ├── input.json    <- Test input data
    │       │   └── output.json   <- Test output data
    │       └── test_pipelines.py <- Integration tests for the HTTP API
    │
    └── serve                     <- HTTP API for serving predictions
        ├── Dockerfile            <- Dockerfile for HTTP API
        ├── Pipfile               <- The Pipfile for reproducing the serving environment
        ├── app.py                <- The entry point of the HTTP API
        └── tests
            ├── fixtures          <- Where to put example inputs and outputs
            │   ├── input.json    <- Test input data
            │   └── output.json   <- Test output data
            └── test_app.py       <- Integration tests for the HTTP API




[Cookiecutter]: https://github.com/audreyr/cookiecutter
[Pipenv]: https://pipenv.pypa.io/en/latest/
[Prefect]: https://docs.prefect.io/
[Weights and Biases]: https://www.wandb.com/
[MLFlow]: https://mlflow.org/
[FastAPI]: https://fastapi.tiangolo.com/
[asyncio]: https://docs.python.org/3/library/asyncio.html
[ASGI]: https://asgi.readthedocs.io/en/latest/
[uvicorn]: https://www.uvicorn.org/
[Typer]: https://typer.tiangolo.com/
[Pandas]: https://pandas.pydata.org/
[numpy]: https://numpy.org/
[scipy]: https://www.scipy.org/
[seaborn]: https://seaborn.pydata.org/
[jupyterlab]: https://jupyterlab.readthedocs.io/en/stable/
[black]: https://github.com/psf/black
[isort]: https://github.com/timothycrosley/isort
[autoflake]: https://github.com/myint/autoflake
[pylint]: https://www.pylint.org/
[Pytest]: https://docs.pytest.org/en/latest/
[GitHub Pages]: https://pages.github.com/
[Git LFS]: https://git-lfs.github.com/

