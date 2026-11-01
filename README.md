<h1 align="center">Hi, I'm Dwi Yuda 👋</h1>

<p align="center">
  <b>AI / ML Engineer</b> — deep learning in PyTorch, model evaluation & interpretability,<br/>
  and shipping vision + LLM systems behind real APIs.
</p>

<p align="center">
  <a href="https://dwiyuda.is-a.dev">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/dwiyuda">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:dwiiyudaaa@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## About

Informatics Engineering at **Universitas Islam Riau** (Pekanbaru, Indonesia), graduating late 2026.
I build deep learning systems that survive contact with real data — the kind where an evaluation
audit matters more than a leaderboard number.

- 🔬 **Working on:** computer vision pipelines, LLM / RAG tooling, model evaluation & interpretability
- 🛠️ **Stack I reach for:** PyTorch, Hugging Face, FastAPI, Go, Next.js, OpenCV
- 🎓 **Teaching Assistant** at UIR Informatics — ran lab sections for ~300 students across Statistics, Databases, and Web Programming
- 💬 Indonesian (native) · English (professional) · Arabic (conversational)
- 📫 Open to **AI Engineer**, **Data**, and **Backend** roles, and research collaboration

---

## Featured Projects

### 🪪 [Student ID Card Forgery Detection](https://github.com/Dwiyuda/KTM-Detector-UIR-Skripsi_Public) · *final thesis*
Four-stage pipeline that detects forged student ID cards. Qwen3-VL gates out non-card photos,
Florence-2 + Canny crops and straightens the card, EfficientNet-B0 classifies genuine vs. forged,
and Grad-CAM explains the decision.
- **97.7% accuracy, ROC-AUC 0.9912** on 1,645 images across five forgery scenarios
- Rebuilt the train/test split to be group-aware after an audit exposed a **29% card-level leak** — the honest number, not the flattering one
- Runs on 4 GB VRAM; served through FastAPI with a Next.js frontend

`PyTorch` `FastAPI` `Next.js` `OpenCV` `Grad-CAM`

### ⚖️ [Islamic Family Law Assistant](https://github.com/Dwiyuda/islamic-family-law-assistant)
RAG assistant for Indonesian Islamic family law (divorce & inheritance): hybrid retrieval +
reranking, refusal gating so it declines what it cannot ground, and a **deterministic faraid
engine** for the arithmetic an LLM should never guess.

`Python` `RAG` `Hybrid Retrieval` `Reranking` `LLM`

### 🏘️ [Village Aid Priority — K-Means + AHP-TOPSIS](https://github.com/Dwiyuda/village-aid-priority-kmeans-ahp-topsis)
Decision support system that ranks **371 villages** for social-assistance targeting: K-Means
clustering plus AHP-TOPSIS multi-criteria ranking, a Flask app with live consistency checking,
and an [interactive dashboard](https://datastudio.google.com/reporting/caaa607a-7a94-49e2-bc3f-3698f9c8e82a).

`Python` `scikit-learn` `AHP-TOPSIS` `Flask` `Looker Studio`

### 📝 [LLM Practicum Grader](https://github.com/Dwiyuda/llm-practicum-grader)
Grades lab submissions via the Gemini API against a human-approved answer key and rubric, then
exports an Excel recap. Every output carries a confidence label; anything below high confidence
routes to a human reviewer.

`Python` `Gemini API` `Prompt Engineering` `Human-in-the-loop`

---

## More Projects

| Project | What it is |
|---|---|
| [practicum-score-graphql](https://github.com/Dwiyuda/practicum-score-graphql) | GraphQL API in **Go** (gqlgen) with PostgreSQL, migrations, tests & CI |
| [housing-aid-priority-xgboost](https://github.com/Dwiyuda/housing-aid-priority-xgboost) | Housing-renovation aid prioritisation: eligibility gate + XGBoost urgency score, Streamlit app |
| [eggplant-leaf-disease-detection-yolov11](https://github.com/Dwiyuda/eggplant-leaf-disease-detection-yolov11) | Eggplant leaf disease detection with YOLOv11 + box-level label audit |
| [shallot-disease-lvlm-zero-shot](https://github.com/Dwiyuda/shallot-disease-lvlm-zero-shot) | Zero-shot shallot disease ID: prompt engineering across 4 vision-language models |
| [plant-disease-cnn-graph-rag](https://github.com/Dwiyuda/plant-disease-cnn-graph-rag) | ResNet-50 classifier + Graph RAG explanations (Neo4j + LLM), evaluated with RAGAS |
| [WEB_PORTOFOLIO](https://github.com/Dwiyuda/WEB_PORTOFOLIO) | Source for my portfolio site — Astro, static, zero JS bundle |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Serving & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Let's Connect

Open to AI Engineer, Data, and Backend roles, applied ML collaboration, and academic work.

- 🌐 [dwiyuda.is-a.dev](https://dwiyuda.is-a.dev)
- 💼 [LinkedIn](https://www.linkedin.com/in/dwiyuda)
- 📧 dwiiyudaaa@gmail.com
