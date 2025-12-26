# AI and ML Internship Tasks – DevelopersHub Corporation

This repository contains my work completed during the **AI/ML Engineering Internship** at **DevelopersHub Corporation**.  
The internship is structured in weekly phases, progressing from classical machine learning and data analysis to advanced AI and LLM based applications.

---

## Internship Progress Overview

- **Week 1:** Foundations of Machine Learning and Data Analysis  
- **Week 2:** Advanced AI, Transformers, and LLM Applications  

---

## Week 1 Tasks – Machine Learning Foundations

### Task 1 – Iris Dataset Exploration
**Key Work Completed:**
- Loaded and inspected the Iris dataset using Pandas and Seaborn
- Performed descriptive analysis using `.info()` and `.describe()`
- Visualized feature relationships using scatter plots, pairplots, histograms, and boxplots
- Analyzed species distributions and feature correlations

**Notebook:** `Task1_Iris_Visualization.ipynb`

---

### Task 3 – Heart Disease Prediction
**Key Work Completed:**
- Cleaned dataset and handled missing values
- Conducted Exploratory Data Analysis including correlation analysis
- Trained Logistic Regression and Decision Tree models
- Evaluated models using accuracy, confusion matrix, ROC curve, and ROC AUC score
- Identified key features influencing heart disease prediction

**Notebook:** `Task3_Heart_Disease.ipynb`

---

### Task 6 – House Price Prediction
**Key Work Completed:**
- Loaded dataset using KaggleHub
- Applied preprocessing including one hot encoding, feature scaling, and target transformation
- Trained Linear Regression, Random Forest, and Gradient Boosting models
- Performed hyperparameter tuning using GridSearchCV
- Evaluated models using MAE, RMSE, and R² metrics
- Visualized actual vs predicted prices
- Exported the best performing model as `gbr_model.joblib`

**Notebook:** `Task6_House_Price.ipynb`

---

## Week 2 Tasks – Advanced AI and LLM Applications

### Task 1 – News Topic Classifier Using BERT
**Key Work Completed:**
- Fine tuned a pre trained BERT transformer on the AG News dataset
- Performed tokenization and preprocessing using Hugging Face Transformers
- Evaluated the model using Accuracy and Weighted F1 Score
- Deployed the trained model using Streamlit for live headline classification
  ## Screenshot

Screenshots demonstrating model outputs and Streamlit applications for NEWS_CLASSIFIER_USING_BERT.ipynb
<img width="1915" height="806" alt="image" src="https://github.com/user-attachments/assets/fbd2f4a2-93cd-4530-8944-97f3e0fdf1da" />

**Technologies:** BERT, Hugging Face Transformers, PyTorch, Streamlit

---

### Task 4 – Context Aware Chatbot Using RAG
**Key Work Completed:**
- Implemented Retrieval Augmented Generation using LangChain
- Created document embeddings and stored them in a FAISS vector database
- Enabled conversational memory for context retention
- Built a Streamlit based chatbot interface for real time interaction

**Technologies:** LangChain, FAISS, Hugging Face, Streamlit

---

### Task 5 – Auto Tagging Support Tickets Using LLM
**Key Work Completed:**
- Implemented LLM based ticket classification using prompt engineering
- Compared zero shot and few shot learning approaches
- Generated top 3 most probable tags per support ticket
- Analyzed performance differences between prompting strategies

**Technologies:** LLMs, Prompt Engineering, Few Shot Learning

---


