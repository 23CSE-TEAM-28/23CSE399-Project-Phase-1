# Explainable Federated Analytics for Multivariate Time-Series Forecasting with Personalized Model Adaptation

## Project Overview
This repository contains the work for **23CSE399 -- Project Phase 1** at Amrita Vishwa Vidyapeetham. The research focuses on developing a unified federated architecture—**FPDAF (Federated Personalized Drift-Aware Attention Framework)**—that integrates personalization, concept drift adaptation, and explainability for multivariate time-series forecasting. 

The project specifically targets **Smart Energy Grids (Household Load Forecasting)** to handle non-IID energy distributions and behavioral shifts in demand.

## Key Features
- **Privacy Preservation**: Collaborative model training without centralizing sensitive data, enhanced by Differential Privacy ($\epsilon$-DP).
- **Client Heterogeneity**: Addressing non-IID distributions through a hybrid global–personalized architecture (FedPer).
- **Concept Drift Adaptation**: Online drift detection using CUSUM (Cumulative Sum) to trigger adaptive retraining of localized layers.
- **Explainability**: Temporal attention mechanisms to provide interpretable forecasting insights for grid operators.

## Repository Structure
- **[Review 1/](Review%201/)**: Contains initial research, panel comments, and the technical report for the first panel review.
  - `Literature_Survey_Summary.md`: Summary of 25 peer-reviewed papers.
  - `review_one_comments.md`: Feedback received from the first panel.
- **[Review 2/](Review%202/)**: Contains technical progress addressing panel feedback, targeting the Smart Grid domain.
  - `report.tex`: Technical summary of findings and methodology.
  - `presentation.tex`: Beamer slideshow for the second panel review.
  - `review_one_comments_addressed.md`: Point-by-point response to previous feedback.

## Team Members (Team 28)
- Sheela Akshar Sakhi (CB.SC.U4CSE23547)
- Hasini Reddy M (CB.SC.U4CSE23529)
- Kousik Sarma Lakkaraju (CB.SC.U4CSE23761)
- Haswitha K (CB.SC.U4CSE23363)
- V.Chakravarthy (CB.SC.U4CSE23753)

## Guides
- Dr. G R RAMYA
- Dr. VANDHANA S

---
*Department of Computer Science and Engineering, Amrita School of Computing.*
