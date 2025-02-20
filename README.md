# AI-Powered-Resume-Classifier-Automated-Resume-Categorization
An automated system that extracts, cleans, and categorizes resumes using NLP and Machine Learning. It processes PDFs, predicts job categories, organizes resumes into folders, and logs results in a CSV file—streamlining resume screening for recruiters!

## 📌 Project Overview
This project automates the process of categorizing resumes using Natural Language Processing (NLP) and Machine Learning (ML). It extracts text from resume PDFs, cleans and preprocesses the text, and classifies resumes into predefined job categories using a trained ML model. Once categorized, resumes are automatically moved into respective folders, and a CSV report is generated for easy tracking. The project leverages PyPDF2 for text extraction, NLTK for preprocessing, and Scikit-learn for classification. It streamlines the hiring process by organizing resumes efficiently, making it an essential tool for recruiters and HR professionals. 

## 📂 Dataset
- **Source**: [GitHub - Sbhawal/resumeScraper](https://github.com/Sbhawal/resumeScraper)
- **Description**: The dataset contains resumes from different professional fields, including Advocate, Information Technology, and more.
- **Key Features**:
  - `ResumeID`: Unique identifier for each resume
  - `Category`: Field of profession (e.g., Advocate, IT, HR, etc.)
  - `ResumeText`: Raw textual data of resumes
  - `Skills`: Extracted skills from resumes
  - `Experience`: Years of experience mentioned in resumes

## 🛠️ Tech Stack
Your AI-Powered Resume Classifier project utilizes a combination of data science, machine learning, and software development technologies:

- **Programming Language**: Python – Core language for data processing, model training, and automation.
- **Libraries & Frameworks**:
  - **Machine Learning & NLP**:
    - `scikit-learn` – Used for training the classification model.
    - `nltk` – Natural Language Processing for tokenization, stopword removal, and text preprocessing.
    - `pandas` – Data manipulation and processing.
    - `numpy` – Numerical operations and array handling.
  - **PDF Processing & File Handling**:
    - `PyPDF2` – Extracting text from PDF resumes.
    - `os` & `shutil` – File system operations to categorize and move resumes.
  - **Version Control & Deployment**:
    - `Git & GitHub` – Managing the project repository and collaboration.

## 🚀 Installation & Setup
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   https://github.com/Codewtithdips/AI-Powered-Resume-Classifier-Automated-Resume-Categorization.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-Powered-Resume-Classifier-Automated-Resume-Categorization
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Add Resumes for Categorization:
   - Place all your resumes in the `raw_resumes` folder inside the project directory.
   - Ensure resumes are in PDF format for proper text extraction.
   - The classifier will categorize the resumes based on job descriptions.
     
5. Run the Python script:
   ```bash
   python script.py
   ```

## 📊 Exploratory Data Analysis (EDA)
- Data Cleaning & Handling Missing Values
- Feature Engineering & Encoding Categorical Variables
- Data Visualization (Histograms, Correlation Heatmaps, Boxplots)

## 🤖 Model Building & Evaluation
- Train-Test Split
- Model Selection & Hyperparameter Tuning
- Performance Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC Curve

## 📌 Results & Findings
- Best performing model: **(mention model name with highest accuracy or best metric)**
- Key insights from feature importance
- Business recommendations based on results

## 📁 Directory Structure
```
📂 customer-churn-prediction
│-- 📄 README.md
│-- 📂 data (Dataset files)
│-- 📂 notebooks (Jupyter notebooks)
│-- 📂 src (Python scripts for preprocessing & modeling)
│-- 📂 models (Saved trained models)
│-- 📄 requirements.txt
│-- 📄 churn_prediction.py
```



## 📞 Contact
- **GitHub**: [Your GitHub Profile](https://github.com/your-username)
- **LinkedIn**: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile)
- **Email**: your-email@example.com
