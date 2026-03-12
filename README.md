# Semantic Book Recommender: LLM-Powered Recommendation Engine
![Status](https://img.shields.io/badge/Status-In_Development-blue.svg)

## Executive Summary

This project aims to build an intelligent, content-based book recommendation system engineered using modern Generative AI and Natural Language Processing (NLP) techniques. Moving beyond traditional collaborative filtering approaches, this system will leverage Large Language Models (LLMs) to understand the contextual and semantic relationships between books.

By transforming unstructured book descriptions into mathematical vector representations, the engine will perform highly precise semantic matching. The final pipeline will integrate vector search, zero-shot text classification, and sentiment analysis to recommend books by thematic depth and emotional tone.

---

## Current Progress & Development Phases

The project is currently in active development. Below is the roadmap and current status:

* [x] **Phase 1: Project Setup & Environment Isolation**
* Configured custom Conda environment (`recommender_env`) with Python 3.11.
* Initialized PyCharm Professional workspace.


* [x] **Phase 2: Data Ingestion & Initial Exploration**
* Ingested the 7K Books dataset from Kaggle.
* Currently performing exploratory data analysis (EDA) using Pandas and Jupyter Notebooks to understand the metadata structure and missing values.


* [ ] **Phase 3: Vectorization & Semantic Search (Planned)**
* Implement LangChain for text chunking.
* Generate high-dimensional embeddings and construct a local Vector Database.


* [ ] **Phase 4: Zero-Shot Classification & Sentiment Analysis (Planned)**
* Deploy Hugging Face transformer models for dynamic topic categorization.
* Utilize LLMs to extract emotional tones from book descriptions.


* [ ] **Phase 5: UI Deployment (Planned)**
* Build an interactive dashboard using Gradio for user inference.



---

## Technical Infrastructure & Environment

* **Environment Management:** The project strictly utilizes a customized Conda environment to maintain dependency isolation.
* **Development IDE:** Engineered using PyCharm Professional.
* **Data Processing:** Pandas and Jupyter integrations for robust data exploration.

---

## Repository Structure

```text
├── data/                       # Ingested datasets (books.csv)
├── notebooks/                  # Experimental Jupyter environments
│   └── data-exploration.ipynb  # Current EDA notebook
│
├── .env.example                # Template for environment variables (Pending)
├── requirements.txt            # Project dependencies (Pending)
└── README.md                   # Project documentation

```

---

*Architected and developed by [Muhammad Zaenal Abidin Abdurrahman](https://www.linkedin.com/in/zendin1102/) - 2026*