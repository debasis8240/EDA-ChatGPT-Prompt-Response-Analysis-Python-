# EDA-ChatGPT-Prompt-Response-Analysis-Python-

## 📌 Project Overview
A complete Exploratory Data Analysis (EDA) project on ChatGPT prompts and responses using Python. This project focuses on analyzing user prompt behavior, prompt categories, response readability, verbosity, and the impact of additional context on ChatGPT-generated responses using NLP and visualization techniques.
The analysis includes:

 - Data Cleaning
 - Text Preprocessing
 - Prompt Categorization
 - Readability Analysis
 - Response Complexity Analysis
 - Word Cloud Visualization
 - Statistical & Correlation Analysis

---

## 🚀 Project Objectives
This project analyzes ChatGPT prompts and responses to uncover valuable insights such as:
 - Most common prompt types used in ChatGPT
 - Frequently used words in prompts
 - Readability level of ChatGPT responses
 - Relationship between prompt length and response readability
 - Verbosity of ChatGPT responses
 - Impact of additional context on generated responses
 - Distribution of prompt categories

---


## 🛠️ Technologies Used
 - Python(Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook, SQL Server

---

## 📂 Dataset Information
The dataset used in this project:
 - Alpaca GPT-4 Dataset
 - Loaded using Hugging Face datasets library
 - Dataset Features
   
Contains:
 - instruction
 - input
 - output

 ---

 
## 📊 Steps and Workflow
🔹 1. Data Collection
 - a.Loaded dataset using Hugging Face datasets library. b. Converted dataset into Pandas DataFrame, c. Explored dataset structure and records
🔹 2. Data Understanding
 - a. Performed initial dataset exploration. b. Checked dataset shape and columns. c. Analyzed prompt and response structure.  d. Explored missing values. e.         Generated descriptive statistics
🔹 3. Data Cleaning & Preprocessing
 - a. Removed unwanted characters using Regex. b. Converted text to lowercase. c. Removed stopwords using NLTK. d. Cleaned prompt text for NLP analysis
🔹 4. Word Cloud Analysis
 - a. Generated Word Clouds to identify. b. Most frequently used prompt words. c. Common user query patterns. d.High-frequency keywords
🔹 5. Prompt Type Analysis
 - a.Categorized prompts into multiple categories such as. b.Information Retrieval. c. Summarization. d. Coding. e. Translation. f. Creative Writing
   g. Question Answering. h. Analyzed the distribution of different prompt types used by users.
🔹 6. Readability Analysis

Used TextStat to calculate:

Flesch Reading Ease Score
Readability levels of ChatGPT responses

Classified responses into:

Very Easy
Easy
Medium
Difficult
🔹 7. Prompt Length vs Response Complexity

Analyzed:

Relationship between prompt length and readability score
Correlation between prompt size and response complexity
Impact of detailed prompts on generated responses

Performed:

Correlation analysis
Regression analysis
Scatter plot visualization
🔹 8. Response Verbosity Analysis

Measured:

Sentence count
Word count
Words per sentence

Analyzed how verbose ChatGPT responses are across different prompt types.

🔹 9. Context-Based Analysis

Analyzed whether additional context improves ChatGPT responses by comparing:

Response readability
Output length
Average response quality

Compared:

Prompts with extra context
Prompts without extra context
🔹 10. Data Visualization

Created visualizations including:

Word Clouds
Bar Charts
Pie Charts
Scatter Plots
Boxplots
Regression Plots
Correlation Analysis Charts
📈 Key Findings and Insights
🧠 Prompt Analysis
Information retrieval and question-answering prompts were among the most common prompt types.
Users frequently asked explanatory and descriptive questions.
☁️ Word Cloud Insights
Common prompt keywords included:
explain
summarize
write
create
define

These keywords reflected strong interest in content generation and learning tasks.

📖 Readability Insights
Most ChatGPT responses fell into the Easy and Medium readability categories.
Responses were generally designed to be understandable and user-friendly.
📏 Prompt Length Insights
Longer prompts often generated more detailed responses.
Weak correlation observed between prompt length and readability complexity.
📝 Response Verbosity
ChatGPT responses contained varying sentence lengths depending on prompt type.
Detailed prompts generally produced more verbose outputs.
