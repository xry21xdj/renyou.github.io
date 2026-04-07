---
permalink: /
title: "Welcome to Renyou Xie's Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# <a name="about"></a>👨‍🎓 About

I am a Ph.D. candidate at the [School of Electrical Engineering and Telecommunications](https://www.unsw.edu.au/engineering/our-schools/electrical-engineering-telecommunications), [University of New South Wales](https://www.unsw.edu.au/), Sydney, Australia (Expected Submission: August 2026). My supervisors are [A/Prof Guo Chen](https://research.unsw.edu.au/people/dr-guo-chen) and [Dr. Chaojie Li](https://chaojieli.github.io/).

My research focuses on **Trustworthy AI for Sustainable Energy Systems**, spanning federated learning, large language models, privacy-preserving machine learning, and their applications in power systems, microgrids, and fuel cells.

**Research Interests:** \| Federated Learning \| Privacy-Preserving AI \| LLM for Energy Systems \| Fuel Cell Prognostics \| Power System State Estimation

---

# <a name="news"></a>🔥 News

- **2026.01** Received **UNSW Digital Grid Futures Institute (DGFI) Seed Funding** (17,000 AUD).
- **2025** Invited as **Session Chair** at IECON 2026 (SS22: System-Level Planning and Economic Optimization of V2G/V2H-Enabled Smart Buildings and Power Systems).
- **2025** New paper published in *IEEE Transactions on Cybernetics* (Q1, IF 10.5).
- **2025** New paper published in *Cyber-Physical Energy Systems*.
- **2024** Won **Gold Medal** at China International College Students' Innovation Competition (CICSIC) as team leader.
- **2024** New paper published in *IEEE Internet of Things Journal* (Q1, IF 8.9).
- **2024** New paper published in *IEEE Transactions on Parallel and Distributed Systems* (CCF-A, Q1, IF 6.0).

---

# <a name="publications"></a>📝 Publications

[[Google Scholar](https://scholar.google.com.hk/citations?user=PLujFT4AAAAJ&hl=zh-CN)]

### First Author / Corresponding Author

1. **R. Xie**, L. Xu, C. Li, et al. [Neural-optimization integration for AC optimal power flow: A differentiable warm-start approach](). *Cyber-Physical Energy Systems*, 2025.

   <img src="/renyou.github.io/images/pub_ACOPF.png" alt="ACOPF Framework" style="max-width:600px; width:100%; margin: 10px 0;">

   We propose a differentiable warm-start framework that integrates neural networks with nonlinear programming solvers for AC optimal power flow. The neural network provides high-quality initial points, and gradients from the NLP solver flow back to update the network, enabling end-to-end training without labelled data.

2. **R. Xie**, C. Li, Z. Yang et al. [Differential privacy enabled robust asynchronous federated multitask learning: a multigradient descent approach](). *IEEE Transactions on Cybernetics*, 2025. (**Q1**, JCR ranked 16/204 in Computer Science, Artificial Intelligence, **IF 10.5**)

   <img src="/renyou.github.io/images/pub_FedMGDA.png" alt="FedMGDA Framework" style="max-width:600px; width:100%; margin: 10px 0;">

   We develop an asynchronous federated multitask learning framework with differential privacy guarantees. Each edge device performs local MGDA-based training on its own task, and uploads model updates with calibrated Laplace noise to a central server for aggregation, achieving both privacy protection and multi-task fairness.

3. **R. Xie**, X. Yin, C. Li, et al. [Large Language Model-aided Edge Learning in Distribution System State Estimation](https://ieeexplore.ieee.org/abstract/document/10722848). *IEEE Internet of Things Journal*, 2024. (**Q1**, JCR Ranked 23/368 in Engineering, Electrical & Electronic, **IF 8.9**)

   <img src="/renyou.github.io/images/pub_LLM_DSSE.png" alt="LLM-aided DSSE Framework" style="max-width:600px; width:100%; margin: 10px 0;">

   We introduce a pretrained LLM into distribution system state estimation to handle missing measurement data. The LLM is fine-tuned to forecast missing values from domain-specific prompts and historical sequences, which are then fed into a multi-task learning model for accurate state estimation.

4. **R. Xie**, C. Li, X. Zhou and Z. Dong. [Accelerating Communication-efficient Federated Multi-Task Learning With Personalization and Fairness](https://ieeexplore.ieee.org/abstract/document/10552428). *IEEE Transactions on Parallel and Distributed Systems*, 2024. (**CCF-A, Q1**, JCR ranked 16/147 in Computer Science, Theory & Methods, **IF 6.0**)

   <img src="/renyou.github.io/images/pub_FL_platform.png" alt="Federated Learning Platform" style="max-width:600px; width:100%; margin: 10px 0;">

   We design a communication-efficient federated multi-task learning algorithm that balances personalization and fairness across heterogeneous clients. A physical Raspberry Pi-based federated learning platform is built to validate the proposed method in real-world distributed settings.

5. **R. Xie**, C. Li, X. Zhou, H. Chen and Z. Dong. [Differentially Private Federated Learning for Multitask Objective Recognition](https://ieeexplore.ieee.org/abstract/document/10429819). *IEEE Transactions on Industrial Informatics*, vol. 20, no. 5, pp. 7269-7281, May 2024. (**Q1**, JCR Ranked 9/177 in Computer Science, Interdisciplinary Applications, **IF 9.9**)

6. **R. Xie**, C. Li, R. Ma, L. Xu and X. Zhou. [An Explainable Data-Driven Framework for Fuel Cell Aging Prediction Under Dynamic Condition](https://ieeexplore.ieee.org/abstract/document/9866604). *IEEE Transactions on Industrial Electronics*, vol. 70, no. 6, pp. 5960-5970, June 2023. (**Q1**, JCR Ranked 39/368 in Engineering, Electrical & Electronic, **IF 7.2**)

7. **R. Xie**, R. Ma, S. Pu, L. Xu, D. Zhao, and Y. Huangfu. [Prognostic for fuel cell based on particle filter and recurrent neural network fusion structure](https://www.sciencedirect.com/science/article/pii/S2666546820300173). *Energy and AI*, vol. 2, p. 100017, Nov. 2020. (**Q1**, JCR ranked 20/204 in Computer Science, Artificial Intelligence, **IF 9.6**)

8. R. Ma, **R. Xie\***, L. Xu, Y. Huangfu and Y. Li. [A Hybrid Prognostic Method for PEMFC With Aging Parameter Prediction](https://ieeexplore.ieee.org/abstract/document/9417096). *IEEE Transactions on Transportation Electrification*, vol. 7, no. 4, pp. 2318-2331, Dec. 2021. (**Q1**, JCR Ranked 27/368 in Engineering, Electrical & Electronic, **IF 8.3**)

### Co-authored

9. Y. Li, **R. Xie**, C. Li, et al. [Federated graph learning for EV charging demand forecasting with personalization against cyber-attacks](https://arxiv.org/abs/2405.00742). arXiv preprint arXiv:2405.00742, 2024. (*Major revision in IEEE Transactions on Intelligent Transportation Systems*)

10. H. Zhang, **R. Xie**, Y. Li, et al. [Finite-Time Model Predictive Stabilization of DC Electrical Power Systems Feeding CPLs in More Electric Aircraft](https://ieeexplore.ieee.org/abstract/document/10429820). *IEEE Transactions on Industrial Electronics*, vol. 71, no. 10, pp. 12119-12130, Oct. 2024. (**Q1**, **IF 7.2**)

11. H. Zhang, **R. Xie**, Y. Li, et al. [Fast Terminal Sliding Mode Control of DC-DC Boost Converters with Enhanced Disturbance Rejection](https://ieeexplore.ieee.org/abstract/document/10328744). *IEEE Journal of Emerging and Selected Topics in Power Electronics*, vol. 12, no. 1, pp. 531-542, Feb. 2024. (**Q1**, **IF 4.9**)

12. H. Zhang, Y. Li, **R. Xie**, J. Song, B. Liang and Y. Huangfu. [Adaptive Model Predictive Control of an Interleaved Boost Converter Using Real-Time Updated Model](https://ieeexplore.ieee.org/abstract/document/9926158). *IEEE Transactions on Power Electronics*, vol. 38, no. 2, pp. 1720-1731, Feb. 2023. (**Q1**, JCR Ranked 44/368 in Engineering, Electrical & Electronic, **IF 6.5**)

13. L. Xu, R. Ma, **R. Xie**, S. Zhuo, Y. Huangfu and F. Gao. [Offset-Free Model Predictive Control of Fuel Cell DC-DC Boost Converter With Low-Complexity and High-Robustness](https://ieeexplore.ieee.org/abstract/document/9869784). *IEEE Transactions on Industrial Electronics*, vol. 70, no. 6, pp. 5784-5796, June 2023. (**Q1**, **IF 7.2**)

14. L. Xu, R. Ma, **R. Xie**, J. Xu, Y. Huangfu and F. Gao. [Open-Circuit Switch Fault Diagnosis and Fault-Tolerant Control for Output-Series Interleaved Boost DC-DC Converter](https://ieeexplore.ieee.org/abstract/document/9448170). *IEEE Transactions on Transportation Electrification*, vol. 7, no. 4, pp. 2054-2066, Dec. 2021. (**Q1**, JCR Ranked 27/368 in Engineering, Electrical & Electronic, **IF 8.3**)

---

# <a name="honours-and-awards"></a>🏆 Honours and Awards

- **2026**: UNSW Digital Grid Futures Institute (DGFI) Seed Funding, 17,000 AUD
- **2025**: Development and Research Training Grant, University of New South Wales
- **2024**: Gold Medal of China International College Students' Innovation Competition (CICSIC, Team Leader), Ministry of Education of the People's Republic of China
- **2023**: Tuition Fee Scholarship & Stipend, University of New South Wales
- **2021**: Outstanding Master's Thesis, Northwestern Polytechnical University
- **2021**: Outstanding Graduate Student, Northwestern Polytechnical University
- **2020**: National Scholarship, Chinese Ministry of Education

---

# <a name="education"></a>📖 Education

- **09/2023 ~ Present**: [University of New South Wales](https://www.unsw.edu.au/), Sydney, Australia
  - Ph.D. Candidate in *Electrical Engineering* (Expected Submission: August 2026)
  - Supervisors: A/Prof Guo Chen, Dr. Chaojie Li

- **09/2018 ~ 04/2021**: [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), Xi'an, China
  - M.Phil. in *Electrical Engineering*
  - Supervisor: Prof. Yuren Li

- **09/2014 ~ 07/2018**: [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), Xi'an, China
  - B.E. in *Electrical Engineering*
  - Honours thesis advisor: A/Prof. Bo Liang

---

# <a name="professional-experience"></a>💼 Professional Experience

- **03/2025 ~ 12/2025**: Research Assistant, [University of New South Wales](https://www.unsw.edu.au/), Sydney, Australia
  - Supervisor: Dr. Rachel Zhang
  - Supervised 10+ master's students on thesis projects focusing on data-driven power system stability assessment
  - Conducted research on AI-driven methods for power system stability and security assessment

- **09/2021 ~ 07/2023**: Research Assistant, [Central South University](https://www.csu.edu.cn/), Changsha, China
  - Supervisor: Prof. Xiaojun Zhou
  - Conducted research on federated learning for distributed energy systems
  - Published 2 papers in high-impact IEEE Transactions including TPDS (CCF-A, Q1), TII (Q1)

---

# <a name="teaching-experience"></a>🏫 Teaching Experience

- **ELEC9781: Special Topics in Energy Systems** (Postgraduate), University of New South Wales
  - Tutor, Term 2 2024 & Term 2 2025
  - Led tutorial sessions for 60+ postgraduate students on AI applications in power systems with renewable energy (2025) and energy storage systems (2024)

- **ELEC3111: Distributed Energy Generation** (Undergraduate), University of New South Wales
  - Tutor & Lab Demonstrator, Term 3 2024 & Term 3 2025
  - Conducted tutorial sessions on renewable energy integration, distribution network analysis, and power flow calculations

---

# <a name="conference-presentations"></a>💬 Conference Presentations

1. **Oral presentation** at 20th IEEE ICIT, Melbourne, Australia, February 2019. **R. Xie\***, B. Liang, H. Zhang, and Y. Li, "A novel constant frequency sliding mode control for bidirectional quadratic boost-buck converter."

2. **Oral presentation** at ICASSP 2023, Rhodes Island, Greece. **R. Xie\***, C. Li, X. Zhou and Z. Dong, "Asynchronous Federated Learning for Real-Time Multiple Licence Plate Recognition Through Semantic Communication."

3. **Oral presentation** at IECON 2023, Singapore. **R. Xie\*** and C. Li, "Private Reversible Aging-Aware Fuel Cell Prognostic: A Federated Multitask Learning Approach."

---

# <a name="professional-service"></a>🔧 Professional Service

**Session Chair:**
- The 3rd International Conference on Machine Learning and Intelligent System (MLIS 2021), Session on Neural Networks, IoT and Digitalization
- The 52nd Annual Conference of the IEEE Industrial Electronics Society (IECON 2026), SS22: System-Level Planning and Economic Optimization of V2G/V2H-Enabled Smart Buildings and Power Systems

**Peer Reviewer:**
- *Journals:* IEEE Transactions on Smart Grid, IEEE Transactions on Industrial Electronics, IEEE Transactions on Power Systems, IEEE Transactions on Sustainable Energy, IEEE Transactions on Energy Conversion, IEEE Transactions on Transportation Electrification, IEEE Transactions on Information Forensics and Security, IEEE Transactions on Cybernetics, IEEE Internet of Things Journal, IEEE Transactions on Industrial Cyber-Physical Systems, IEEE Transactions on Industry Applications, Automatica, Applied Energy, Energy Conversion and Management
- *Conferences:* AAAI 2025, ICASSP, IEEE IECON
