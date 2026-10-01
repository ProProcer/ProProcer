# Matthew Alexander Paudianto

**Data Scientist / ML Engineer** — building end-to-end systems, from raw data and SQL pipelines to validated models and deployed services.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matthew-alexander-paudianto-a5a342192/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ProProcer)

---

## About

Data Science student who ships production-oriented projects rather than notebooks. I care about the parts that make models useful in practice: clean layered data, leakage-free validation, tracked experiments, and services someone can actually call. My work spans data engineering (PostgreSQL), applied machine learning (scikit-learn, PyTorch/Hugging Face), and MLOps/deployment (MLflow, W&B, Docker, FastAPI, GCP).

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Data & Machine Learning**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Data Engineering & MLOps**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights%20&%20Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Hydra](https://img.shields.io/badge/Hydra-89B8CD?style=for-the-badge&logo=python&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Deployment & Apps**

![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

---

## Featured Projects

### Marketplace Logistics & SLA Bottleneck Detection
End-to-end decision-support and anomaly-attribution system for marketplace operations (Olist Brazil). Decouples **seller handling time** from **carrier transit time** to attribute late deliveries to their true root cause.

- **Data engineering:** layered **Bronze/Silver/Gold PostgreSQL** pipeline with deduplication, constraints, and a geodesic (Haversine) distance feature.
- **Modeling:** monthly **sliding-window cross-validation** for leakage-free evaluation; decoupled anomaly models (Box-Cox group z-scores for handling, multiple linear regression with prediction intervals for transit), benchmarked against statistical baselines with Out-of-Fold scoring.
- **Delivery:** **Streamlit + Plotly** operations dashboard tracking OTD rate, fulfillment composition, and freight unit economics.
- **Stack:** PostgreSQL · Python · scikit-learn · Hydra · MLflow · Streamlit

[![Repo](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ProProcer/olist-ecommerce-analytics)

### Grab Voice-of-Customer Review Triage
End-to-end ML + MLOps system that triages Indonesian app-store reviews into operational domains using a fine-tuned **IndoBERT** multi-label classifier.

- **Results:** **88.91% mean macro F1** and **84.0% exact-match** across all three labels on the held-out test set.
- **Data-centric pipeline:** Play Store scraping (10k reviews) → cleaning → taxonomy + human golden set → **OpenAI Batch API weak supervision** with schema-enforced structured outputs → stratified multi-label split.
- **Serving:** **FastAPI** microservice (single + batched inference) containerized with **Docker** and deployed to **Google Cloud Run**; experiments tracked in **Weights & Biases**.
- **Stack:** PyTorch · Hugging Face · FastAPI · Docker · W&B · GCP Cloud Run

[![Repo](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ProProcer/grab-voc-triage)

---

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ProProcer&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ProProcer&layout=compact&hide_border=true&langs_count=8" alt="Top languages" />
</p>

---

## Let's Connect

I'm open to **Data Science**, **ML Engineering**, and **Analytics Engineering** roles and internships.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matthew-alexander-paudianto-a5a342192/)
