# 🧠 Sentiment Analysis using RoBERTa, DeBERTa & TinyBERT

> **A transformer-based NLP project for understanding sentiment through three powerful language models — RoBERTa, DeBERTa, and TinyBERT — combined with LIME explainability.**

---

## 🌟 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) task that determines the emotional polarity of text, such as whether a piece of text expresses a **positive, negative, or other sentiment category**.

This project explores transformer-based approaches to sentiment classification using three different pretrained models:

- 🤖 **RoBERTa**
- 🚀 **DeBERTa**
- ⚡ **TinyBERT**

The project covers the complete sentiment-analysis workflow, including **data preparation, text preprocessing, exploratory data analysis (EDA), tokenization, model training, evaluation, prediction, and explainability using LIME**.

The implementations are organized into separate notebooks for each model.

---

## 🎯 Objectives

The main objectives of this project are:

- Perform text preprocessing for sentiment analysis.
- Explore and understand the dataset through **Exploratory Data Analysis (EDA)**.
- Implement sentiment classification using **RoBERTa**.
- Implement sentiment classification using **DeBERTa**.
- Implement sentiment classification using **TinyBERT**.
- Train and evaluate transformer-based sentiment classifiers.
- Compare model performance using evaluation metrics.
- Apply **LIME (Local Interpretable Model-agnostic Explanations)** to understand model predictions.
- Build an end-to-end sentiment analysis workflow using modern transformer architectures.

---

## 🔬 Models

| Model | Description |
|---|---|
| 🤖 **RoBERTa** | A robustly optimized transformer model based on BERT, used for sentiment classification. |
| 🚀 **DeBERTa** | An advanced transformer architecture designed to improve language understanding through disentangled attention and enhanced decoding. |
| ⚡ **TinyBERT** | A lightweight and compact transformer model designed to provide efficient NLP inference while retaining useful language understanding capabilities. |

---

## 🔄 Project Workflow

```text
                    📊 Dataset
                        │
                        ▼
              🧹 Data Preprocessing
                        │
                        ▼
                 🔍 EDA & Analysis
                        │
                        ▼
                  🔤 Tokenization
                        │
          ┌─────────────┼─────────────┐
          ▼             ▼             ▼
       RoBERTa       DeBERTa       TinyBERT
          │             │             │
          ▼             ▼             ▼
       Training       Training      Training
          │             │             │
          ▼             ▼             ▼
      Prediction     Prediction    Prediction
          │             │             │
          └─────────────┼─────────────┘
                        ▼
                📈 Model Evaluation
                        │
                        ▼
                 💡 LIME Explainability
```

---

## 🧹 Data Preprocessing

The notebooks contain the preprocessing workflow required to prepare the textual data for transformer-based sentiment classification.

The preprocessing stage prepares the raw textual information before it is passed to the tokenizers and transformer models.

---

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis (EDA) is included in the notebooks to understand the dataset before model training.

The analysis helps examine the characteristics and distribution of the sentiment data and provides a better understanding of the dataset used for classification.

---

## 💡 LIME Explainability

Model accuracy alone does not explain **why** a model made a particular prediction.

To make individual predictions more interpretable, this project uses:

### LIME — Local Interpretable Model-agnostic Explanations

LIME provides an interpretation of individual predictions by identifying parts of the input text that contribute to the model's decision.

Conceptually:

```text
Input Text
    │
    ▼
Transformer Model
    │
    ▼
Sentiment Prediction
    │
    ▼
      LIME
    │
    ▼
Important Words / Text Features
    │
    ▼
Human-Interpretable Explanation
```

This makes the sentiment classifier easier to inspect and understand.

---

## 📂 Project Structure

```text
sentiment-analysis-roberta-deberta-tinybert/
│
├── 📊 Datasets/
│   └── your_dataset.xlsx
│
├── 📓 notebooks/
│   │
│   ├── 🤖 RoBERTa/
│   │   └── 01_RoBERTa_Sentiment_Analysis.ipynb
│   │
│   ├── 🚀 DeBERTa/
│   │   └── 02_DeBERTa_Sentiment_Analysis.ipynb
│   │
│   └── ⚡ TinyBERT/
│       └── 03_TinyBERT_Sentiment_Analysis.ipynb
│
└── 📖 README.md
```

---

## 📓 Notebooks

### 🤖 RoBERTa

`01_RoBERTa_Sentiment_Analysis.ipynb`

Contains the RoBERTa-based sentiment analysis implementation, including preprocessing, EDA, model processing, evaluation, prediction, and LIME explainability.

### 🚀 DeBERTa

`02_DeBERTa_Sentiment_Analysis.ipynb`

Contains the DeBERTa-based sentiment analysis implementation with the corresponding preprocessing, analysis, evaluation, prediction, and LIME explainability workflow.

### ⚡ TinyBERT

`03_TinyBERT_Sentiment_Analysis.ipynb`

Contains the TinyBERT-based sentiment analysis implementation along with preprocessing, EDA, evaluation, prediction, and LIME explainability.

---

## 📊 Dataset

The project uses an **Excel dataset** for sentiment analysis.

Dataset location:

```text
Datasets/
└── your_dataset.xlsx
```

The dataset is processed within the notebooks before being used for model training and evaluation.

---

## 📈 Model Evaluation

The implemented models are evaluated using classification performance metrics available in the respective notebooks.

The evaluation stage is used to assess how effectively each transformer model performs sentiment classification.

The project therefore provides an experimental setup for examining:

```text
RoBERTa  ──► Sentiment Classification
DeBERTa  ──► Sentiment Classification
TinyBERT ──► Sentiment Classification
```

---

## 🛠️ Technologies & Libraries

### Programming Language
- 🐍 Python

### Deep Learning & NLP
- PyTorch
- Hugging Face Transformers
- Hugging Face Tokenizers

### Explainable AI
- LIME

### Data Science
- Pandas
- NumPy
- Scikit-learn

### Visualization
- Matplotlib
- Seaborn

### Development Environment
- Google Colab
- Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ramanrishi076/sentiment-analysis-roberta-deberta-tinybert.git
cd sentiment-analysis-roberta-deberta-tinybert
```

### 2. Open the Notebooks

Navigate to:

```text
notebooks/
```

and select the model you want to run:

```text
RoBERTa/
DeBERTa/
TinyBERT/
```

### 3. Open in Google Colab

The notebooks can be opened and executed using **Google Colab** or another compatible Jupyter environment.

### 4. Run the Notebook

Follow the cells sequentially to execute:

```text
Dataset
   ↓
Preprocessing
   ↓
EDA
   ↓
Tokenization
   ↓
Model
   ↓
Training
   ↓
Evaluation
   ↓
Prediction
   ↓
LIME Explanation
```

---

## ✨ Key Features

- 🧠 Three transformer-based sentiment analysis models
- 🤖 RoBERTa implementation
- 🚀 DeBERTa implementation
- ⚡ TinyBERT implementation
- 🧹 Text preprocessing
- 🔍 Exploratory Data Analysis
- 🔤 Transformer tokenization
- 🎯 Sentiment classification
- 📈 Model evaluation
- 💡 LIME-based explainability
- 📓 Organized model-specific notebooks
- ☁️ Google Colab compatible workflow

---

## 🧩 Why Three Transformer Models?

Using multiple transformer architectures provides an opportunity to study sentiment classification from different model perspectives.

```text
                  SENTIMENT ANALYSIS
                         │
          ┌──────────────┼──────────────┐
          │              │              │
          ▼              ▼              ▼
      RoBERTa         DeBERTa        TinyBERT
          │              │              │
          ▼              ▼              ▼
      Powerful        Advanced       Lightweight
      Language        Language        Transformer
      Model           Model           Model
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                  Model Evaluation
                         │
                         ▼
                  LIME Explanation
```

---

## 💡 Explainable AI Component

A major part of this project is not only obtaining a sentiment prediction but also understanding the prediction.

The combination of:

**Transformer Models + LIME**

provides both:

> **Prediction** → What sentiment does the model predict?

and

> **Explanation** → Which parts of the text influenced that prediction?

---

## 📌 Project Summary

This project demonstrates an end-to-end implementation of transformer-based sentiment analysis using **RoBERTa, DeBERTa, and TinyBERT**.

From **data preprocessing and EDA** to **model training, evaluation, prediction, and LIME-based explainability**, the project brings together multiple NLP and Explainable AI techniques in a single sentiment-analysis workflow.

---

## 👨‍💻 Author

**Rishi Raman Saxena**

Computer Science & Engineering

---

## ⭐ Repository

**sentiment-analysis-roberta-deberta-tinybert**

A practical implementation of transformer-based sentiment analysis with multiple architectures and explainable predictions.

---

### 🧠 *Predict the sentiment. Understand the prediction.*
