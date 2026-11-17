# MachineLearningProjects

A collection of hands-on machine learning projects covering foundational supervised and unsupervised learning, dimensionality reduction, and neural networks. The repository is primarily made up of Jupyter notebooks, including an MLP exercise related to object avoidance in an Arduino autonomous vehicle.

---

## Table of Contents

- [Projects](#projects)
- [Highlights](#highlights)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Repository Structure](#repository-structure)
- [Final Project](#final-project)

---

## Projects

| Project | Topics | Notebook / Materials |
| --- | --- | --- |
| 1 — Linear Regression | Batch gradient descent, normalization, learning-rate selection, and housing-price prediction | [`Assignment_linear_regression.ipynb`](Project%201%20-%20LinearRegression/Assignment_linear_regression.ipynb) |
| 2 — Logistic Regression | Binary classification with the Iris dataset and gradient descent | [`Assignment_logistic_resgression.ipynb`](Project%202%20-%20Logistic_regression/Assignment_logistic_resgression.ipynb) |
| 3 — Bayes Decision-Theoretic Classifier | Gaussian discriminant analysis, class-specific covariance matrices, and validation accuracy | [`Assignment_discriminant_analysis.ipynb`](Project%203%20-%20Bayes%20Decision%20Theoretic%20Classifier/Assignment_discriminant_analysis.ipynb) |
| 4 — K-means | Unsupervised clustering, centroid updates, and cluster visualization | [`Assignment_Kmeans.ipynb`](Project%204%20-%20K-means/Assignment_Kmeans.ipynb) |
| 5 — PCA | Eigen-decomposition, dimensionality reduction, reconstruction, and classification evaluation | [`Assignment_pca.ipynb`](Project%205%20-%20PCA/Assignment_pca.ipynb) |
| 6 — RoboCar | Training a small multilayer perceptron and exporting its weights | [`Assignment_TrainMLP.ipynb`](Project%206%20-%20RoboCar/Assignment_TrainMLP.ipynb) · [`MLP_weights.csv`](Project%206%20-%20RoboCar/MLP_weights.csv) |

The notebooks include exercises, implementations, or demonstrations using datasets such as Iris and housing-price data. See each notebook for its assumptions, data requirements, and results.

---

## Highlights

- Practice implementing core machine learning algorithms in Python.
- Explore both supervised learning (regression and classification) and unsupervised learning (clustering and PCA).
- Inspect training, validation, and visualization workflows in interactive notebooks.
- Train a compact neural network and save its learned weights as CSV data.
- Review final-project materials on resource-efficient edge vision in [`FinalProject/`](FinalProject/).

---

## Tech Stack

- Python 3
- Jupyter Notebook
- NumPy and pandas
- Matplotlib
- scikit-learn (used in select notebooks for data splitting and evaluation)

---

## Getting Started

### Requirements

Install Python 3 and Jupyter Notebook or JupyterLab. The notebooks use common scientific Python packages; some notebooks also use scikit-learn.

```bash
python -m pip install jupyter numpy pandas matplotlib scikit-learn
```

### Run the notebooks

1. Clone the repository:

   ```bash
   git clone https://github.com/cjr03/MachineLearningProjects.git
   cd MachineLearningProjects
   ```

2. Start Jupyter:

   ```bash
   jupyter notebook
   ```

3. Open a project folder and run its notebook. Keep the notebook and its accompanying CSV data file in the same folder so relative data paths resolve correctly.

Some notebooks contain Google Colab-specific upload or download cells. If running locally, use the data files already included in the corresponding project folder and skip or adapt those Colab-only cells as needed.

---

## Usage

- Choose a project from the table above and open its notebook.
- Read the notebook instructions and run cells from top to bottom.
- Review the outputs, plots, and evaluation results; edit the implementation cells to experiment with model behavior.
- For the RoboCar MLP notebook, the trained weights are also provided in `Project 6 - RoboCar/MLP_weights.csv`.

---

## Repository Structure

```text
MachineLearningProjects/
├── FinalProject/                              # Edge-vision project reports and artifacts
├── Project 1 - LinearRegression/              # Regression notebook and plot
├── Project 2 - Logistic_regression/           # Logistic regression notebook and Iris data
├── Project 3 - Bayes Decision Theoretic Classifier/
│                                               # Discriminant analysis notebook and datasets
├── Project 4 - K-means/                       # Clustering notebooks and Iris data
├── Project 5 - PCA/                           # PCA notebook and Iris data
└── Project 6 - RoboCar/                       # MLP training notebook and exported weights
```

---

## Final Project

The [`FinalProject/`](FinalProject/) folder contains a presentation, project reports, an adaptive-resolution image, and an ONNX model related to **Optimizing Neural Network Resource-Efficiency for Edge Vision**. Refer to the included documents for project details.
