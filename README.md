# Mohammed Ismail Sarfaraz Shaik

### Data Scientist · ML Engineer
**Building production ML & GenAI systems end-to-end**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ismail-sarfaraz-shaik-87886b20a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sarfarazzzzz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m.shaik@gwu.edu)
[![Resume](https://img.shields.io/badge/Resume-2C5BB4?style=for-the-badge&logo=readthedocs&logoColor=white)](RESUME_PDF_URL)

📍 United States

---

## 🎯 About

I came to data science from engineering — which taught me that systems either work in the real world or they don't. I build ML and GenAI systems that fall on the **"work" side of that line**.

Recently completed my **M.S. in Data Science at The George Washington University**, while working as a Data Analyst at the Milken Institute School of Public Health on financial reconciliation, statistical analysis, and executive dashboards. Prior: a year at **Tata Consultancy Services** building HIPAA-compliant clinical ML infrastructure for a Fortune 500 medical devices client — Medallion ETL pipelines, shadow-deployment validation, and feature engineering that contributed to lifting downstream model AUC from **0.76 → 0.84**.

🎯 **Now open to full-time Data Scientist and ML Engineer roles.**

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**ML & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗_Hugging_Face-FFD21E?style=flat-square&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Data Engineering & Cloud**

![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Visualization & BI**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## 🚀 Featured Projects

### ☁️ [AWS CloudGuide — Cloud Architecture Assistant](https://github.com/Sarfarazzzzz/Final-Project-Group-BotBuilders/tree/main)
> **Hybrid RAG system over 100k+ AWS technical pages**

**Problem:** Navigating 100k+ pages of AWS documentation to find architectural answers is a nightmare.

**Build:** Engineered hybrid retrieval fusing **bge-m3 (dense)** + **BM25 (sparse)** via **Reciprocal Rank Fusion**, resolving semantic ambiguity across 100k+ pages. Deployed **Qwen-2.5-7B-Instruct** on T4 GPU with quantization tuning, achieving **sub-200ms latency** for citation-backed answers. Fault-tolerant ingestion pipeline processed 640MB raw text into 800k+ vector embeddings with recursive chunking for context preservation.

`Python` · `LangChain` · `Hugging Face` · `PyTorch` · `RAG` · `Vector Databases`

---

### 🚗 [EV Charging Station Placement Optimization](https://github.com/Sarfarazzzzz/Optimizing-EV-Charging-Station-Placement-Using-Data-Driven-Analysis)
> **Six-phase MILP optimization across 37k US census tracts**

**Problem:** Public EV charging infrastructure can't be deployed everywhere — planners need data-driven tradeoffs between coverage, cost, and equity mandates.

**Build:** Built six-phase optimization pipeline processing **37,093 census tracts across 20 East Coast states**. Formulated **two MILP models** (PuLP/CBC) for commuter coverage maximization and hub minimization. Encoded the federal **Justice40 mandate** as a hard constraint, lifting equity compliance from **12% → 41%** without sacrificing reach. Shipped a **Streamlit + Folium** dashboard letting planners explore budget/equity tradeoffs live.

`Python` · `GeoPandas` · `Linear Programming` · `Streamlit` · `Folium`

---

### 🎨 [Image Restoration & Colorization](https://final-project-group3demo.streamlit.app/)
> **End-to-end Computer Vision pipeline on AWS EC2**

**Problem:** Restoring degraded and black-and-white images requires overcoming severe regression-to-the-mean biases in deep learning.

**Build:** Architected pipeline on AWS EC2 (T4 GPU) processing the **18GB COCO dataset (118k images)** with Mixed Precision Training. Developed multi-subsystem framework: **ResNet-18 U-Net** for semantic colorization + **Depthwise Separable U-Net** for denoising. Pioneered a 5-phase Curriculum Learning strategy and custom Exponential Weighted Loss to mitigate regression-to-the-mean, achieving **85% model compression**, **2.5× faster convergence**, and **25 dB PSNR / 0.496 SSIM**. Deployed live Streamlit app for real-time restoration.

`PyTorch` · `Computer Vision` · `Deep Learning` · `AWS EC2` · `Transfer Learning` · `Streamlit`

---

### 🏥 [Hospital Readmissions Prediction](https://github.com/Sarfarazzzzz/Predicting-Hospital-Readmissions)
> **ML pipeline predicting 30-day clinical readmissions**

**Problem:** US hospitals lose billions annually on preventable readmissions — accurate risk scoring can target interventions where they matter.

**Build:** Trained Logistic Regression, Random Forest, and XGBoost on clinical and demographic features. Best result: **Random Forest (F1: 64.1%, AUC: 0.742)** — surfacing lab procedures, medications, and length of stay as top predictors. Handled class imbalance via weighting, performed full EDA, feature engineering, and hyperparameter tuning.

`Python` · `XGBoost` · `Random Forest` · `Healthcare Analytics` · `Classification`

---

### 🏏 [IPL Live Match Win Predictor](https://iplprediction-tywz8ytnoa5carjvxla3w6.streamlit.app/)
> **Real-time ball-by-ball win probability for T20 cricket**

**Problem:** T20 cricket is notoriously volatile — early-game win predictions are practically useless without taming chaotic in-game state.

**Build:** Engineered XGBoost model on 500+ historical IPL matches with custom features for live in-game state. Designed a **confidence-weighted blend-in algorithm** that stabilized early-over volatility, reducing forecast uncertainty by **60%**. Deployed as a live **Streamlit web app** with ball-by-ball predictions and probability trend visualization.

`XGBoost` · `Python` · `Streamlit` · `Feature Engineering` · `Predictive Modeling`

---

### 🍎 [Food Desert Prediction — 🏆 3rd Place, DSA Datathon 2025](https://github.com/Sarfarazzzzz/DSA-Datathon-2025)
> **Ensemble ML for food insecurity prediction**

**Problem:** Identifying at-risk communities for food insecurity is critical for targeted policy intervention — but requires fusing socioeconomic, geographic, and access-to-supply signals.

**Build:** Derived features from **10+ datasets** spanning socioeconomic, geographic, and accessibility indicators. Trained ensemble models (**Random Forest, CatBoost**) achieving **88% accuracy** identifying at-risk census tracts. Proposed data-driven policy recommendations to prevent food desert formation. Placed **3rd at DSA Datathon 2025**.

`Python` · `Random Forest` · `CatBoost` · `Ensemble Methods` · `Geospatial Analysis`

---

## 💼 Experience

**Data Analyst** · *George Washington University, Milken Institute School of Public Health* · Mar 2025 – May 2026

Reconciled $2M+ in historical funding allocations to fix corrupted inputs to departmental forecasting models. Built automated Python validation pipelines feeding live executive dashboards, and applied ANOVA on demographic and program variables to surface retention drivers — informing program redesign that closed a 25% attrition gap.

**Software Engineer (Data & ML)** · *Tata Consultancy Services* · Jun 2023 – Jun 2024

Built clinical risk-scoring ML infrastructure for a Fortune 500 medical devices client. Engineered PySpark feature pipelines and Medallion ETL syncing 12+ PHI sources to Snowflake, enabling real-time risk-scoring inference. Validated new pipelines via 30-day A/B testing against legacy heuristics. Designed HIPAA-compliant validation framework (Great Expectations) cutting data quality incidents 20% in production.

**Data Analyst Intern** · *Tata Consultancy Services* · Mar 2023 – May 2023

Supported a global capital markets client — tuned SQL queries on OLTP systems handling 50M+ daily transactions, built Tableau dashboards (LOD expressions, parameters) for self-service analytics, and conducted Pearson correlation analysis across 20+ metrics to define 15 strategic KPIs for risk and trading reporting.

---

## 🎓 Education

**M.S., Data Science** · *The George Washington University* · Aug 2024 – May 2026 · **GPA: 3.95**

*Relevant Coursework:* Deep Learning, Data Mining, Mathematics in Machine Learning, Data Analytics, Data Visualization, NLP

**B.Tech., Electronics and Communication Engineering** · *VNR Vignana Jyothi Institute of Engineering & Technology* · 2019 – 2023

---

## 📈 Beyond the Day Job

I also built and scaled a digital content platform (Instagram: *@never_beforu_ever_afteru*) to **15,000+ organic followers** — applying data-driven content strategy, audience segmentation, and engagement analytics in practice. Understanding what makes humans return to a feed taught me more about retention metrics than any course could.

---

## 📜 Certifications

- **Google Data Analytics Professional Certificate** — Google
- **Machine Learning Specialization** — NPTEL
- **Introduction to SQL** — University of Michigan
- **Introduction to R** — DataCamp

---

## 📫 Connect

Always open to conversations on **production ML, GenAI applications, or data systems** — and roles where I can build them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-ismail-sarfaraz-shaik-87886b20a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sarfarazzzzz)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:m.shaik@gwu.edu)
