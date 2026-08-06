
<div align="center">

# Hi, I'm Bhim Rajbhar👋
### Machine Learning Engineer · Data Scientist. I'd rather ship something than keep polishing it in a notebook.

**ML Intern @ SmartED Innovations · Ex-Data Scientist @ TCS (Walmart Global Tech, 3.8 yrs) · MCA (AI/ML)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/bhimaiengineer)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/bhimaiengineer)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhimrajbhar.ai.engineer@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BhimAIEngineer)

</div>

<br/>

### 👨‍💻 About Me 

I spent 3.8 years at TCS on the Walmart Global Tech account as a Data Scientist, mostly demand forecasting, NLP pipelines, and computer vision for real business problems. Somewhere in there I got tired of models that worked great in a notebook and then just... sat there. Nobody was actually shipping them.

So that's what I've been fixing for the past year. I'm doing an MCA (AI/ML) at Uttaranchal University, working as an ML Intern at SmartED Innovations, and using every side project as an excuse to deploy something properly: Docker, an actual API, experiment tracking, CI. Not another notebook that ends with "and then we could deploy this."

Right now I'm deep into production ML systems, computer vision for industrial use cases, predictive maintenance, and multi-agent LLM systems with LangGraph.

<br/>

### 🚀 Featured Projects

**🏭 [Industrial Defect Detection System](https://github.com/BhimAIEngineer/industrial-defect-detection)**
Catches defects on a manufacturing line as they happen, instead of after the batch has already shipped.
`YOLOv8` `FastAPI` `Docker` `MLflow` `GitHub Actions CI` `Streamlit dashboard`

**🏥 [Disease Prediction & Medical Diagnosis System](https://github.com/BhimAIEngineer/healthcare-triage-agent)**
Combines image-based and tabular models for diagnosis, with SHAP baked in so a doctor isn't just told "trust the model."
`ResNet50 (94% acc.)` `Custom ANN (+6% over baseline)` `SHAP` `FastAPI` `Docker` `MLflow` `CI/CD`

**✈️ [Turbofan Predictive Maintenance (Remaining Useful Life)](https://github.com/BhimAIEngineer/predictive-maintenance-rul)**
Predicts how much life is left in a turbofan engine using NASA's CMAPSS data, then runs the numbers on what that's actually worth compared to reactive maintenance.
`Feature Engineering` `Linear Regression / Random Forest / XGBoost` `LSTM` `FastAPI` `Streamlit` `Cost-Simulation`

**🤖 Multi-Agent Healthcare Triage Assistant** *(in progress)*
Splits triage work across cooperating agents instead of asking one giant prompt to do everything at once.
`LangGraph` `Agentic Workflows` `LLM Orchestration`

**📧 Spam Email Classifier**
Raw text in, deployable model out. 97.5% accuracy.
`Python` `NLTK` `Multinomial Naive Bayes` `Scikit-learn`

**🏠 House Price Predictor**
Regression on California housing data, wrapped in a Streamlit app so you can actually see which features are driving a prediction.
`Linear Regression` `Scikit-learn` `Streamlit`

> 📌 *None of these are just training scripts. Each one ships with an API, tracking, and a container around it.*

<br/>

### 🧰 Tech Toolbox

<table>
<tr>
<td valign="top" width="50%">

#### 📈 Data Science & Classical ML
![EDA](https://img.shields.io/badge/-EDA-6C5CE7?style=flat-square) ![A/B Testing](https://img.shields.io/badge/-A/B_Testing-6C5CE7?style=flat-square) ![XGBoost](https://img.shields.io/badge/-XGBoost-6C5CE7?style=flat-square&logo=xgboost&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-6C5CE7?style=flat-square) ![Random Forest](https://img.shields.io/badge/-Random_Forest-6C5CE7?style=flat-square) ![SVM](https://img.shields.io/badge/-SVM-6C5CE7?style=flat-square) ![Clustering](https://img.shields.io/badge/-Clustering-6C5CE7?style=flat-square) ![Pandas](https://img.shields.io/badge/-Pandas-6C5CE7?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-6C5CE7?style=flat-square&logo=numpy&logoColor=white)
- EDA & statistics: hypothesis testing, A/B testing, distribution analysis, outlier detection
- Feature engineering: encoding, scaling, imputation, dimensionality reduction, custom pipelines
- Classical ML: XGBoost, LightGBM, Random Forest, SVM, regression, clustering (k-means, hierarchical)
- Model evaluation: cross-validation, ROC-AUC, F1, RMSE, calibration curves, tied back to business metrics
- Tooling: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly
- Comfortable digging through messy structured and unstructured client data, handling missing values and outliers along the way

#### 🧠 Deep Learning
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![CNN](https://img.shields.io/badge/-CNNs-1E90FF?style=flat-square) ![LSTM](https://img.shields.io/badge/-RNN/LSTM-1E90FF?style=flat-square) ![Transformers](https://img.shields.io/badge/-Transformers-1E90FF?style=flat-square)
- CNNs and transfer learning: ResNet, EfficientNet, VGG
- Sequential modeling with RNNs and LSTMs for time-series work
- Transformers, attention mechanisms, encoder-decoder architectures, BERT
- Training practices: batch normalization, dropout, LR schedulers, early stopping, regularization
- Frameworks: PyTorch, TensorFlow, Keras
- Used deep sequential models for real forecasting problems, not just tutorial datasets

#### 💬 Natural Language Processing
![BERT](https://img.shields.io/badge/-BERT-FFD21E?style=flat-square) ![NER](https://img.shields.io/badge/-NER-FFD21E?style=flat-square) ![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![NLTK](https://img.shields.io/badge/-NLTK-FFD21E?style=flat-square)
- Text classification, sentiment analysis, named entity recognition
- Cleaning, tokenization, embeddings (Word2Vec, TF-IDF)
- Fine-tuning BERT for domain-specific tasks
- Semantic search and document Q&A, including RAG-style pipelines over unstructured text
- Built and shipped text classification pipelines for actual client use cases, not just Kaggle notebooks

#### 🗄️ SQL & Microsoft Office
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Excel](https://img.shields.io/badge/-Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) ![PowerPoint](https://img.shields.io/badge/-PowerPoint-B7472A?style=flat-square&logo=microsoftpowerpoint&logoColor=white) ![Word](https://img.shields.io/badge/-Word-2B579A?style=flat-square&logo=microsoftword&logoColor=white)
- SQL: joins, aggregations, window functions, pulling and shaping data straight out of relational databases
- Excel: pivot tables, formulas, cleanup, quick dashboards for business-facing analysis
- PowerPoint: project reports and stakeholder decks (used this a lot for MCA coursework and client presentations)
- Word: documentation, project reports, technical write-ups
- Turning model output into something a non-technical stakeholder can actually act on

</td>
<td valign="top" width="50%">

#### ⚙️ ML Engineering & MLOps
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Optuna](https://img.shields.io/badge/-Optuna-2088FF?style=flat-square)
- Model deployment: FastAPI, Flask, REST APIs, model serialization (Pickle, ONNX)
- Experiment tracking with MLflow: metrics, artifacts, model registry
- Docker for reproducible, portable environments
- CI/CD pipelines with GitHub Actions
- Hyperparameter tuning: GridSearchCV, RandomizedSearch, Optuna
- Modular pipelines, OOP design, reproducible notebooks, proper Git/GitHub hygiene
- Follow the same loop on every project: train, track, containerize, serve

#### 🤖 Generative AI & Agents
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square) ![FAISS](https://img.shields.io/badge/-FAISS-1C3C3C?style=flat-square) ![ChromaDB](https://img.shields.io/badge/-ChromaDB-1C3C3C?style=flat-square) ![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
- Prompt engineering, fine-tuning with LoRA/QLoRA, LLM API integration
- RAG systems: retrieval-augmented generation, semantic search, document Q&A
- Vector databases: FAISS, ChromaDB, embeddings
- AI agents: ReAct, tool-calling, LangChain/LangGraph agents, multi-agent orchestration
- Built multi-agent workflows for real triage and support use cases, not single-chain demos

#### 👁️ Computer Vision
![YOLOv8](https://img.shields.io/badge/-YOLOv8-00FFFF?style=flat-square) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![SHAP](https://img.shields.io/badge/-SHAP-5C3EE8?style=flat-square)
- Object detection (YOLOv8) and image classification
- Transfer learning on pretrained backbones for domain-specific vision tasks
- Model explainability with SHAP, for vision and tabular models alike
- Real-time inference pipelines, dashboarding in Streamlit
- Shipped a full industrial defect-detection pipeline, start to finish

#### ☁️ Cloud & Deployment
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
- AWS: S3, EC2, SageMaker basics
- Google Cloud Platform for ML workloads
- Azure ML for training and deployment
- Dockerized, cloud-ready model APIs; picking up CI/CD for ML along the way
- Working toward full cloud-native deployment: SageMaker end-to-end, managed pipelines

</td>
</tr>
</table>

<p align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,mysql,docker,git,github,aws,gcp,azure,fastapi,flask,linux,vscode&theme=dark" />
</p>

<br/>

### 💼 Experience

| Role | Company | Duration |
|---|---|---|
| **ML Intern** | SmartED Innovations (EdTech, remote) | Jun 2026 – Present |
| **Data Scientist** | TCS (Walmart Global Tech account) | 3.8 yrs (ended Jul 2025) |

<br/>

### 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=BhimAIEngineer&theme=tokyonight&hide_border=true" width="60%" />

</div>

<br/>

### 🎓 Currently

- Doing an MCA (AI/ML) at Uttaranchal University
- Building a new project for basically every role I apply to: CV, predictive maintenance, agents, whatever the job actually needs
- Open to **Data Scientist / Machine Learning Engineer** roles

<br/>

<div align="center">

📫 **Let's connect:** [LinkedIn](https://linkedin.com/in/bhimaiengineer) · [Kaggle](https://kaggle.com/bhimaiengineer) · [Email](mailto:bhimrajbhar.ai.engineer@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=BhimAIEngineer&label=Profile%20Views&color=00C9FF&style=flat)

</div>
