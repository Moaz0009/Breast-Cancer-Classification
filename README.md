# Breast-Cancer-Classification

This repository contains a project focused on predicting the diagnosis of breast cancer using a Support Vector Machine (SVM) model. The analysis is performed on a breast cancer dataset, with the goal of accurately classifying tumors as malignant or benign.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis and Modeling](#analysis-and-modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Breast-Cancer-Classification project uses a Support Vector Machine (SVM) model to classify breast tumors based on features derived from digitized images of breast masses. The project focuses on data preprocessing, exploratory analysis, and the application of the SVM algorithm to achieve high accuracy in predictions.

## Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). It includes features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass, such as:

- **ID Number**: Patient ID
- **Diagnosis**: The diagnosis of the tumor (M = malignant, B = benign)
- **Features**: 30 numeric features describing characteristics of the cell nuclei, including mean, standard error, and worst (largest) values for each feature (e.g., `radius_mean`, `texture_mean`, `perimeter_mean`).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Moaz0009/Breast-Cancer-Classification.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Breast-Cancer-Classification
    ```
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    The `requirements.txt` file includes the following packages:
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `seaborn`
    - `scikit-learn`
    - `jupyter`

## Usage

To explore and run the analysis:

1. **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2. **Open the notebook:**
    In the Jupyter interface, open the `Breast Cancer.ipynb` file.
3. **Run the cells:**
    Execute the cells to perform the analysis, build the SVM model, and evaluate the predictions.

## Analysis and Modeling

The project includes the following steps:

- **Data Preprocessing:** Handling missing data, normalizing features, and encoding categorical variables.
- **Exploratory Analysis:** Visualizing feature distributions and understanding their relationship with the diagnosis.
- **Modeling:** Building and evaluating the Support Vector Machine (SVM) model.
- **Model Evaluation:** Assessing the model's performance using accuracy, precision, recall, and F1-score.

## Results

The SVM model achieved an accuracy of 97% on the test set, demonstrating its effectiveness in predicting whether a tumor is malignant or benign. Key features like `radius_mean`, `perimeter_mean`, and `area_mean` were found to be significant predictors of the diagnosis.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or find any issues, please feel free to fork the repository, create a branch, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
