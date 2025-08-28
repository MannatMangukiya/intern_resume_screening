# intern_resume_screening

This project is an AI-powered Resume Screening App that helps recruiters parse resumes, extract key information, and rank candidates against job descriptions using Natural Language Processing (NLP) and Machine Learning (ML).

The system automates the recruitment workflow by reducing manual effort and providing data-driven candidate shortlisting.

## Day 1 – Project Initialization

Commit: chore: initialize project structure & setup virtual environment

Details: Created the base folder structure for the project (src/, data/, ui/, notebooks/). Set up a Python virtual environment and installed initial dependencies (Flask, Streamlit, Pandas, NumPy).

## Day 2 – Documentation Setup

Commit: docs: add project README and .gitignore

Details: Wrote the initial README with project goals and tech stack. Added .gitignore to exclude unnecessary files such as virtual environment folders, cache, and dataset files.

## Day 3 – Sample Data

Commit: data: add sample resumes and job descriptions

Details: Collected a few sample resumes in PDF/DOCX format and job descriptions in text format to test the system. Placed them inside the data/ directory.

## Day 4 – Resume Parser (PDF)

Commit: feat: implement basic resume parser for PDF

Details: Built the first version of the PDF resume parser using pdfminer.six to extract text content from resumes.

## Day 5 – Resume Parser (DOCX)

Commit: feat: implement DOCX parser

Details: Added support for parsing resumes in .docx format using python-docx. Ensured that extracted text is clean and structured for further processing.

## Day 6 – Error Handling in Parsing

Commit: fix: handle parsing errors for non-standard resume formats

Details: Implemented error handling for corrupt or incorrectly formatted resumes. Added logging for debugging problematic files.

## Day 7 – Candidate Information Extraction

Commit: feat: extract candidate details (name, skills, experience)

Details: Wrote NLP scripts using spaCy to extract key information like name, email, phone number, skills, and work experience.

## Day 8 – Job Description Processing

Commit: feat: clean & normalize job descriptions

Details: Preprocessed job descriptions by removing stopwords, lowercasing, and lemmatization. Normalized text to make it suitable for NLP models.

## Day 9 – Structured Resume Data

Commit: data: store structured resume data in JSON/DB

Details: Designed a schema for storing candidate details. Stored parsed and extracted information into JSON format and integrated with MongoDB for structured storage.

## Day 10 – Exploratory Data Analysis

Commit: chore: add initial EDA notebook

Details: Created a Jupyter notebook for exploratory data analysis. Imported sample data and began analyzing text length, word counts, and skill frequency.

## Day 11 – Data Visualization

Commit: feat: visualize top skills and experience distribution

Details: Used Matplotlib/Seaborn to visualize the most common skills, years of experience, and frequency of keywords in resumes vs. job descriptions.

## Day 12 – Text Preprocessing

Commit: feat: implement text preprocessing (tokenization, lemmatization)

Details: Implemented tokenization and lemmatization using spaCy. Ensured resume and job texts are transformed into clean tokens for modeling.
