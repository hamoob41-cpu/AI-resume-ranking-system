# AI Resume Ranking System Using NLP

## 📌 Project Overview
The AI Resume Ranking System is an intelligent application that automatically evaluates and ranks resumes based on their relevance to a given job description. The system uses Natural Language Processing (NLP) techniques to objectively compare resumes submitted in different file formats.

This project simulates a basic Applicant Tracking System (ATS) used in real-world recruitment.

---

## 🎯 Problem Statement
Manual resume screening is time-consuming, inefficient, and often subjective. Recruiters struggle to compare resumes fairly, especially when candidates submit resumes in different formats.

This project solves the problem by automating resume analysis and ranking using AI-based text similarity methods.

---

## ✨ Features
- Supports multiple resume formats (CSV and DOCX)
- Handles multiple resumes at once
- Automatically ranks candidates based on job relevance
- Simple and scalable design

---

## 🛠️ Technologies Used
- Programming Language: Python
- Platform: Google Colab
- Libraries:
  - Pandas
  - Scikit-learn
  - python-docx
  - re (Regular Expressions)

---

## ⚙️ How the System Works
1. Upload resumes in CSV or Word (DOCX) format  
2. Extract and clean text from resumes  
3. Extract relevant skills  
4. Convert text into numerical vectors using TF-IDF  
5. Measure similarity with the job description using cosine similarity  
6. Rank candidates based on match percentage  

---

## ▶️ How to Run the Project
1. Open the project in Google Colab or VS Code
2. Install required libraries:
   pip install pandas scikit-learn python-docx
3. Upload resume files (CSV and/or DOCX)
4. Run the Python script or notebook
5. View ranked results in tabular format

---

## 📊 Output
The system outputs a ranked list containing:
- Resume file name
- Match percentage
- Rank

---

## 🚧 Limitations
- Skill extraction is keyword-based
- Does not perform deep semantic understanding
- Accuracy depends on resume content quality

---

## 🔮 Future Enhancements
- Add PDF resume support
- Use advanced NLP models (BERT)
- Develop a web-based interface

---

## 👨‍🎓 Academic Declaration
This project is developed for academic purposes as part of an AI/ML subject.
