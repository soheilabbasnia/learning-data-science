# Learning Data Science

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python: 3.10+](https://img.shields.io/badge/Python-3.10%2B-3776AB.svg?logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org)
[![Frameworks](https://img.shields.io/badge/Stack-Pandas%20%7C%20Scikit--Learn%20%7C%20PyTorch-orange.svg)](#)

English | [فارسی](README_FA.md)

A curated, practical curriculum and codebase of hands-on data science, statistical analysis, machine learning algorithms, and deep learning architectures with real-world datasets and reproducible Jupyter Notebooks.

---

## Overview

This repository is designed as a structured practical reference guide for data science practitioners and learners. It covers the full lifecycle of data analysis and predictive modeling — from initial exploratory data understanding and rigorous data cleaning to classical machine learning and modern neural network frameworks.

Key highlights:
- **Comprehensive Lifecycle**: End-to-end workflows structured around industry standards (understanding, cleaning, modeling, deep learning).
- **Interactive Jupyter Notebooks**: Self-contained notebooks with detailed visual explanations, code cells, and outputs.
- **Real-World Datasets**: Includes tabular datasets (diabetes, loans, customer segmentation) for realistic experimentation.
- **Multi-Framework Deep Learning**: Implements foundational neural networks from scratch in pure NumPy, as well as production pipelines in PyTorch and TensorFlow.

---

## Learning Modules Matrix

| Module | Core Concepts & Topics | Key Tools & Notebooks |
| :--- | :--- | :--- |
| [`data-understanding`](data-understanding/) | Exploratory data analysis (EDA), descriptive statistics, inferential statistics, data visualization | Matplotlib, Seaborn, Pandas, SciPy |
| [`data-preparation`](data-preparation/) | Missing value imputation, outlier detection, categorical encoding (dummies), normalization, deduplication | Pandas, Scikit-Learn Preprocessing |
| [`machine-learning`](machine-learning/) | Supervised learning (classification, regression), unsupervised learning (clustering, PCA) | Scikit-Learn, XGBoost |
| [`deep-learning`](deep-learning/) | Neural networks from scratch with NumPy, forward/backward propagation, modern deep learning architectures | NumPy, PyTorch, TensorFlow |

---

## Getting Started

### Prerequisites

- Python 3.9+ or Python 3.10+
- `pip` and `venv`

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/soheilabbasnia/learning-data-science.git
   cd learning-data-science
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab or Notebook**:
   ```bash
   jupyter lab
   ```

---

## Project Structure

```text
learning-data-science/
├── data-understanding/          # Statistical exploration & visual analysis
│   ├── data-visualization/
│   ├── descriptive-statistics/
│   └── inferential-statistics/
├── data-preparation/            # Data cleaning and feature engineering
│   ├── datasets/
│   ├── preprocessing/
│   └── *.ipynb                  # Missing values, outliers, normalization notebooks
├── machine-learning/            # Classical ML algorithms
│   ├── datasets/
│   ├── supervised-learning/
│   └── unsupervised-learning/
├── deep-learning/               # Neural network architectures
│   ├── datasets/
│   ├── tensorflow/
│   ├── torch/
│   └── nn-np.ipynb              # Neural network from scratch in NumPy
├── requirements.txt             # Python packages and environment specifications
└── LICENSE                      # Project license
```

---

## Contributing

Contributions, notebook improvements, and additional dataset examples are welcome!
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/new-algorithm-notebook`).
3. Commit your changes (`git commit -m 'Add notebook on Gradient Boosting'`).
4. Push to the branch (`git push origin feature/new-algorithm-notebook`).
5. Open a Pull Request.

---

## License

This project is licensed under the [MIT License](LICENSE).
Feel free to use the notebooks, code snippets, and datasets for your educational and research endeavors.

