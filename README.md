# Emotion Classification with Transformers and Explainable AI (XAI)

This repository presents an end-to-end **Bangla Emotion Classification** project using **Transformer-based NLP models** and **Explainable AI (XAI)** techniques. The system classifies Bangla text into multiple emotion categories and explains model predictions using **SHAP**.

This project was developed as part of **CSE475 (Machine Learning / NLP)** coursework and follows a clean, reproducible, and research-oriented workflow.

---

## 🔍 Problem Statement

Given a Bangla text sentence, the goal is to accurately predict the **underlying emotion** expressed in the text using state-of-the-art Transformer models while maintaining **interpretability** of predictions.

---

## 🧠 Emotion Classes

The dataset contains Bangla sentences labeled with multiple emotion categories such as:
- Joy
- Sadness
- Anger
- Fear
- Surprise  

*(Exact label names depend on dataset annotations.)*

---

## 🚀 Models Used

- **Multilingual BERT (mBERT)**
- **XLM-RoBERTa**

Both models are fine-tuned using PyTorch and Hugging Face Transformers.

---

## 📊 Explainable AI (XAI)

To improve model transparency and trust:
- **SHAP (SHapley Additive exPlanations)** is applied
- Token-level importance scores are visualized
- Positive and negative contributions of words are analyzed

---

## 🧪 Methodology

1. **Data Preparation**
   - Text cleaning and preprocessing
   - Stratified train/validation/test split

2. **Exploratory Data Analysis (EDA)**
   - Class distribution visualization
   - Text length analysis

3. **Model Training**
   - Fine-tuning Transformer models
   - AdamW optimizer with learning rate scheduling

4. **Evaluation**
   - Accuracy
   - Macro F1-score
   - Weighted F1-score
   - Confusion Matrix

5. **Explainability**
   - SHAP-based interpretation of predictions

---

## 📈 Results Summary

| Model | Accuracy | Macro F1 | Weighted F1 |
|------|----------|----------|-------------|
| mBERT | Strong | High | High |
| XLM-RoBERTa | Higher | Better | Best |

*(Detailed results are available in the notebook.)*

---

## 📂 Repository Structure
```
emotion-classification-with-transformers-xai\.
├── Emotion_Classification_with_Transformers_&_XAI.ipynb
├── README.md
├── data/
  └── dataset files


