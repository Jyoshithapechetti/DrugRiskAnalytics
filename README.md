# Uncovering the Hidden Risk

A comprehensive data analytics framework for mining **patient-reported drug reviews** to identify adverse drug reactions, analyze side-effect patterns, predict sentiment and ratings, and provide actionable insights for healthcare stakeholders. The system combines **Natural Language Processing (NLP)**, **machine learning**, and **interactive visualization** to uncover hidden risks associated with medications.

---

## Features

* **Drug Review Analytics** using real-world patient feedback.
* **Side-Effect Extraction** through medical dictionaries and phrase-based pattern matching.
* **Severity Detection** using medical keywords, multiword patterns, and negation handling.
* **Side-Effect Co-occurrence Analysis** using PMI and Jaccard similarity metrics.
* **Drug Similarity Modeling** based on normalized side-effect frequency profiles.
* **Risk-Level Classification** for individual drugs.
* **Sentiment Classification** (Positive vs Negative) using machine learning.
* **Rating Prediction** (1–10 scale) based on review content.
* **Interactive Streamlit Dashboard** with multiple analytical views and visualizations.
* **Real-Time Review Analysis** through an integrated prediction module.

---

## Tech Stack

* **Programming Language**: Python
* **Frontend & Dashboard**: Streamlit
* **Data Processing**: Pandas, NumPy
* **Machine Learning**: Scikit-learn
* **NLP Techniques**: TF-IDF, VADER Sentiment Analysis
* **Visualization**: Matplotlib
* **Models**: Logistic Regression, Ridge Regression
* **Similarity & Analytics**: PMI, Jaccard Similarity, Cosine Similarity


## Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/Uncovering-the-Hidden-Risk.git
cd Uncovering-the-Hidden-Risk

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit application
streamlit run app.py
```

Then, visit the local URL displayed in your terminal (typically http://localhost:8501).

---

## Project Objectives

The project aims to:

* Understand patient experiences with different drugs
* Identify common side effects and evaluate their severities
* Analyze similarity relationships among drugs
* Build predictive models for sentiment classification and rating prediction
* Generate decision-support insights for healthcare professionals, researchers, and pharmaceutical organizations

---

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/ukveteran/drug-review

---

## Additional Resources

* Scikit-learn Documentation
* Streamlit API Documentation
* NLP TF-IDF Feature Extraction Guides
* Research Papers on Adverse Event Mining
* Pharmacovigilance and Drug Safety Literature

---

**Department of Computer Science and Engineering**
Amrita School of Computing, Bengaluru
Amrita Vishwa Vidyapeetham, India
