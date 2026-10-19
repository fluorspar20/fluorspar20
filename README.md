<h1 align="center">Hi, I'm Amogh Dixit</h1>

<p align="center">
MS Computer Science @ UW–Madison • Machine Learning • Statistical Learning Theory • Foundation Models • ML Systems
</p>

<p align="center">
<a href="mailto:asdixit3@wisc.edu"><img src="https://img.shields.io/badge/Email-asdixit3%40wisc.edu-red?style=for-the-badge&logo=gmail"></a>
<a href="https://linkedin.com/in/amoghdixit2010"><img src="https://img.shields.io/badge/LinkedIn-Amogh%20Dixit-blue?style=for-the-badge&logo=linkedin"></a>
<a href="https://github.com/fluorspar20"><img src="https://img.shields.io/badge/GitHub-fluorspar20-black?style=for-the-badge&logo=github"></a>
<a href="https://scholar.google.com/citations?user=ROVYlJIAAAAJ"><img src="https://img.shields.io/badge/Google%20Scholar-Profile-blue?style=for-the-badge&logo=googlescholar"></a>
</p>

---

## About Me

🎓 Currently pursuing my **M.S. in Computer Science at the University of Wisconsin–Madison** (GPA 4.0/4.0), focusing on foundation models, statistical learning theory, and ML systems.

☁️ Spent Summer 2026 as a **Software Development Engineer Intern at Amazon**, building an LLM-powered oncall investigation agent.

💼 Previously a **Software Engineer II at Optum (UnitedHealth Group)** for two years, building large-scale healthcare data platforms and AI-powered tools.

🔬 Published research on **self-supervised speech enhancement** (IIT Indore) and **decentralized venture capital tokenization** (University College London).

📍 Based in **Madison, Wisconsin**.

---

## Experience

### Software Development Engineer Intern — Amazon
*May 2026 – Aug 2026*
- Built an oncall investigation agent in **Python** that ingests alarm tickets, correlates evidence from **AWS CloudWatch** and **Spark** processors on **EMR** via an **MCP** server, and recommends mitigations
- Achieved **88%** recommendation accuracy and cut diagnosis time from 30–60 min to under **10 min**

### Software Engineer II — Optum (UnitedHealth Group)
*Jul 2023 – Aug 2025*
- Developed **Coding Intelligence**, a real-time medical coding platform with high-performance search and retrieval, using **Angular** and **Spring Boot** microservices
- Led the **Azure** migration of Simba, a Java-based PDF engine processing critical CMS medical data
- Reduced **Terraform** upgrade effort by **90%** with an **AutoGen/LlamaIndex** AI agent for Azure infrastructure
- Built a real-time summarization pipeline for 7,000+ AHA articles using GPT-4o mini, Azure Cognitive Search, dense embeddings, and hybrid retrieval
- Migrated search APIs to **Apache Solr**, cutting latency to **300 ms** and indexing time by **15%** via multithreading
- Implemented CI/CD in **GitHub Actions** with composite actions and matrix strategies; shipped Java features tested with Mockito/JMeter

### Undergraduate Researcher — IIT Indore
*Aug 2022 – Mar 2023* · Supervisor: [Dr. Nitya Tiwari](https://scholar.google.com/citations?user=jJDO-m0AAAAJ)
- Engineered noise-aware **variational autoencoders** for **self-supervised** single-channel speech enhancement
- Implemented a **PyTorch dual-VAE** with CNN layers, using cyclic loss to shape the latent space for robust denoising
- Outperformed SOTA baselines by **5%** on NISQA/STOI

### Research Intern — University College London
*May 2022 – Oct 2022* · Supervisors: [Dr. Philip Treleaven](https://dl.acm.org/profile/81100128871), [Dr. Hirsh Pithadia](https://scholar.google.com/citations?user=hmem3YEAAAAJ)
- Engineered a **decentralized** VC tokenization platform on **Polygon** for startup listing and investor funding
- Developed Solidity contracts and tokenomics with bonding curves for automated liquidity and fee structures
- Built a **React** frontend with wallet auth, integrating smart contracts and IPFS via Hardhat and Ethers.js

### Software Development Intern — Appointy
*May 2021 – Jul 2021*
- Built a module with **React, Relay, Go and GraphQL** to visualize enterprise locations on an interactive world map
- Optimized search with throttling and lazy loading, improving rendering efficiency by **20%**

---

## Publications

- **Noise-aware Self-supervised Variational Autoencoder for Speech Enhancement** — A. Dixit, K. S. Nataraj, N. Tiwari. *Circuits, Systems, and Signal Processing* (Springer). [DOI: 10.1007/s00034-025-03036-6](https://link.springer.com/article/10.1007/s00034-025-03036-6)
- **Venture Capital Tokenized Investment** — A. Rastogi, A. Dixit, H. Pithadia, P. Treleaven. SSRN, 2023. [DOI: 10.2139/ssrn.4475767](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4475767)

---

## Selected Projects

### [TALMAS: Timestep-Adaptive Attention Suppression on DLMs](https://github.com/fluorspar20/TALMAS)
- **Training-free** attention intervention on **LLaDA-8B** that suppresses masked-token key attention via adaptive logit biasing, improving GSM8K accuracy from **71% → 73%**
- PPMI-inspired **dependency-aware unmasking** for masked diffusion models, using cross-attention weights to find load-bearing masked positions instead of greedy confidence-first unmasking

### [Pedestrian Intent Prediction for Autonomous Vehicles](https://github.com/fluorspar20/EfficientPIE)
- Offline **CLIP knowledge distillation** into a trainable MLP with combined cross-entropy + MSE loss; **Grad-CAM++** showed partial attention shift toward pedestrians after distillation
- Spatial-masking and scale ablations showed EfficientPIE (IJCAI 2025) relies on scene context over pedestrian body language (F1 0.064 vs 0.457), exposing an overconfidence failure at 76.5% accuracy on the closest pedestrians

### [Adaptive Learning Scheduler for Serverless Functions](https://github.com/fluorspar20/cs736)
- Reproduced a **Google ghOSt/eBPF** scheduler that uses **linear regression** to learn **SRPT** policies for kernel-level enforcement
- Added a runtime-prediction feedback loop, cutting I/O-bound P99 latency by **30%** vs Linux CFS
- Diagnosed I/O bottlenecks in CPU-centric learning that caused **15%** throughput degradation for concurrent CPU tasks

---

## Education

### University of Wisconsin–Madison
**Master of Science — Computer Science** · *Sep 2025 – Dec 2026*
GPA: **4.0 / 4.0**

*Relevant Coursework*:
Advanced Reinforcement Learning • Learning Theory • Computer Vision • Foundation Models • Advanced Operating Systems • High Performance Computing

### Indian Institute of Technology Indore
**Bachelor of Technology — Electrical & Computer Engineering** · *Jul 2019 – May 2023*
GPA: **8.76 / 10.0** · Minor: Economics

*Relevant Coursework*:
Probability & Random Processes • Digital Signal Processing • Linear Algebra • Calculus • Object Oriented Programming • IoT Networks • Information Theory

---

## Technical Skills

### Languages
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/sql-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

### Frameworks & Libraries
![React](https://img.shields.io/badge/react-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![GraphQL](https://img.shields.io/badge/graphql-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Django](https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white)

### Tools & Infrastructure
![AWS](https://img.shields.io/badge/aws-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Jenkins](https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Apache Solr](https://img.shields.io/badge/apache%20solr-D9411E?style=for-the-badge&logo=apachesolr&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/dynamodb-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![SQL Server](https://img.shields.io/badge/sql%20server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Machine Learning & AI
![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![LangChain](https://img.shields.io/badge/langchain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/langgraph-4B8BBE?style=for-the-badge)
![AutoGen](https://img.shields.io/badge/autogen-5C2D91?style=for-the-badge)
![LlamaIndex](https://img.shields.io/badge/llamaindex-6B46C1?style=for-the-badge)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**Areas:** Agentic AI • Computer Vision • Foundation Models • Reinforcement Learning • Statistical Learning Theory

---

⭐ If you're interested in research collaborations across learning theory, foundation models or ML systems, feel free to connect.
