<div align="center">

# Hi, I'm Bhim 👋
### Machine Learning Engineer · Data Scientist — I'd rather ship something than keep polishing it in a notebook

**ML Intern @ SmartED Innovations · Ex-Data Scientist @ TCS (Walmart Global Tech, 3.8 yrs) · MCA (AI/ML)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bhimaiengineer)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/bhimaiengineer)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhimrajbhar.ai.engineer@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BhimAIEngineer)

</div>

<br/>

![👨‍💻 About Me](https://img.shields.io/badge/👨‍💻_ABOUT_ME-4A6FE3?style=for-the-badge&logoColor=white)

I spent 3.8 years at TCS on the Walmart Global Tech account as a Data Scientist — mostly demand forecasting, NLP pipelines, and computer vision for real business problems. Somewhere in there I got tired of models that worked great in a notebook and then just... sat there. Nobody was actually shipping them.

So that's what I've been fixing for the past year. I'm doing an MCA (AI/ML) at Uttaranchal University, working as an ML Intern at SmartED Innovations, and using every side project as an excuse to deploy something properly — Docker, an actual API, experiment tracking, CI. Not another notebook that ends with "and then we could deploy this."

Right now I'm deep into production ML systems, computer vision for industrial use cases, predictive maintenance, and multi-agent LLM systems with LangGraph.

<br/>

![🚀 Featured Projects](https://img.shields.io/badge/🚀_FEATURED_PROJECTS-4A6FE3?style=for-the-badge&logoColor=white)

### 🏭 [Industrial Defect Detection System](https://github.com/BhimAIEngineer/industrial-defect-detection)
Catches defects on a manufacturing line as they happen, instead of after the batch has already shipped.
`YOLOv8` · `FastAPI` · `Docker` · `MLflow` · `GitHub Actions CI` · `Streamlit dashboard`

### 🏥 Disease Prediction & Medical Diagnosis System
Combines image-based and tabular models for diagnosis, with SHAP baked in so a doctor isn't just told "trust the model."
`ResNet50 (94% acc.)` · `Custom ANN (+6% over baseline)` · `SHAP` · `FastAPI` · `Docker` · `MLflow` · `CI/CD`

### ✈️ Turbofan Predictive Maintenance (Remaining Useful Life)
Predicts how much life is left in a turbofan engine using NASA's CMAPSS data, then runs the numbers on what that's actually worth compared to reactive maintenance.
`Feature Engineering` · `Linear Regression / Random Forest / XGBoost` · `LSTM` · `FastAPI` · `Streamlit` · `Cost-Simulation`

### 🤖 Multi-Agent Healthcare Triage Assistant *(in progress)*
Splits triage work across cooperating agents instead of asking one giant prompt to do everything at once.
`LangGraph` · `Agentic Workflows` · `LLM Orchestration`

### 📧 Spam Email Classifier
Raw text in, deployable model out — 97.5% accuracy.
`Python` · `NLTK` · `Multinomial Naive Bayes` · `Scikit-learn`

### 🏠 House Price Predictor
Regression on California housing data, wrapped in a Streamlit app so you can actually see which features are driving a prediction.
`Linear Regression` · `Scikit-learn` · `Streamlit`

> 📌 *None of these are just training scripts — each one ships with an API, tracking, and a container around it.*

<br/>

![🧰 Tech Toolbox](https://img.shields.io/badge/🧰_TECH_TOOLBOX-4A6FE3?style=for-the-badge&logoColor=white)

<table>
<tr>
<td valign="top" width="50%">

#### 📈 Data Science & Classical ML
![EDA](https://img.shields.io/badge/-EDA-6C5CE7?style=flat-square) ![A/B Testing](https://img.shields.io/badge/-A/B_Testing-6C5CE7?style=flat-square) ![XGBoost](https://img.shields.io/badge/-XGBoost-6C5CE7?style=flat-square&logo=xgboost&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-6C5CE7?style=flat-square) ![Random Forest](https://img.shields.io/badge/-Random_Forest-6C5CE7?style=flat-square) ![SVM](https://img.shields.io/badge/-SVM-6C5CE7?style=flat-square) ![Clustering](https://img.shields.io/badge/-Clustering-6C5CE7?style=flat-square) ![Pandas](https://img.shields.io/badge/-Pandas-6C5CE7?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-6C5CE7?style=flat-square&logo=numpy&logoColor=white)
- **EDA & Statistics** — hypothesis testing, A/B testing, distribution analysis, outlier detection
- **Feature Engineering** — encoding, scaling, imputation, dimensionality reduction, custom pipelines
- **Classical ML** — XGBoost, LightGBM, Random Forest, SVM, regression, clustering (k-means, hierarchical)
- **Model Evaluation** — cross-validation, ROC-AUC, F1, RMSE, calibration curves, business-metric alignment
- **Tooling** — Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly
- **Applied EDA** — deep exploratory analysis on structured & unstructured client data, missing-value and outlier strategies for messy real-world datasets

#### 🧠 Deep Learning
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![CNN](https://img.shields.io/badge/-CNNs-1E90FF?style=flat-square) ![LSTM](https://img.shields.io/badge/-RNN/LSTM-1E90FF?style=flat-square) ![Transformers](https://img.shields.io/badge/-Transformers-1E90FF?style=flat-square)
- **Computer Vision Backbones** — CNNs, transfer learning (ResNet, EfficientNet, VGG)
- **Sequential Modeling** — RNNs, LSTMs, time-series forecasting
- **Transformers** — attention mechanisms, encoder-decoder architectures, BERT
- **Training Practices** — batch normalization, dropout, LR schedulers, early stopping, regularization
- **Frameworks** — PyTorch, TensorFlow, Keras
- **Time-Series Forecasting** — demand/remaining-useful-life forecasting with deep sequential models on real production data

#### 💬 Natural Language Processing
![BERT](https://img.shields.io/badge/-BERT-FFD21E?style=flat-square) ![NER](https://img.shields.io/badge/-NER-FFD21E?style=flat-square) ![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![NLTK](https://img.shields.io/badge/-NLTK-FFD21E?style=flat-square)
- **Text Understanding** — text classification, sentiment analysis, named entity recognition (NER)
- **Text Processing** — cleaning, tokenization, embeddings (Word2Vec, TF-IDF)
- **Transformer-based NLP** — BERT fine-tuning for domain-specific tasks
- **Retrieval-Aware NLP** — semantic search, document Q&A, RAG-style pipelines over unstructured text
- **Applied NLP** — production text classification & document processing pipelines built for real client use cases

#### 🗄️ SQL & Microsoft Office
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Excel](https://img.shields.io/badge/-Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) ![PowerPoint](https://img.shields.io/badge/-PowerPoint-B7472A?style=flat-square&logo=microsoftpowerpoint&logoColor=white) ![Word](https://img.shields.io/badge/-Word-2B579A?style=flat-square&logo=microsoftword&logoColor=white)
- **SQL** — writing and optimizing queries (joins, aggregations, window functions) for data extraction, EDA, and reporting from relational databases
- **Excel** — pivot tables, formulas, data cleaning, and dashboards for quick business-facing analysis
- **PowerPoint** — building project reports and stakeholder-facing presentations (used for MCA coursework submissions and client-facing decks)
- **Word** — structured documentation, project reports, and technical write-ups
- **Business Reporting** — translating model outputs and analysis into clear, non-technical summaries for stakeholders

</td>
<td valign="top" width="50%">

#### ⚙️ ML Engineering & MLOps
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Optuna](https://img.shields.io/badge/-Optuna-2088FF?style=flat-square)
- **Model Deployment** — FastAPI, Flask, REST APIs, model serialization (Pickle, ONNX)
- **Experiment Tracking** — MLflow for metrics, artifacts, and model registry
- **Containerization** — Docker for reproducible, portable ML environments
- **CI/CD** — GitHub Actions pipelines for automated testing and deployment
- **Hyperparameter Tuning** — GridSearchCV, RandomizedSearch, Optuna
- **Code Quality** — modular pipelines, OOP design, reproducible notebooks, Git/GitHub version control
- **End-to-End Ownership** — train → track → containerize → serve, applied consistently across every shipped project

#### 🤖 Generative AI & Agents
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square) ![FAISS](https://img.shields.io/badge/-FAISS-1C3C3C?style=flat-square) ![ChromaDB](https://img.shields.io/badge/-ChromaDB-1C3C3C?style=flat-square) ![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
- **LLMs** — prompt engineering, fine-tuning (LoRA/QLoRA), LLM API integration
- **RAG Systems** — retrieval-augmented generation, semantic search, document Q&A
- **Vector Databases** — FAISS, ChromaDB, embeddings
- **AI Agents** — ReAct, tool-calling, LangChain/LangGraph agents, multi-agent orchestration
- **Applied Agentic Systems** — multi-agent workflows built for real triage/support use cases, not just single-chain demos

#### 👁️ Computer Vision
![YOLOv8](https://img.shields.io/badge/-YOLOv8-00FFFF?style=flat-square) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![SHAP](https://img.shields.io/badge/-SHAP-5C3EE8?style=flat-square)
- **Detection & Classification** — object detection (YOLOv8), image classification
- **Transfer Learning** — fine-tuning pretrained backbones for domain-specific vision tasks
- **Explainability** — model interpretability with SHAP for vision & tabular models alike
- **Serving** — real-time inference pipelines, dashboarding (Streamlit)
- **Industrial CV** — defect detection for manufacturing lines, built and deployed as a full production pipeline

#### ☁️ Cloud & Deployment
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
- **AWS** — S3, EC2, SageMaker basics
- **Google Cloud Platform** — GCP core services for ML workloads
- **Microsoft Azure** — Azure ML for model training & deployment
- **Deployment** — Dockerized, cloud-ready model APIs; CI/CD for ML (learning)
- **Scaling Path** — actively building toward full cloud-native ML deployment (SageMaker end-to-end, managed pipelines)

</td>
</tr>
</table>

<p align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,mysql,docker,git,github,aws,gcp,azure,fastapi,flask,linux,vscode&theme=dark" />
</p>

<br/>

![💼 Experience](https://img.shields.io/badge/💼_EXPERIENCE-4A6FE3?style=for-the-badge&logoColor=white)

| Role | Company | Duration |
|---|---|---|
| **ML Intern** | SmartED Innovations (EdTech, remote) | Jun 2026 – Present |
| **Data Scientist** | TCS (Walmart Global Tech account) | 3.8 yrs (ended Jul 2025) |

<br/>

![📊 GitHub Stats](https://img.shields.io/badge/📊_GITHUB_STATS-4A6FE3?style=for-the-badge&logoColor=white)

<div align="center">

<img src="https://streak-stats.demolab.com/?user=BhimAIEngineer&theme=tokyonight&hide_border=true" width="60%" />

</div>

<br/>

![🎓 Currently](https://img.shields.io/badge/🎓_CURRENTLY-4A6FE3?style=for-the-badge&logoColor=white)

- Doing an MCA (AI/ML) at Uttaranchal University
- Building a new project for basically every role I apply to — CV, predictive maintenance, agents, whatever the job actually needs
- Open to **Data Scientist / Machine Learning Engineer** roles

<br/>

<div align="center">

📫 **Let's connect** — [LinkedIn](https://linkedin.com/in/bhimaiengineer) · [Kaggle](https://kaggle.com/bhimaiengineer) · [Email](mailto:bhimrajbhar.ai.engineer@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=BhimAIEngineer&label=Profile%20Views&color=00C9FF&style=flat)

</div>
