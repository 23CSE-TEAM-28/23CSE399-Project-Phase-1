# FPDAF: Explainable Federated Analytics for Multivariate Time-Series Forecasting

## Project Overview
This repository contains the work for **23CSE399 -- Project Phase 1** at **Amrita Vishwa Vidyapeetham**. Our research focuses on developing a unified federated architecture—**FPDAF (Federated Personalized Drift-Aware Attention Framework)**. This system integrates:
1.  **Personalization** for client heterogeneity.
2.  **CUSUM-based Concept Drift Adaptation**.
3.  **Attention-driven Explainability** for Multivariate Time-Series (MVTS) forecasting.

The project specifically targets **Smart Energy Grids (Household Load Forecasting)** to solve accuracy-degradation issues caused by non-IID distributions and seasonal behavior shifts.

---

## 🏗 System Architecture & Workflow

### 🛠 Architecture Overview
The framework consists of a **Shared Global Backbone** capturing temporal periodicity and a **Personalization Head** mapped to specific household energy consumption habits.

![System Architecture](Review%202/SA_1.png)

### 📈 Adaptive Workflow
We integrate the **Cumulative Sum (CUSUM)** algorithm directly into the federated training loop to trigger specialized retraining when local behavioral shifts (e.g., festive seasons, holidays) are detected.

![Adaptive Workflow](Review%202/AWF.png)

---

## 🚀 Key Features & Novelty
- **Privacy Preservation**: raw sensitive meter data never leaves the household gateway; gradients are protected via **Laplacian Differential Privacy ($\epsilon$-DP)**.
* **Non-IID Handling**: Addresses the 15%+ error gap in standard FedAvg by using localized personalized layers (FedPer).
* **Drift-Awareness**: Actively monitors model residuals to detect environmental shifts before they pollute the global model.
* **Interpretable Analytics**: Temporal attention weights highlight exactly *when* demand spikes originate, building trust with grid operators.

---

## 📂 Repository Structure
* **[Review 1/](Review%201/)**: Baseline research and Literature Survey of 25 peer-reviewed papers.
  * `literature_survey_summary.md`: Detailed breakdown of 25 research gaps.
* **[Review 2/](Review%202/)**: Technical progress addressing panel feedback.
  * `report.tex`: 2-page Technical Summary of FPDAF.
  * `presentation.tex`: Beamer Slides for Technical Progress.
  * `ref.bib`: Unified bibliography for the phase.
  * `review_one_comments_addressed.md`: Feedback traceability matrix.

---

## 📊 Phase 1 Implementation Status (Review 2 Update)
- [x] **Literature Survey Completion** (25 Peer-reviewed papers)
- [x] **Domain definition**: Residential Energy Analytics (Pecan Street Dataset)
- [x] **Mathematical Modeling**: CUSUM-FL integration logic finalized.
- [x] **Baseline Simulation**: Initial LSTM-FedAvg benchmarks established.
- [p] **Technical Proof**: Differential Privacy noise layers (In-progress).

---

## 👥 Team 28
- Sheela Akshar Sakhi (CB.SC.U4CSE23547)
- Hasini Reddy M (CB.SC.U4CSE23529)
- Kousik Sarma Lakkaraju (CB.SC.U4CSE23761)
- Haswitha K (CB.SC.U4CSE23363)
- V.Chakravarthy (CB.SC.U4CSE23753)

### 🎓 Guides
- **Dr. G R RAMYA**
- **Dr. VANDHANA S**

---
*Department of Computer Science and Engineering, Amrita School of Computing.*
