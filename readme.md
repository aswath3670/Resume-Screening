# Resume Screening System using NLP (TF-IDF & Cosine Similarity)

## Project Overview
This project implements a Resume Screening System using Natural Language Processing (NLP).
It compares multiple resumes against a job description and ranks them based on relevance.

The system uses **TF-IDF Vectorization** and **Cosine Similarity** to calculate matching scores.

---

## Technologies Used
- Python
- NLP (TF-IDF)
- Scikit-learn
- Pandas
- NLTK
- PyPDF2
- Jupyter Notebook

---

##  Project Structure
Resume_Screening_NLP/
│
├── resumes/                    # Folder containing PDF resumes
│   ├── ASWATH_V_Data_Analyst.pdf
│   ├── ASWATH_V_AI_ML.pdf
│
├── job_description.txt         # Job description text file
├── Resume_Screening.ipynb      # Main Jupyter Notebook with preprocessing, TF-IDF, and scoring
├── requirements.txt            # Python dependencies for the project
├── README.md                   # Project documentation and instructions
└── .gitignore                  # Files and folders to ignore in Git

