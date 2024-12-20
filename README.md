# Fetal Health Classification with TPOT AutoML

This project leverages [TPOT](http://epistasislab.github.io/tpot/), a Python-based automated machine learning (AutoML) tool, to classify fetal health conditions based on a dataset. The notebook automates the process of selecting and optimizing machine learning pipelines.

## Overview

The notebook includes:
- Loading and preprocessing the dataset.
- Splitting the dataset into training and testing subsets.
- Configuring and running a `TPOTClassifier` to automate model optimization.
- Evaluating the best model generated by TPOT on test data.

## Features

- **Dataset**: A CSV file (`fetal_health classification project.csv`) containing data for fetal health classification.
- **Automated ML**: TPOT is used to explore and optimize pipelines.
- **Model Evaluation**: Accuracy is used as the primary evaluation metric.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```
## Install Required Dependencies

Run the following command to install the necessary Python libraries:
    ```bash
    pip install pandas numpy scikit-learn tpot
    ```
## Usage

1. Place the dataset file (`fetal_health classification project.csv`) in the same directory as the notebook.
2. Launch the Jupyter Notebook by running:

    ```bash
    jupyter notebook TPOT.ipynb
    ```

3. Follow the steps in the notebook to:
   - Load the dataset.
   - Split it into training and testing sets.
   - Use TPOT to find the best machine learning pipeline.
## Results

The notebook provides the following outputs:
- The **best pipeline model** discovered by TPOT.
- The **accuracy score** of the pipeline when tested on unseen data.
## Dependencies

This project requires the following software and Python libraries:

- **Python**: Version 3.9 or higher
- `pandas`
- `numpy`
- `scikit-learn`
- `tpot`

## Acknowledgements

- **TPOT**: [http://epistasislab.github.io/tpot/](http://epistasislab.github.io/tpot/)
- **Scikit-learn**: [https://scikit-learn.org/](https://scikit-learn.org/)


