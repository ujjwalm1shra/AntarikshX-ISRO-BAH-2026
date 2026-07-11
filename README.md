# 🌌 AntarikshX — ISRO BAH Hackathon 2026

<p align="center">
  <img src="https://img.shields.io/badge/Hackathon-ISRO%20BAH%202026-blueviolet?style=for-the-badge&logo=nasa" alt="Hackathon Badge">
  <img src="https://img.shields.io/badge/Main%20Branch-Protected-red?style=for-the-badge&logo=github" alt="Protection Badge">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python" alt="Python Badge">
</p>

---

## 🎯 Project Overview
> **A sleek, high-level overview hook describing what your project achieves.**
> Explain your core vision here in 2–3 sentences. What breakthrough does this software achieve for ISRO's space data?

---

## 📋 Problem Statement (PS-15)

<details open>
<summary><b>Click to expand full challenge details</b></summary>
<br>

### 🔍 [PASTE YOUR EXACT PROBLEM STATEMENT TITLE HERE]

*   **Target Objective:** [Summarize the main goal in one line]
*   **Challenge Context:** [Paste the detailed description, constraints, and requirements provided to you by the ISRO hackathon committee here]

</details>

---

## 👥 Crew & Mission Roles

| Crew Member | GitHub Handle | Primary Responsibility |
| :--- | :--- | :--- |
| **Ujjal Mishra** | [@ujjwalm1shra](https://github.com/ujjwalm1shra) | 🤖 Core Data Pipelines & Model Developement |
| **Jaykumar** | [@vermajaykumar428](https://github.com/vermajaykumar428) | 🧪 Evaluation & Physics Validation |
| **Ayshwarye** | [@ayshwarye@gmail.com](https://github.com/ayshwarye) | 📊 UI Dashboard & Benchmarking |
| **Diksha Agrawal** | [@diksha-agrawal](https://github.com/diksha-agrawal) |📄 Presentation and Documentation |

---

## 📂 Project Architecture

```text
AntarikshX-ISRO-BAH-2026/
├── data/                  # Data Storage (Git Ignored Large Files)
│   ├── raw/               # Pristine, untouched ISRO datasets
│   ├── processed/         # Cleaned, standardized inputs
│   └── sample/            # Small mini-sets for rapid local testing
├── notebooks/             # Jupyter Notebooks for R&D and EDA
├── src/                   # Production-grade Source Code
│   ├── data_pipeline/     # Ingestion, cleaning, and filtering scripts
│   ├── models/            # Core ML model architectures (LSTM, XGBoost)
│   ├── physics/           # Physics-informed verification layers
│   ├── evaluation/        # Validation, metrics, and SHAP logic
│   ├── api/               # Fast-API server backends
│   └── dashboard/         # Streamlit visual interface files
├── docs/                  # Project documentation & reference sheets
├── papers/                # Reviewed academic literature & source material
├── reports/               # Generated technical evaluation charts
└── tests/                 # Unit testing suites
---

## 🛠️ Local Environment Launch Setup

### Acquire the Repository
```bash
git clone url?id=3.git
cd AntarikshX-ISRO-BAH-2026
git checkout dev
pip install -r requirements.txt
<p>To ensure zero code conflicts and maintain high codebase integrity, the team follows strict version control rules:

🔒 <b>main Branch</b>: Protected production environment. Direct commits are strictly locked.

🛠️ <b>dev Branch</b>: Integration sandbox. All completed team features merge here first.

🌿 <b>feature/ Branches</b>: Isolated local development environments.</p>


### Daily Feature Workflow

# 1. Update your local blueprint map
git fetch origin

# 2. Teleport into your dedicated workspace branch
git checkout feature/your-assigned-feature

# 3. Code your feature, stage, and save it locally
git add .
git commit -m "feat: implemented core mathematical logic"

# 4. Upload directly to your feature branch cloud
git push origin feature/your-assigned-feature

💡 Next Step: Open a Pull Request (PR) on GitHub targeting the dev branch for peer review!
1. Scroll down, write a commit message like `docs: add setup and contribution guide`, and click **Commit changes**
2. After approved by peers, the code will be pushed to main branch.
