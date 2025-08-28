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

## Day 13 – TF-IDF Vectors

Commit: feat: convert resumes & jobs to TF-IDF vectors

Details: Implemented TF-IDF vectorization for resume and job descriptions using Scikit-learn. Stored vectors for similarity computation.

## Day 14 – Similarity Scoring

Commit: feat: add cosine similarity scoring

Details: Wrote a function to calculate cosine similarity between resumes and job descriptions. Tested ranking results on sample resumes.

## Day 15 – Logistic Regression Baseline

Commit: feat: implement baseline Logistic Regression model

Details: Built a baseline Logistic Regression classifier to classify resumes based on job fit. Evaluated accuracy and precision.

## Day 16 – SVM Model

Commit: feat: train SVM model for ranking resumes

Details: Implemented Support Vector Machine (SVM) model for candidate ranking. Compared results with Logistic Regression.

## Day 17 – BERT Embeddings

Commit: feat: integrate BERT embeddings for semantic similarity

Details: Used Transformers (BERT) to generate embeddings for resumes and job descriptions. Improved semantic understanding compared to TF-IDF.

## Day 18 – Model Evaluation

Commit: test: evaluate models with Precision/Recall/F1

Details: Evaluated Logistic Regression, SVM, and BERT models using Precision, Recall, and F1-score. Documented results in a notebook.

## Day 19 – Candidate Ranking

Commit: feat: build candidate ranking function

Details: Developed ranking logic to order resumes based on similarity score and classifier predictions. Ensured top candidates are listed first.

## Day 20 – Model Comparison Documentation

Commit: docs: update EDA results and model comparison

Details: Documented the EDA insights and compared baseline vs advanced models (Logistic Regression, SVM, BERT). Updated README with results.

## Day 21 – Streamlit UI Skeleton

Commit: feat: create Streamlit UI skeleton

Details: Set up a simple Streamlit app structure with sidebar and placeholder sections for resume upload and results.

## Day 22 – File Upload Feature

Commit: feat: add file upload (resume/job description) in UI

Details: Implemented file upload functionality in Streamlit to allow users to upload resumes (PDF/DOCX) and job descriptions.

## Day 23 – Display Extracted Details

Commit: feat: display extracted resume details in UI

Details: Connected backend parser with the Streamlit UI. Displayed candidate information (Name, Skills, Experience) after upload.

## Day 24 – Similarity Score in UI

Commit: feat: show candidate-job similarity score in UI

Details: Displayed the calculated similarity score between uploaded resume and job description directly in the Streamlit interface.

## Day 25 – Candidate Ranking Dashboard

Commit: feat: implement candidate ranking dashboard

Details: Built a dashboard to rank multiple resumes against a single job description. Displayed results in a table with scores.

## Day 26 – Database Integration

Commit: chore: add MongoDB integration for storing resumes

Details: Integrated MongoDB to persist parsed resumes, job descriptions, and ranking results for long-term usage.

## Day 27 – Deployment (Streamlit Cloud)

Commit: feat: deploy app on Streamlit Cloud

Details: Deployed the application to Streamlit Cloud for demo purposes. Shared live demo link with stakeholders.

## Day 28 – Deployment Documentation

Commit: docs: add deployment instructions to README

Details: Updated README with detailed instructions on how to run the app locally and on cloud platforms like Streamlit/Heroku.

## Day 29 – Code Refactoring

Commit: refactor: optimize preprocessing & model pipeline

Details: Refactored preprocessing scripts and model pipeline for better efficiency. Reduced redundancy and improved modularity.

## Day 30 – UI Fixes

Commit: fix: resolve UI alignment issues

Details: Fixed alignment issues in the Streamlit UI. Improved table formatting and readability of ranking results.

## Day 31 – Final Documentation

Commit: docs: add final internship report summary

Details: Added the final project summary and key learnings from the internship to the README. Prepared documentation for submission.
