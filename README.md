<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,50:7B2FBE,100:FF6B6B&height=120&section=header&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=800&color=00D9FF&center=true&vCenter=true&multiline=false&repeat=true&width=700&height=60&lines=Hey%2C+I'm+Sahil+Gaund+%F0%9F%91%8B;AI+%2F+ML+Engineer+%7C+Data+Scientist;Building+Systems+That+Think.)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahilgaund)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sahilgaund)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sahilgaund@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-00D9FF?style=for-the-badge&logo=vercel&logoColor=black)](https://sahilgaund.dev)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=sahilgaund&style=for-the-badge&color=00D9FF&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/sahilgaund?style=for-the-badge&color=7B2FBE&labelColor=0D1117&label=FOLLOWERS)

</div>

<br/>

---

## 🧠 About Me

<img align="right" width="340" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="Coding GIF" style="border-radius:12px; margin-left:20px;"/>

```python
class SahilGaund:
    role       = ["AI/ML Engineer", "Data Scientist"]
    focus      = "End-to-end ML systems, from raw data → production"
    languages  = ["Python", "SQL"]
    interests  = ["Machine Learning", "NLP", "Computer Vision"]
    building   = "Bank Customer Churn Prediction System"
    open_to    = "Internships · Collaborations · Research"
    fun_fact   = "🥉 Award-winning photographer turned data scientist"
```

<br/>

- 🎯 &nbsp;Building **production-grade ML pipelines** with real-world impact
- 📊 &nbsp;Specializing in **predictive modeling**, **NLP**, and **data visualization**
- 🏆 &nbsp;Achieved **87% accuracy** on churn prediction with full SHAP explainability
- 📜 &nbsp;Completed **ML Specialization** (Andrew Ng) + **TensorFlow Developer Cert**
- 📸 &nbsp;**3rd Prize** — University Photography Competition (200+ participants)
- 🌍 &nbsp;Based in **India** · Open to remote opportunities

<br clear="right"/>

---

## 🐍 Contribution Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sahilgaund/sahilgaund/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sahilgaund/sahilgaund/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/sahilgaund/sahilgaund/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

</div>

> **Setup:** Add a GitHub Actions workflow at `.github/workflows/snake.yml` to auto-generate this — see [platane/snk](https://github.com/platane/snk).

---

## 🚀 Featured Project — Bank Customer Churn Prediction

<div align="center">

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sahilgaund/churn-prediction)
[![Live Demo](https://img.shields.io/badge/Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://churn-prediction.streamlit.app)
[![Stars](https://img.shields.io/github/stars/sahilgaund/churn-prediction?style=for-the-badge&color=FFD166&labelColor=0D1117)](https://github.com/sahilgaund/churn-prediction)

</div>

### 📌 Problem Statement

> Banks lose **15–25% of customers annually** to churn, costing millions in acquisition to replace them. Early identification of at-risk customers enables proactive retention — but most internal tools rely on lagging indicators.
>
> **Goal:** Build a real-time, explainable ML system that predicts churn with high precision, deployable by non-technical bank staff.

---

### 🏗️ System Architecture

```mermaid
flowchart TD
    A[🗄️ Raw Bank Data\n10,000+ customers] --> B[🔧 Data Preprocessing\nImputation · Encoding · Scaling]
    B --> C[📊 Exploratory Analysis\nCorrelation · Distribution · Outliers]
    C --> D[⚙️ Feature Engineering\nCredit Score Bins · Tenure Ratio · Balance Flag]
    D --> E{🤖 Model Training}
    E --> F[Logistic Regression]
    E --> G[Random Forest]
    E --> H[XGBoost ⭐ Best]
    E --> I[LightGBM]
    E --> J[SVM]
    F & G & H & I & J --> K[📈 Evaluation\nROC-AUC · F1 · Precision · Recall]
    K --> L[🔍 SHAP Explainability\nGlobal + Local Feature Importance]
    L --> M[🚀 Streamlit Dashboard\nReal-time Inference · CSV Upload]
    M --> N[👤 End User\nBank Relationship Manager]

    style H fill:#00D9FF,color:#000,stroke:#00D9FF
    style M fill:#FF4B4B,color:#fff,stroke:#FF4B4B
    style A fill:#1a1a2e,color:#fff
    style N fill:#7B2FBE,color:#fff
```

---

### 🔬 Methodology

| Phase | Steps | Tools |
|:---|:---|:---|
| **Data Wrangling** | Missing value imputation, outlier detection, type casting | `Pandas`, `NumPy` |
| **EDA** | Churn rate by geography, age, balance distribution | `Matplotlib`, `Seaborn` |
| **Feature Engineering** | Credit score bins, balance-to-salary ratio, activity flags | `Pandas`, `Scikit-learn` |
| **Modeling** | 5 algorithms trained, cross-validated (k=5) | `Scikit-learn`, `XGBoost` |
| **Explainability** | SHAP waterfall + beeswarm plots per prediction | `SHAP` |
| **Deployment** | Interactive web app with CSV batch inference | `Streamlit` |

---

### 📊 Results

<div align="center">

| Model | Accuracy | ROC-AUC | F1-Score | Precision | Recall |
|:---:|:---:|:---:|:---:|:---:|:---:|
| Logistic Regression | 81.2% | 0.774 | 0.76 | 0.79 | 0.73 |
| Random Forest | 84.6% | 0.842 | 0.83 | 0.86 | 0.80 |
| SVM | 82.1% | 0.798 | 0.79 | 0.81 | 0.77 |
| LightGBM | 85.9% | 0.861 | 0.84 | 0.87 | 0.82 |
| **XGBoost ⭐** | **87.3%** | **0.891** | **0.86** | **0.89** | **0.84** |

</div>

**Key Insights from SHAP Analysis:**
- `Age` and `NumOfProducts` were the strongest churn predictors
- Customers in **Germany** showed 2.5× higher churn propensity
- Inactive members with `Balance > $100K` had **68% churn probability**

---

### ☁️ Deployment

```
📦 churn-prediction/
├── 📂 data/              # Raw + processed datasets
├── 📂 notebooks/         # EDA + model training notebooks
├── 📂 models/            # Saved model artifacts (.pkl)
├── 📂 src/               # Preprocessing + inference pipeline
├── 📄 app.py             # Streamlit application entry point
├── 📄 requirements.txt
└── 📄 README.md
```

> **Live App Features:** Single-customer prediction · Batch CSV upload · SHAP explanation panel · Confidence score meter

---

## 🛠️ Tech Stack

<div align="center">

**Languages & Core**

[![Skills](https://skillicons.dev/icons?i=python,git,github,linux,vscode&theme=dark)](https://skillicons.dev)

**ML / Data Science**

[![Skills](https://skillicons.dev/icons?i=tensorflow,pytorch,sklearn&theme=dark)](https://skillicons.dev)

**Deployment & Tools**

[![Skills](https://skillicons.dev/icons?i=streamlit,fastapi,docker,jupyter&theme=dark)](https://skillicons.dev)

**Databases**

[![Skills](https://skillicons.dev/icons?i=postgresql,mysql&theme=dark)](https://skillicons.dev)

</div>

<div align="center">

| Domain | Technologies |
|:---:|:---|
| **ML Frameworks** | Scikit-learn · XGBoost · LightGBM · TensorFlow · PyTorch |
| **Data** | Pandas · NumPy · SQL · SHAP · Matplotlib · Seaborn · Plotly |
| **Deployment** | Streamlit · FastAPI · Docker |
| **NLP** | HuggingFace Transformers · NLTK · spaCy |
| **Vision** | OpenCV · YOLOv8 |
| **DevOps** | Git · GitHub Actions · Linux |

</div>

---

## 📈 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=sahilgaund&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=7B2FBE&text_color=c9d1d9&count_private=true&include_all_commits=true" />
&nbsp;&nbsp;
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahilgaund&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=c9d1d9&langs_count=8" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=sahilgaund&theme=midnight-purple&hide_border=true&background=0D1117&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF&sideLabels=7B2FBE&dates=666666" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=sahilgaund&bg_color=0D1117&color=00D9FF&line=7B2FBE&point=FF6B6B&area=true&hide_border=true&area_color=00D9FF" width="100%"/>

</div>

---

## ⚡ Technical Strengths

<div align="center">

| Strength | Capability |
|:---|:---|
| 🔬 **ML Engineering** | End-to-end pipeline design: ingestion → feature store → training → serving |
| 📊 **Statistical Analysis** | Hypothesis testing, A/B analysis, distribution modeling |
| 🧾 **Model Explainability** | SHAP, LIME, permutation importance — production-ready interpretability |
| 🚀 **Rapid Prototyping** | MVP to deployed app in days using Streamlit + FastAPI |
| 🔍 **EDA Mastery** | Surfacing non-obvious patterns from messy, real-world datasets |
| 🧠 **Cross-domain Thinking** | Translating business KPIs into measurable ML objectives |

</div>

---

## 🏆 Achievements

<div align="center">

| 🥇 | Achievement | Details |
|:---:|:---|:---|
| 🧠 | **87% Churn Prediction Accuracy** | Best-in-class XGBoost model with SHAP explainability |
| 📜 | **ML Specialization** | Coursera — Andrew Ng · Supervised, Unsupervised & RL |
| 🎓 | **TensorFlow Developer Certificate** | Google certified · Neural network proficiency |
| 📸 | **3rd Prize — Photography** | University Cultural Festival · 200+ participants |
| 💬 | **NLP Pipeline @ 1K req/s** | BERT fine-tuned · 94% sentiment classification accuracy |
| 🔭 | **YOLOv8 Object Detection** | 91% mAP · Real-time WebRTC inference |

</div>

---

## 🎯 Career Objective

<div align="center">

> *"I don't just build models — I build systems that make decisions at scale."*

</div>

I'm actively seeking **internship and entry-level opportunities** in AI/ML Engineering or Data Science where I can:

- Deploy models that **directly improve business outcomes** — not just Kaggle leaderboards
- Work within **fast-moving teams** that value clean code, reproducibility, and impact
- Apply **end-to-end ML thinking** — from stakeholder requirements to monitored production systems

If you're building something that uses data to make smarter decisions, **let's talk.**

---

## 📬 Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sahilgaund)
&nbsp;
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sahilgaund@email.com)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Visit_Portfolio-00D9FF?style=for-the-badge&logo=vercel&logoColor=black)](https://sahilgaund.dev)

<br/>

*Response time: within 24 hours · Open to DMs on LinkedIn*

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,50:7B2FBE,100:00D9FF&height=100&section=footer&animation=fadeIn" width="100%"/>

**Sahil Gaund** · AI/ML Engineer · Data Scientist

*"Data is the new oil. Refined intelligently, it powers everything."*

![Made with ❤️](https://img.shields.io/badge/Made_with-❤️_in_India-FF6B6B?style=flat-square)
![Last Updated](https://img.shields.io/badge/Last_Updated-2025-00D9FF?style=flat-square)

</div>
