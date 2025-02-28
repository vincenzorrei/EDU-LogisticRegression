# Logistic Regression Study: From Binary to Multiclass

This repository contains an in-depth study on **logistic regression**, covering both **binary classification** and **multiclass classification** scenarios. Additionally, it explores the **class imbalance problem** and techniques to handle it. The study is conducted using two different Jupyter notebooks:

## Notebooks

1. **default.ipynb** - Investigates the classical binary logistic regression case.
2. **multiclass.ipynb** - Explores logistic regression for multiclass classification problems, along with strategies for handling imbalanced data.

## Installation

To replicate this project, ensure you have Python installed. It is recommended to use a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

Then, install the required dependencies using:

```bash
pip install -r requirements.txt
```

This will install all necessary libraries used in the Jupyter notebooks.

## Usage

Once dependencies are installed, you can open and run the notebooks using Jupyter:

```bash
jupyter notebook
```

Then, navigate to the desired notebook and execute the cells.

## Repository Structure
```
.
├── default.ipynb
├── multiclass.ipynb
├── slide_graphs.ipynb
├── requirements.txt
├── .gitignore
├── data/  # Contains datasets (ignored in git)
├── .venv/  # Virtual environment (ignored in git)
└── README.md
```

## .gitignore
```
data/
.venv/
```

## License
This project is provided for educational purposes. Feel free to modify and use it as needed.

---

Happy coding!

