<h1 align="center">Hi, I'm Dwi Yuda</h1>

<p align="center">
  AI Engineer deep learning in PyTorch, model evaluation and interpretability, and shipping vision models behind real APIs.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dwiyuda">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:dwiiyudaaa@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <!-- Aktifkan baris di bawah kalau portfolio sudah live:
  <a href="https://DOMAIN-PORTOFOLIO-ANDA">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=flat&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  -->
</p>

---

## About

Informatics Engineering at **Universitas Islam Riau** (Pekanbaru, Indonesia), graduating late 2026. I build deep learning systems that survive contact with real data — the kind where an evaluation audit matters more than a leaderboard number.

- 🔬 **Working on:** computer vision pipelines, LLM-based tooling, model evaluation & interpretability
- 🛠️ **Stack I reach for:** PyTorch, Hugging Face, FastAPI, Next.js, OpenCV
- 🎓 **Teaching Assistant** at UIR Informatics — ran lab sections for ~300 students across Statistics, Databases, and Web Programming
- 💬 Indonesian (native) · English (professional) · Arabic (conversational)
- 📫 Open to **AI Engineer** roles and research collaboration

---

## Featured Projects

### 🪪 [Automatic Student ID Card Forgery Detection](https://github.com/Dwiyuda/KTM-Detector-UIR-Skripsi_Public)
Four-stage pipeline for detecting forged student ID cards. Qwen3-VL gates out non-card photos, Florence-2 with Canny crops and straightens the card, EfficientNet-B0 classifies genuine vs. forged, and Grad-CAM explains the decision.

- **97.7% accuracy, ROC-AUC 0.9912** on 1,645 images across five forgery scenarios
- Rebuilt the train/test split to be group-aware after an audit exposed a **29% card-level leak** — the honest number, not the flattering one
- Runs on 4 GB VRAM; served through FastAPI with a Next.js 14 frontend

`PyTorch` `FastAPI` `Next.js` `OpenCV` `Grad-CAM`

### 📝 LLM-Based Automated Practicum Grading System
Python system that grades practicum submissions via the Gemini API, reading the question, answer key, and rubric to score each student and export an Excel recap with per-student feedback. Covers eight sessions including a quiz and final exam.

- Skipped RAG deliberately — the full context fits in a single prompt
- Every output carries a confidence label; anything below high confidence routes to a human reviewer
- Instructor validates AI-drafted answer keys before use; submitted code is read, never executed
- Approved by the head of department

`Python` `Gemini API` `Prompt Engineering` `Human-in-the-loop`

---

## What I Focus On

| Area | What that means in practice |
|------|------------------------------|
| **Applied Deep Learning** | Transfer learning, vision pipelines, training under tight VRAM budgets |
| **Model Evaluation** | ROC-AUC, confusion matrices, group-aware splitting, leakage audits |
| **Interpretability** | Grad-CAM and explaining *why* a model decided what it decided |
| **LLM Systems** | Prompt engineering, structured outputs, confidence gating, human-in-the-loop design |
| **Model Serving** | FastAPI backends, Next.js frontends, making the model usable by non-engineers |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
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
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Dwiyuda&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dwiyuda&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" alt="Top languages"/>
</p>

---

## Let's Connect

Open to AI Engineer roles, applied ML collaboration, and academic work.

- 💼 [LinkedIn](https://www.linkedin.com/in/dwiyuda)
- 📧 dwiiyudaaa@gmail.com
