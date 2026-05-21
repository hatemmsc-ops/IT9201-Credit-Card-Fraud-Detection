# Credit Card Fraud Detection — IT9201 Machine Learning and Data Mining

**Student:** Hatem Isa | ID: 202508993 | Programme: ICT9010
**Course:** IT9201 Machine Learning and Data Mining
**Institution:** Bahrain Polytechnic, MSc Artificial Intelligence
**Supervisor:** Dr. Shomona Gracia Jacob

---

## Project Overview

This project applies supervised machine learning to detect fraudulent credit card transactions.
Three algorithms are compared: Logistic Regression, Random Forest, and Gradient Boosting.
The workflow is implemented in both Python (Jupyter Notebook) and Orange 3 (no-code tool).

---

## Key Results

| Model | AUC | F1 (Fraud) | Precision (Fraud) |
|---|---|---|---|
| Logistic Regression | 0.974 | N/A | N/A |
| Random Forest | N/A | 0.851 | 0.937 |
| Gradient Boosting | Underperformed | N/A | N/A |

Statistical comparison (LR vs RF): p = 0.003, confirming a significant difference.
Evaluation strategy: 5-fold stratified cross-validation.

---

## Repository Structure

```
├── Notebook(s).zip                                      # Jupyter notebook + Orange 3 workflow
├── Viva Presentation.zip                                # Viva slides PDF
├── Weekly Log.zip                                       # Weekly progress log
├── IT9201_202508893_Report.pdf                          # Final project report
├── dataset_download.txt                                 # Instructions to obtain the dataset
└── README.md
```

---

## Dataset

The dataset is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
It is not included in this repository due to file size (284,807 transactions, 32 MB+).
See `dataset_download.txt` for download instructions.

---

## How to Run

1. Download the dataset and place `creditcard.csv` in the same directory as the notebook.
2. Extract `Notebook(s).zip` and open `IT9201_Credit_Card_Fraud_Detection.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells in order.
4. To view the no-code workflow, open the `.ows` file in Orange 3.

### Dependencies

```
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
```

Install via:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

---

## Generative AI Use

This project used the following AI tools in accordance with course guidelines:

- **Claude (Anthropic)** — code debugging, report structuring, and workflow guidance
- **Perplexity AI** — literature search and source verification

All AI-assisted content was reviewed, verified, and edited by the student.
