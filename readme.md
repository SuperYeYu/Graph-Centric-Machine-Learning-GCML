# Graph-Centric Machine Learning (GCML)



![image-20260306222323495](./image/gcml.png)



## 🌟 Overview

This repository is structured around three core components:

- **📂 Graph Datasets:** Providing diverse graph datasets and the extensive array of downstream graph tasks.
- **📖 Graph Surveys & Reviews:** Offering a systematic overview of the graph machine learning domain to comprehensively explore its foundational concepts and emerging developmental trends.
- **⚖️ Graph Benchmarks:** Facilitating rapid onboarding into specific sub-fields and enabling rigorous comparative analysis of various models.



## 📂 Graph Datasets

#### 1.1 Classification explanation

###### 🎯Downstream Tasks: 

Node Classification (NC), Node Regression (NR), Node Generation (NG), Link Prediction (LP), Link Classification (LC), Graph Classification (GC), Graph Regression (GR), Graph Generation (GG), Graph Alignment (GA), Reasoning

###### 🌐Knowledge Domain:

Co-purchase, Online Review, Co-authorship, Citation, Physical, Molecular, Dialogue, Social, Movie Review, Patent, Q&A, Power Grid, Scene Graph, Game Social, Traffic, E-commerce, Sports, Medical, Web, Server, Protein, Workflow, Circuit, Algorithm, Map, Scene Graph, Neuron, Nutrition-Health

###### 📊Features & Attributes:

Embedding, Text, Image, Tabular,  Bag of Words (BoW), Multimodal  **Tips: * denotes that edges have features.**

###### 🧩Structural Relationship:

Heterogeneous Graph, Homogeneous Graph, Multiplex Graph, Homophily Graph, Heterophilic Graph, Knowledge Graph, Bipartite Graph, Spatio-temporal Graph, Dynamic Graph, Hypergraph

#### 1.2 Paper List

- **A Critical Look at the Evaluation of GNNs under Heterophily: Are We really Making Progress?** [Paper Link](https://arxiv.org/pdf/2302.11640)

  🎯NC  🌐Co-purchase, Online Review, Co-authorship  📊Embedding, BoW  🧩Heterophilic Graph, Homogeneous Graph

- **Can LLMs Effectively Leverage Graph Structural Information: When and Why** [Paper Link](https://arxiv.org/pdf/2309.16595)

  🎯NC  🌐Citation  📊Text  🧩Homogeneous Graph

- **Towards Foundational Models for Molecular Learning on Large-Scale Multi-Task Datasets** [Paper Link](https://arxiv.org/pdf/2310.04292)

  🎯GC, GR  🌐Physical, Molecular  📊Embedding, BoW  🧩

- **Benchmarking and Rethinking Multiplex Graphs** [Paper Link](https://openreview.net/attachment?id=RvyJ5iy9LS&name=pdf)

  🎯NC, LP, LC  🌐Citation, Co-purchase, Movie Review  📊Embedding, BoW  🧩Multiplex Graph

- **Can Large Language Models Improve the Adversarial Robustness of Graph Neural Networks?** [Paper Link](http://www.shichuan.org/doc/185.pdf)

  🎯NC  🌐Citation, Co-purchase  📊Text  🧩Homogeneous Graph

- **DTGB:A Comprehensive Benchmark for Dynamic Text-Attributed Graphs** [Paper Link](https://arxiv.org/pdf/2406.12072)

  🎯LP, LC  🌐Dialogue, Social, Co-purchase  📊*****Text  🧩Dynamic Graph, Bipartite Graph

- **Harnessing Explanations: LLM-to-LM Interpreter for Enhanced Text-Attributed Graph Representation Learning** [Paper Link](https://arxiv.org/pdf/2305.19523)

  🎯NC  🌐Citation, Co-purchase  📊Text  🧩Homogeneous Graph

- **Mosaic of Modalities: A Comprehensive Benchmark for Multimodal Graph Learning** [Paper Link](https://arxiv.org/pdf/2406.16321)

  🎯NC, LP  🌐Co-purchase, Online Review  📊Multimodal (Text, Image)  🧩Homogeneous Graph

- **Multi-Scale Heterogeneous Text-Attributed Graph Datasets From Diverse Domains** [Paper Link](https://arxiv.org/pdf/2412.08937)

  🎯NC  🌐Movie Review, Patent, Q&A, Citation  📊Text, Embedding  🧩Heterogeneous Graph

- **PowerGraph: A Power Grid Benchmark Dataset for Graph Neural Networks** [Paper Link](https://arxiv.org/pdf/2402.02827)

  🎯NR, GC, GR  🌐Power Grid  📊BoW  🧩Homogeneous Graph

- **RelBench: A Benchmark for Deep Learning on Relational Databases** [Paper Link](https://arxiv.org/pdf/2407.20060)

  🎯NC, NR, LP  🌐E-commerce, Social, Medical, Sports  📊BoW, Embedding  🧩Heterogeneous Graph, Spatio-temporal Graph

- **TAGLAS: An Atlas of Text-Attributed Graph Datasets in the Era of Large Graph and Language Models** [Paper Link](https://arxiv.org/pdf/2406.14683)

  🎯NC, GC, GR, LP, LC  🌐Citation, Molecular, Q&A, Movie Review, Online Review  📊Text  🧩Homogeneous Graph, Bipartite Graph

- **TEG-DB: A Comprehensive Dataset and Benchmark of Textual-Edge Graphs** [Paper Link](https://arxiv.org/pdf/2406.10310v1)

  🎯NC, LP  🌐Citation, Social, E-commerce, Co-purchase  📊*****Text  🧩Homogeneous Graph

- **TGB2.0: A Benchmark for Learning on Temporal Knowledge Graphs and Heterogeneous Graphs** [Paper Link](https://arxiv.org/pdf/2406.09639)

  🎯LP  🌐Online Review, Web  📊Embedding  🧩Heterogeneous Graph, Spatio-temporal Graph, Knowledge Graph

- **TabGraphs: A Benchmark and Strong Baselines for Learning on Graphs with Tabular Node Features** [Paper Link](https://arxiv.org/pdf/2409.14500)

  🎯NC, NR  🌐Online Review, Traffic, Game Social, Co-purchase  📊BoW  🧩Homogeneous Graph

- **Text-space Graph Foundation Models: Comprehensive Benchmarks and New Insights** [Paper Link](https://arxiv.org/pdf/2406.10727)

  🎯NC, LP, GC  🌐Citation, Co-purchase, Molecular  📊Text  🧩Homogeneous Graph

- **WelQrate: Defining the Gold Standard in Small Molecule Drug Discovery Benchmarking** [Paper Link](https://arxiv.org/pdf/2411.09820)

  🎯GC, GR  🌐Molecular  📊*****BoW  🧩

- **A GraphTalks, But Who’s Listening? Rethinking Evaluations for Graph-Language Models** [Paper Link](https://arxiv.org/pdf/2508.20583)

  🎯Reasoning  🌐Citation, Co-purchase, Traffic  📊*****Text  🧩Homogeneous Graph

- **Adaptive Heterogeneous Graph Neural Networks: Bridging Heterophily and Heterogeneity** [Paper Link](https://arxiv.org/pdf/2508.06034?)

  🎯NC  🌐Social, Movie Review  📊Embedding, BoW  🧩Heterogeneous Graph, Heterophilic Graph

- **CITE: A Comprehensive Benchmark for Heterogeneous Text-Attributed Graphs on Catalytic Materials** [Paper Link](https://arxiv.org/pdf/2508.15392)

  🎯NC  🌐Citation  📊Text   🧩Heterogeneous Graph

- **ChronoGraph: A Real-World Graph-Based Multivariate Time Series Dataset** [Paper Link](https://arxiv.org/pdf/2509.04449)

  🎯NC, NR  🌐Server  📊*****BoW   🧩Spatio-temporal Graph

- **Depth-Adaptive Graph Neural Networks via Learnable Bakry-Émery Curvature** [Paper Link](https://dl.acm.org/doi/pdf/10.1145/3711896.3736905)

  🎯NR  🌐Citation, Power Grid  📊Embedding  🧩Homogeneous Graph, Heterophilic Graph

- **DiffGraph: Heterogeneous Graph Diffusion Model** [Paper Link](https://arxiv.org/pdf/2501.02313)

  🎯NC, LP  🌐E-commerce  📊BoW   🧩Heterogeneous Graph

- **Enhanced Insurance Claim Prediction via Decoupled Graph Neural Networks with Pseudo Labeling** [Paper Link](https://dl.acm.org/doi/pdf/10.1145/3711896.3737213)

  🎯NR  🌐Social  📊Embedding  🧩Multiplex Graph

- **FOS: ALarge-Scale Temporal Graph Benchmark for Scientific Interdisciplinary Link Prediction** [Paper Link](https://arxiv.org/pdf/2511.18631)

  🎯LP  🌐Citation  📊Embedding  🧩Spatio-temporal Graph

- **FedMetro: Efficient Metro Passenger Flow Prediction via Federated Graph Learning** [Paper Link](https://dl.acm.org/doi/pdf/10.1145/3711896.3737218)

  🎯NR  🌐Traffic  📊BoW  🧩Spatio-temporal Graph

- **Graph Alignment via Dual-Pass Spectral Encoding and Latent Space Communication** [Paper Link](https://arxiv.org/pdf/2509.09597) 

  🎯GA  🌐Protein, Social, Citation, Co-authorship, Online Review  📊BoW  🧩Homogeneous Graph

- **Graph World Model** [Paper Link](https://arxiv.org/pdf/2507.10539)

  🎯NG, LP, NC, GC, Reasoning  🌐Citation, Co-purchase, Workflow  📊Text, Multimodal (Text, Image, Tabular)  🧩Homogeneous Graph, Bipartite Graph

- **GraphBench: Next-Generation Graph Learning Benchmarking** [Paper Link](https://arxiv.org/pdf/2512.04475)

  🎯NR, LP, LC, GR, GC, GG  🌐Circuit, Social, Algorithm, Map  📊*****Text, Multimodal (Text, Image, Tabular)  🧩Homogeneous Graph, Spatio-temporal Graph

- **LLM-Empowered Class Imbalanced Graph Prompt Learning for Online Drug Trafficking Detection** [Paper Link](https://arxiv.org/pdf/2503.01900)

  🎯NC  🌐Social  📊Embedding  🧩Heterogeneous Graph

- **NineRec: A Benchmark Dataset Suite for Evaluating Transferable Recommendation** [Paper Link](https://arxiv.org/pdf/2309.07705)

  🎯LP 🌐E-commerce  📊Multimodal (Text, Image)  🧩Bipartite Graph

- **Towards Efficient LLM-aware Heterogeneous Graph Learning** [Paper Link](https://arxiv.org/pdf/2511.17923)

  🎯*****NC, LP 🌐E-commerce  📊Text  🧩Heterogeneous Graph, Bipartite Graph

- **Towards Quantifying Long-Range Interactions in Graph Machine Learning: a Large Graph Dataset and a Measurement** [Paper Link](https://arxiv.org/pdf/2503.09008)

  🎯NC 🌐Map, Traffic  📊*****BoW  🧩Homogeneous Graph

- **Towards Multimodal Graph Large Language Model** [Paper Link](https://arxiv.org/pdf/2506.09738)

  🎯NC, NG, LP, GC, Reasoning 🌐E-commerce,  Scene Graph, Co-purchase 📊Multimodal (Text, Image, Audio)  🧩Bipartite Graph, Homophily Graph, Knowledge Graph

- **When Graph Meets Multimodal: Benchmarking and Meditating on Multimodal Attributed Graph Learning** [Paper Link](https://dl.acm.org/doi/10.1145/3711896.3737404)

  🎯NC, LP 🌐Social, Co-purchase 📊Multimodal (Text, Image)  🧩Homogeneous Graph

- **When Heterophily Meets Heterogeneity: Challenges and a New Large-Scale Graph Benchmark** [Paper Link](https://arxiv.org/pdf/2407.10916)

  🎯NC, LP 🌐Social, E-commerce, Web, Citation 📊Embedding  🧩Heterogeneous Graph, Heterophilic Graph

- **A Benchmark Analysis of Graph and Non-Graph Methods for Caenorhabditis elegans Neuron Classification** [Paper Link](https://www.cs.emory.edu/~jyang71/files/neurobench.pdf)

  🎯NC 🌐Neuron 📊BoW  🧩Homogeneous Graph

- **GLEN-Bench: A Graph-Language based Benchmark for Nutritional Health** [Paper Link](https://arxiv.org/pdf/2601.18106)

  🎯NC, LP, NG 🌐Nutrition-Health  📊BoW, Embedding  🧩Heterogeneous Graph, Knowledge Graph

- **Opbench: A Graph Benchmark to Combat the Opioid Crisis** [Paper Link](https://arxiv.org/pdf/2602.14602)

  🎯NC 🌐Medical  📊Text, Embedding  🧩Heterogeneous Graph, Hypergraph, Multiplex Graph

- **RelBench v2: A Large-Scale Benchmark and Repository for Relational Data** [Paper Link](https://arxiv.org/pdf/2602.12606)

  🎯NC, NR, NG, LP  🌐Citation, Medical, Workflow, E-commerce  📊Embedding  🧩Heterogeneous Graph

- **Social-Aware Multimodal Graph Learning for Micro-Video Popularity Prediction** [Paper Link](https://ieeexplore.ieee.org/document/11417265/)

  🎯GR  🌐E-commerce  📊Multimodal (Text, Image)  🧩Heterogeneous Graph

- **Reinforced Neighborhood Selection Guided Multi-Relational Graph Neural Networks** [Paper Link](https://dl.acm.org/doi/pdf/10.1145/3490181)

  🎯NC  🌐Medical  📊Embedding  🧩Multiplex Graph

- **Multi-Scale Attributed Node Embedding** [Paper Link](https://arxiv.org/pdf/1909.13021)

  🎯NC, NR  🌐Web, Social  📊Embedding  🧩Homogeneous Graph

- **OpenMAG: A Comprehensive Benchmark for Multimodal-Attributed Graph** [Paper Link](https://arxiv.org/pdf/2602.05576)

  🎯NC, LP, NG  🌐E-commerce  📊Multimodal (Text, Image),   🧩Bipartite Graph, Homogeneous Graph



## 📖 Graph Surveys & Reviews

### 2.1 Research

#### 2.1.1 Self-Supervised GNN

- **A Survey on Self-Supervised Graph Foundation Models: Knowledge-Based Perspective** [Paper Link](https://arxiv.org/pdf/2403.16137)
- **Towards Graph Contrastive Learning: A Survey and Beyond** [Paper Link](https://arxiv.org/pdf/2405.11868?)
- **Self-Supervised Learning for Graph-Structured Data in Healthcare Applications: A Comprehensive Review** [Paper Link](https://arxiv.org/pdf/2412.05312?)

#### 2.1.2 Graph Foundation Model & Prompting

- **A Survey on Self-Supervised Graph Foundation Models: Knowledge-Based Perspective** [Paper Link](https://arxiv.org/pdf/2403.16137)
- **Graph Foundation Models: A Comprehensive Survey** [Paper Link](https://arxiv.org/pdf/2505.15116)
- **Graph Foundation Models for Recommendation: A Comprehensive Survey** [Paper Link](https://arxiv.org/pdf/2502.08346)
- **A Survey of Generalization of Graph Anomaly Detection: From Transfer Learning to Foundation Models** [Paper Link](https://arxiv.org/pdf/2509.06609)
- **Out-of-Distribution Generalization in Graph Foundation Models** [Paper Link](https://arxiv.org/pdf/2601.21067)
- **Graph Prompting for Graph Learning Models: Recent Advances and Future Directions** [Paper Link](https://arxiv.org/pdf/2506.08326)

#### 2.1.3 Graph Generation

- **A Systematic Survey on Generative Models for Graph Generation** [Paper Link](https://www.preprints.org/frontend/manuscript/2371b1d4089f03f490326dbdb91bd7bc/download_pub)
- **A Survey of Large Language Models on Generative Graph Analytics: Query, Learning, and Applications** [Paper Link](https://arxiv.org/pdf/2404.14809)

#### 2.1.4 Graph Transformer

- **Graph Transformers: A Survey** [Paper Link](https://arxiv.org/pdf/2407.09777?)
- **A Survey of Graph Transformers: Architectures, Theories and Applications** [Paper Link](https://arxiv.org/pdf/2502.16533?)

#### 2.1.5 Imbalance/Incomplete Graph

- **Incomplete Graph Learning: A Comprehensive Survey** [Paper Link](https://arxiv.org/pdf/2502.12412)
- **A Survey of Graph Neural Networks in Real world: Imbalance, Noise, Privacy and OOD Challenges** [Paper Link](https://arxiv.org/pdf/2403.04468)

#### 2.1.6 Reduction

- **A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation** [Paper Link](https://arxiv.org/pdf/2402.03358)
- **A Survey on Graph Condensation** [Paper Link](https://arxiv.org/pdf/2402.02000)
- **Graph Condensation: A Survey** [Paper Link](https://arxiv.org/pdf/2401.11720)
- **Learning to Reduce the Scale of Large Graphs: A Comprehensive Survey** [Paper Link](https://dl.acm.org/doi/pdf/10.1145/3729427)
- **Finding the Cores of Higher Graphs Using Geometric and Topological Means: A Survey** [Paper Link](https://arxiv.org/pdf/2506.19857)

#### 2.1.7 Temporal, Dynamic & Continual 

- **Dynamic Text-Attributed Graphs and Learning Models for Community Evolution: A Survey of Recent Advances** [Paper Link](https://www.publications.scrs.in/uploads/final_menuscript/822ab703ff97f28905558d3502c7974b.pdf) 
- **Advances in Continual Graph Learning for Anti-Money Laundering Systems: A Comprehensive Review** [Paper Link](https://arxiv.org/pdf/2503.24259?)  
- **A Survey on Temporal Interaction Graph Representation Learning: Progress, Challenges, and Opportunities** [Paper Link](https://arxiv.org/pdf/2505.04461?)
- **Review on Development of Spatio-Temporal Graph Neural Networks for Traffic Flow Prediction** [Paper Link](https://arxiv.org/pdf/2307.00495)

#### 2.1.8 Fairness

- **Fairness in Graph Learning Augmented with Machine Learning: A Survey** [Paper Link](https://arxiv.org/pdf/2504.21296?) 

#### 2.1.9 TTA & OOD

- **Out-of-Distribution Detection on Graphs: A Survey** [Paper Link](https://arxiv.org/pdf/2502.08105)
- **A Survey of Graph Neural Networks in Real world: Imbalance, Noise, Privacy and OOD Challenges** [Paper Link](https://arxiv.org/pdf/2403.04468)
- **Out-of-Distribution Generalization in Graph Foundation Models** [Paper Link](https://arxiv.org/pdf/2601.21067)
- **Test-Time Adaptation for Graph Learning: A Systematic Survey** [Paper Link](https://www.techrxiv.org/doi/full/10.36227/techrxiv.177138879.90217571)

#### 2.1.10 Complex Network

- **The Heterophilic Graph Learning Handbook: Benchmarks, Models, Theoretical Analysis, Applications and Challenges** [Paper Link](https://arxiv.org/pdf/2407.09618)
- **A Survey on Centrality and Importance Measures in Hypergraphs: Categorization and Empirical Insights** [Paper Link](https://arxiv.org/pdf/2512.00107)
- **A Survey of Geometric Graph Neural Networks: Data Structures, Models and Applications** [Paper Link](https://arxiv.org/pdf/2403.00485)
- **Hyperbolic Graph Embeddings: a Survey and an Evaluation on Anomaly Detection** [Paper Link](https://arxiv.org/pdf/2512.18826)
- **Pattern-Based Graph Classification: Comparison of Quality Measures and Importance of Preprocessing**

#### 2.1.11 Structure & Topology 

- **A Comprehensive Survey on Spectral Clustering with Graph Structure Learning** [Paper Link](https://arxiv.org/pdf/2501.13597)
- **Topology Identification and Inference over Graphs** [Paper Link](https://arxiv.org/pdf/2512.10183)
- **A Topical Review of Graph Embedding in Graph Neural Networks** [Paper Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11299063)
- **Graph Neural Network based on Graph Kernel: A Survey** [Paper Link](https://www.sciencedirect.com/science/article/abs/pii/S0031320324010586) 
- **Pattern-Based Graph Classification: Comparison of Quality Measures and Importance of Preprocessing** [Paper Link](https://arxiv.org/pdf/2507.00039)

#### 2.1.12 Theory & Insight

- **Graph ODEs and Beyond: A Comprehensive Survey on Integrating Differential Equations with Graph Neural Networks** [Paper Link](https://arxiv.org/pdf/2503.23167)
- **Efficient Algorithms for Personalized PageRank Computation: A Survey** [Paper Link](https://arxiv.org/pdf/2403.05198)
- **Graph Learning: A Survey** [Paper Link](https://arxiv.org/pdf/2507.05636)
- **Survey on Generalization Theory for Graph Neural Networks** [Paper Link](https://arxiv.org/pdf/2503.15650?)

### 2.2 Application

#### 2.2.1 Healthcare & Bioinformatics

- **A Review of Graph Neural Networks in Epidemic Modeling** [Paper Link](https://arxiv.org/pdf/2403.19852)
- **A Survey of Graph Neural Networks for Drug Discovery: Recent Developments and Challenges** [Paper Link](https://arxiv.org/pdf/2509.07887)
- **Graph Learning in Bioinformatics: A Survey of Graph Neural Network Architectures, Biological Graph Construction and Bioinformatics Applications** [Paper Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC12938586/)
- **Graph Neural Networks in Modern AI-aided Drug Discovery** [Paper Link](https://arxiv.org/pdf/2506.06915?)
- **Graph Neural Networks in Multi-Omics Cancer Research: A Structured Survey** [Paper Link](https://arxiv.org/pdf/2506.17234)
- **Graph Neural Networks for Source Detection: A Review and Benchmark Study** [Paper Link](https://arxiv.org/pdf/2512.20657)
- **Interpretable graph-based models on multimodal biomedical data integration: A technical review and benchmarking** [Paper Link](https://arxiv.org/pdf/2505.01696)
- **Medical Applications of Graph Convolutional Networks Using Electronic Health Records: A Survey** [Paper Link](https://arxiv.org/pdf/2502.09781)
- **Recent Developments in GNNs for Drug Discovery** [Paper Link](https://arxiv.org/pdf/2506.01302)
- **Self-Supervised Learning for Graph-Structured Data in Healthcare Applications: A Comprehensive Review** [Paper Link](https://arxiv.org/pdf/2412.05312?)

#### 2.2.2 Anomaly Detection

- **A Survey on Graph Neural Networks for Fraud Detection in Ride Hailing Platforms** [Paper Link](https://arxiv.org/pdf/2512.23777)
- **Graph-based Fake Account Detection: A Survey** [Paper Link](https://arxiv.org/pdf/2507.06541?)
- **Recent Advances in Malware Detection: Graph Learning and Explainability** [Paper Link](https://arxiv.org/pdf/2502.10556?)
- **A Survey of Generalization of Graph Anomaly Detection: From Transfer Learning to Foundation Models** [Paper Link](https://arxiv.org/pdf/2509.06609)
- **A Survey of Heterogeneous Graph Neural Networks for Cybersecurity Anomaly Detection** [Paper Link](https://arxiv.org/pdf/2510.26307)
- **Advances in Continual Graph Learning for Anti-Money Laundering Systems: A Comprehensive Review** [Paper Link](https://arxiv.org/pdf/2503.24259?)  
- **Hyperbolic Graph Embeddings: a Survey and an Evaluation on Anomaly Detection** [Paper Link](https://arxiv.org/pdf/2512.18826)

#### 2.2.3 Agent & RAG

- **Graph-based Agent Memory: Taxonomy, Techniques, and Applications** [Paper Link](https://arxiv.org/pdf/2602.05665)
- **Graph-based Approaches and Functionalities in Retrieval-Augmented Generation: A Comprehensive Survey** [Paper Link](https://arxiv.org/pdf/2504.10499)
- **Graph-Based Re-ranking: Emerging Techniques, Limitations, and Opportunities** [Paper Link](https://arxiv.org/pdf/2503.14802)
- **Graphs Meet AI Agents: Taxonomy, Progress, and Future Opportunities** [Paper Link](https://arxiv.org/pdf/2506.18019)
- **Graph Neural Networks, Deep Reinforcement Learning and Probabilistic Topic Modeling for Strategic Multiagent Settings** [Paper Link](https://arxiv.org/pdf/2511.10501v3)
- **Graph Neural Network Meets Multi-Agent Reinforcement Learning: Fundamentals, Applications, and Future Directions** [Paper Link](https://arxiv.org/pdf/2404.04898)

#### 2.2.4 Recommendation

- **Graph Foundation Models for Recommendation: A Comprehensive Survey** [Paper Link](https://arxiv.org/pdf/2502.08346)
- **Graph Neural Networks for Collaborative Filtering: A Survey on Ranking Prediction** [Paper Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11359174)
- **Multi-Behavior Recommender Systems: A Survey** [Paper Link](https://arxiv.org/pdf/2503.06963?)

#### 2.2.5 Federated & Cross-Domain

- **A Comprehensive Data-centric Overview of Federated Graph Learning** [Paper Link](https://arxiv.org/pdf/2507.16541?)
- **A Survey of Cross-domain Graph Learning: Progress and Future Directions** [Paper Link](https://arxiv.org/pdf/2503.11086)

#### 2.2.6 Transportation

- **Data Mining in Transportation Networks with Graph Neural Networks: A Review and Outlook** [Paper Link](https://arxiv.org/pdf/2501.16656) 
- **Graph Neural Networks for Vehicular Social Networks: Trends, Challenges, and Opportunities** [Paper Link](https://arxiv.org/pdf/2511.14720)
- **Review on Development of Spatio-Temporal Graph Neural Networks for Traffic Flow Prediction** [Paper Link](https://arxiv.org/pdf/2307.00495)

#### 2.2.7 NLP & LLM

- **A Survey of Large Language Models for Data Challenges in Graphs** [Paper Link](https://arxiv.org/pdf/2505.18475)
- **A Survey of Large Language Models on Generative Graph Analytics: Query, Learning, and Applications** [Paper Link](https://arxiv.org/pdf/2404.14809)
- **A Survey of Quantized Graph Representation Learning: Connecting Graph Structures with Large Language Models** [Paper Link](https://arxiv.org/pdf/2502.00681)
- **Large Language Models Meet Text-Attributed Graphs: A Survey of Integration Frameworks and Applications** [Paper Link](https://arxiv.org/pdf/2510.21131)
- **Trustworthy GNNs with LLMs: A Systematic Review and Taxonomy** [Paper Link](https://arxiv.org/pdf/2502.08353?)
- **Graph2text or Graph2token: A Perspective of Large Language Models for Graph Learning** [Paper Link](https://arxiv.org/pdf/2501.01124)
- **A Systematic Survey on Generative Models for Graph Generation** [Paper Link](https://www.preprints.org/frontend/manuscript/2371b1d4089f03f490326dbdb91bd7bc/download_pub)
- **Exploring Graph-Based Techniques in Text Data Processing: A Comprehensive Survey of NLP Advancements** [Paper Link](https://www.icck.org/filebob/uploads/storage/TETAI_L7uaFiARV760LTrDA.pdf)
- **Dynamic Text-Attributed Graphs and Learning Models for Community Evolution: A Survey of Recent Advances** [Paper Link](https://www.publications.scrs.in/uploads/final_menuscript/822ab703ff97f28905558d3502c7974b.pdf) 
- **Graph4LLM:A Systematic Survey of Graph-Enhanced Large Language Models** [Paper Link](http://shichuan.org/doc/215.pdf)
- **Graphs for LLMs: A Survey of Graph-Assisted Large Language Models** [Paper Link](https://d197for5662m48.cloudfront.net/documents/publicationstatus/308271/preprint_pdf/8467d8fa2a52e780399614ed3a356245.pdf)

#### 2.2.8 Databases & Tabular

- **Graph Neural Networks for Databases: A Survey** [Paper Link](https://arxiv.org/pdf/2502.12908)
- **Relational Deep Learning: Challenges, Foundations and Next-Generation Architectures** [Paper Link](https://arxiv.org/pdf/2506.16654)
- **Graph Neural Networks for Tabular Data Learning: A Survey with Taxonomy & Directions** [Paper Link](https://arxiv.org/pdf/2401.02143)

#### 2.2.9 Alloy Design

- **Advances in Graph Neural Networks for Alloy Design and Properties Predictions: A Review** [Paper Link](https://www.oaepublish.com/articles/jmi.2025.42?to=comment)



## ⚖️ Graph Benchmarks











## 🤝 Contributors

<table style="border-collapse: collapse;">
  <tr>
    <td align="center" valign="top" width="160px" style="border: none;">
      <a href="https://github.com/SuperYeYu" target="_blank">
        <img src="https://github.com/SuperYeYu.png" width="100px" style="border-radius:50%; margin-bottom: 8px;" alt="Yeyu Yan"/>
        <br />
        <b>Yeyu Yan</b>
      </a>
      <br />
      <a href="https://superyeyu.github.io/" target="_blank">
        <small>🌐 Homepage</small>
      </a>
    </td>
    <td align="center" valign="top" width="160px" style="border: none;">
      <a href="https://github.com/boshizhu" target="_blank">
        <img src="https://github.com/boshizhu.png" width="100px" style="border-radius:50%; margin-bottom: 8px;" alt="Xiangkai Zhu"/>
        <br />
        <b>Xiangkai Zhu</b>
      </a>
      <br />
      <a href="https://github.com/boshizhu" target="_blank">
        <small>🌐 Homepage</small>
      </a>
    </td>
    <td align="center" valign="top" width="160px" style="border: none;">
      <a href="https://github.com/SsGood" target="_blank">
        <img src="https://github.com/SsGood.png" width="100px" style="border-radius:50%; margin-bottom: 8px;" alt="Xiangkai Zhu"/>
        <br />
        <b>Shuai Zheng</b>
      </a>
      <br />
      <a href="https://scholar.google.com/citations?user=8UFwA_0AAAAJ&hl=zh-CN" target="_blank">
        <small>🌐 Homepage</small>
      </a>
    </td>
  </tr>
</table>

**📌 Important Note:** As this initiative commenced in mid-2024, our curation intentionally excludes older literature to prioritize recent, state-of-the-art advancements. Additionally, this repository features dedicated sections for **💡 Graph Insights** and **📈 Graph Evaluation Metrics**, which will be subject to continuous updates in future releases.
