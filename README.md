# Detecting Fake News with LSTM and Transformer Models

This repository contains the final project for the *Natural Language Processing and Text Analytics* course at Copenhagen Business School. The goal was to develop robust NLP models capable of classifying news articles as *real* or *fake* based on their textual content.

## 🧠 Project Overview

The task involved:
- Preprocessing and vectorizing news article texts from two labeled datasets.
- Comparing multiple deep learning models: Logistic Regression, LSTM, BERT, and Mistral.
- Evaluating models using accuracy, precision, recall, and F1-score.
- Analyzing attention-based model behavior and tokenization impact.
- Producing a comprehensive report with critical insights and visualizations.

## 📂 Structure
```
📁 Mistral AI - Output/  
    └── Generated results and output files from Mistral-based experiments

📁 Raw Datasets/  
    └── [Note: Original dataset not included due to size restrictions]

📄 NLP_Final_Exam_Code.ipynb  
📄 NLP_Final_Exam_Report.pdf  
📄 HOW TO RUN THE CODE.txt
```

⚠️ **Note:** The full raw dataset (1GB+) could not be uploaded to GitHub due to size limitations.

## ⚙️ Technologies Used

- Python (Pandas, NumPy, TensorFlow/Keras, HuggingFace Transformers)
- Jupyter Notebook
- Mistral AI (via text generation API)
- Google Colab
- LaTeX (for the final report)

## 🏁 Results Summary

- **Best Model (F1):** Fine-tuned LSTM with pre-trained embeddings.
- **Runner-up:** BERT-based Transformer with high overall precision.
- **Most Expensive (Low ROI):** Mistral model – high cost, poor accuracy.
- Attention visualizations and metric plots support model evaluation.
- Key trade-offs between interpretability, performance, and inference time.

## 📑 Report

The report (`NLP_Final_Exam_Report.pdf`) includes methodology, performance comparison, token analysis, and model explainability components.

## 👥 Authors

- **Brian Rohde**  
- **Enrico Manfron**
- **Charalampos Karatzas**

This project was submitted as part of the MSc in Business Administration & Data Science program at Copenhagen Business School.
