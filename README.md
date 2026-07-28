# An Explainable Fake News Detection Framework Using Fine-Tuned BERT with LIME

## Project Overview

This repository presents the implementation of my MPhil research project, which focuses on detecting fake news using Machine Learning and Deep Learning techniques. The project compares the performance of Logistic Regression and Fine-Tuned BERT while applying LIME (Local Interpretable Model-Agnostic Explanations) to make the model predictions more transparent and understandable.

---

## Objectives

- Detect fake and real news articles.
- Compare the performance of Logistic Regression and Fine-Tuned BERT.
- Improve model transparency using LIME.
- Evaluate models using standard performance metrics.

---

## Dataset

**Dataset Name:** WELFake Dataset

The WELFake dataset contains labelled news articles classified into two categories:
- Real News
- Fake News

The dataset was used for training and evaluating both Machine Learning and Deep Learning models.

**Source:** WELFake Dataset (Kaggle)

---

## Models Implemented

- Logistic Regression (Baseline Model)
- Fine-Tuned BERT
- LIME Explainability

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Hugging Face Transformers
- PyTorch
- LIME

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Repository Structure

```text
explainable-fake-news-detection/
│
├── README.md
├── LICENSE
├── requirements.txt
├── 01_Logistic_Regression.ipynb
├── 02_BERT_Model.ipynb
├── 03_LIME_Explainability.ipynb
├── docs/
│   └── README.md
└── results/
    └── README.md
```

---

## Results

The Fine-Tuned BERT model achieved better classification performance than the Logistic Regression baseline model. LIME was used to explain individual predictions and improve the interpretability of the proposed framework.

---

## Future Work

Future research can explore:
- RoBERTa
- DeBERTa
- Multilingual Fake News Detection
- Explainable Large Language Models (LLMs)

---

## Author

**Khadija Rameen**

MPhil Data Science

Superior University, Lahore, Pakistan

---

## License

This repository is created for academic and research purposes. The code is released under the MIT License.
