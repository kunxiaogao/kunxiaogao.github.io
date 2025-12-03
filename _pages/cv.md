---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Kunxiao Gao

📄 [PDF version]({{ '/images/cv.pdf' | relative_url }}){:target="_blank"}

**Email:** kgao9@jh.edu | **GitHub:** [kunxiaogao](https://github.com/kunxiaogao)

## Education

**Johns Hopkins University**, Baltimore, MD  
*M.S.E. in Data Science* | 08/2023 – Present | GPA: 3.87/4

Core: Artificial Intelligence, Deep Learning, Machine Learning for Medical Applications, Machine Translation, Reinforcement Learning, Applied Statistics and Data Analysis, Algorithms.

**University of California, Santa Barbara**, Santa Barbara, CA  
*B.Sc. in Statistics and Data Science* | 09/2019 – 04/2023 | GPA: 3.94/4

Core: Regression Analysis, Advanced Statistical Models, Machine Learning, Bayesian Data Analysis, Big Data Analytics.  
Honors: Dean's Honor List (Spring 2020 – Spring 2023).

## Publications

Gao, K., Favaro, A., Dehak, N., & Moro-Velázquez, L. (2024). *Identifying Early Markers of Alzheimer's Disease through Longitudinal Analysis of Language and Speech Patterns.* npj Dementia – Nature (to be submitted Dec 2024). [PDF](https://www.isca-archive.org/interspeech_2025/gao25b_interspeech.pdf)

## Selected Academic & Professional Research Experience

### Identifying Early Markers of Alzheimer's Disease through Longitudinal Analysis of Language and Speech Patterns
*03/2024 – Present* | Center for Speech and Language Processing, JHU  
Supervisors: Associate Prof. Laureano Moro-Velazquez and Assistant Prof. Najim Dehak

- Investigated early Alzheimer's Disease (AD) detection using longitudinal speech analysis, combining acoustic and linguistic features for binary classification and prodromal marker discovery.  
- Collected 5,000+ recordings up to 10 years pre-diagnosis, applied noise reduction, diarization, and segment filtering to ensure data quality.  
- Extracted acoustic and linguistic features with models such as Llama3 and Wav2Vec 2.0 to generate interpretable/non-interpretable features for early AD signs.  
- Developed and tested classification models (SVM, XGBoost, MLPs), performed longitudinal statistical analysis, and identified significant speech markers (pauses, pitch variation, syntactic complexity) for clinical detection and monitoring.  
- Achieved 0.80 accuracy on pre-diagnosis speech patterns using NIFMs, capturing subtle linguistic and acoustic cues.

### GNN Efficiency Improvements by Using Graph Sampling Strategies
*02/2023 – Present* | Department of Applied Mathematics & Statistics, JHU  
Supervisor: Assistant Prof. Luana Ruiz

- Built a GNN for correlation network prediction, optimizing computational efficiency while preserving predictive accuracy.  
- Applied graph signal sampling techniques (leveraging scores, adapted BFS) to construct smaller representative graphs; trained GNNs on reduced graphs and evaluated with a Graph Shift Operator on full data.  
- Derived Lipschitz continuous graphon-based error bounds showing leverage-score sampling converges faster than uniform sampling.  
- Matched performance of full-graph training with reduced compute, lowering MSE by ~26.8% versus traditional sampling.

### Glodon — Data Scientist Intern
*06/2023 – 08/2023* | Beijing, China

- Predicted customer purchasing behavior and prioritized high-potential clients.  
- Built fuzzy matching with jieba + regex to surface top 200 stop-words for rule-out during matching; engineered term-match tables.  
- Aggregated temporal customer data by project type/budget using back-tracking retrieval across custom time windows.  
- Trained XGBoost with randomized search and Bayesian optimization; best model achieved 0.6589 AUC and stable ROC/K-S behavior on test data.

### Amgen Knowledge Graphs Based on PubMedBERT Model
*01/2023 – 06/2023* | Amgen / UCSB  
Supervisor: Dr. Maxim Ivanov

- Applied NLP and text-mining to automate and refresh biomedical knowledge graphs for drug repurposing.  
- Reproduced BERT baseline from the BioRED paper; fine-tuned PubMedBERT for NER with 62% precision and 75% recall on unseen datasets.  
- Completed data preprocessing and deployed fine-tuned models on Amgen's corpus to extract biomedical entities and relations.

## Other Project Experience

### Machine Learning in Medical Applications
*02/2024 – 05/2024* | Johns Hopkins University  
Instructor: Associate Prof. Laureano Moro-Velazquez

- Built EEG + spectrogram classifiers for harmful brain activity (Harvard Challenge), reaching >86.04% accuracy.  
- Converted EEG to spectrograms, reorganized electrodes into four panels, and applied FFT for clarity.  
- Implemented ResNet and EfficientNet with Multiple Instance Learning (MIL), slicing embeddings into windowed instances to capture localized patterns.  
- Tuned MIL kernels/strides on dev sets to improve adaptability for seizure detection and broader diagnostic use.

### Machine Translation
*09/2023 – 12/2023* | Johns Hopkins University  
Instructor: Prof. Philipp Koehn

- Developed a hybrid statistical + neural French→English translation system.  
- Used Metropolis–Hastings to optimize beam search decoding, improving quality with lower compute.  
- Integrated phrase-based models, language models, and reordering strategies; benchmarked against standard metrics/baselines.

### Data Science Capstone
*09/2022 – 06/2023* | University of California, Santa Barbara  
Supervisor: Prof. Trevor Ruiz

- Practiced GLMs, KNN regression, Random Forests, NLP, and neural nets with professional data-processing pipelines.  
- Led group learning on real-world problems: ASD biomarker identification, fraud risk prediction, clustering countries by socio-economic and health factors.  
- Conducted literature reviews, trend analysis, and presentations to contribute to applied data science discussions.

## Other Working Experience

### Johns Hopkins University — Teaching Assistant for Applied Statistics and Data Analytics
*08/2024 – Present* | Baltimore, MD

- Conduct problem sessions, grade assignments, supervise exams, and maintain updated solutions.

### China Unicom — Software Engineer Intern, Technical Department
*06/2021 – 08/2021* | Beijing, China

- Built Python web crawler to collect and clean data for 30 banks (location, contact, metadata).  
- Helped expand user databases for nine provinces/cities with demographic and economic indicators.  
- Developed a parameterized Python program to auto-generate ICBC Urban Market Analysis PPTs.

## Awards and Honors

- Second Prize, CYPT (China Young Physicists' Tournament), Nankai University, China (August)

## Skills

**Programming:** Python (PyTorch, scikit-learn, TensorFlow, spaCy, requests), R, SAS, SQL, Spark, Shell, LaTeX  
**Languages:** Chinese (native), English (GRE 325: V158, Q167, AW 4.0)
