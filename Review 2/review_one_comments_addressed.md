# Addressing Panel Review 1 Comments in Review 2

This document provides a point-by-point response to the feedback received during Panel Review 1 and where those changes can be found in the current Review 2 documentation.

| Review 1 Comment | Resolution / Action Taken | Document Location |
| :--- | :--- | :--- |
| **1. Define application scope & use case** | Narrowed the project domain to **Smart Energy Grids (STLF)** focusing on residential household load forecasting. | `report.tex`: Section 1<br>`presentation.tex`: Slide 3 |
| **2. Target a well-defined domain** | Targeted the **Pecan Street Public Dataset** environment for residential energy analytics rather than generic datasets. | `report.tex`: Section 4<br>`presentation.tex`: Slide 6 |
| **3. Articulate research novelty** | Explicitly defined the integration of **CUSUM (Cumulative Sum)** drift detection into the federated training loop. | `report.tex`: Section 2<br>`presentation.tex`: Slide 4 |
| **4. Justify drift detection necessity** | Explained how local behavior changes (festivals, weather) disrupt global models without active monitoring. | `report.tex`: Section 2<br>`presentation.tex`: Slide 4 |
| **5. Elucidate on privacy aspects** | Distinguished between standard FL data-staying-local and **Differential Privacy ($\epsilon$-DP)** using Laplacian noise. | `report.tex`: Section 3<br>`presentation.tex`: Slide 5 |
| **6. Comparative discussion of FL** | Included a comparison of **FedAvg, FedPer, and FedProp** highlighting handling of heterogeneity and drift. | `report.tex`: Section 3<br>`presentation.tex`: Slide 6 |
| **7. Improve technical depth** | Provided overviews for the **Shared Backbone, Personalization Head, and Temporal Attention** mechanisms. | `report.tex`: Section 2<br>`presentation.tex`: Slide 5 |
| **8. Connect to real-world scenario** | Connected motivating scenarios to utility peak demand management and grid stability deployment. | `report.tex`: Section 1<br>`presentation.tex`: Slide 3 |
| **9. Strengthen use case impacts** | Highlighted the specific benefit of **Explainable Attention** for grid operators in trusting predictive insights. | `report.tex`: Section 2<br>`presentation.tex`: Slide 5 |

## Summary of Changes
All documents in the `Review 2` folder now prioritize **Smart Grid Analytics** as the core use case, with a strong emphasis on **Drift-Awareness** and **Technical Depth** as requested by the panel.
