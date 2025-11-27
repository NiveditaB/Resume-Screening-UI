##Resume Screening Application | HuggingFace UI

A smart Resume Screening Web Application that uses TF-IDF, Regex-based NLP, and a lightweight LLM-based summarization pipeline to analyze resumes, extract skills, and compute the match score between a candidate and job description.
The project includes a fully interactive HuggingFace Spaces UI for seamless resume screening.

🌐 Live Demo (HuggingFace Space)

🔗 https://huggingface.co/spaces/Nivedita01/Resume-screening-ui

🚀 Project Overview

This project automates the initial HR resume screening process using NLP and machine learning techniques.
It accepts a resume PDF as input, extracts the content, identifies important skills, compares the resume with a job description, and generates a structured analysis for recruiters.

This project was developed as part of an IEEE Internship.

🛠 Tech Stack
Languages & Frameworks
-Python
-Gradio (UI Framework)
-HuggingFace Transformers

NLP Techniques
-TF-IDF Vectorization
-Cosine Similarity Matching
-Regex-based Skill Extraction
-Stop Words Removal
-Text Normalization & Pre-processing

Libraries Used
-NumPy
-Pandas
-Scikit-learn
-PyPDF2 / PDFMiner
-Re (Regex)

🔍 Features
✔ 1. Resume Text Extraction
-Converts PDF resumes to clean text
-Applies preprocessing: lowercasing, stop-word removal, token cleaning

✔ 2. TF-IDF Based Similarity Matching
-Converts Job Description & Resume into numerical vectors
-Computes Cosine Similarity (%)
-Generates a Job Fit Score

✔ 3. Skill Extraction (Regex + Custom Keyword Lists)
-Detects required skills
-Highlights missing skills
-Displays additional skills

✔ 4. LLM-Based Candidate Summary
-Uses a lightweight HuggingFace model to summarize:
-Candidate profile
-Strengths
-Overall suitability

✔ 5. Interactive UI on HuggingFace Spaces
-Upload resume
-Enter job description
-View all results: match score, skills, summary

📂 Project Structure
/Resume-Screening-UI
│
├── app.py                # Main Gradio Application
├── model.py              # TF-IDF, Regex, Similarity Functions
├── utils.py              # Helper Methods
├── skills.json           # Skills Dataset
├── sample_resumes/       # Example resumes for testing
├── requirements.txt      # Required dependencies
└── README.md             # Project Documentation

▶️ How to Run Locally
pip install -r requirements.txt
python app.py

📘 Internship Contribution (IEEE)

This project was developed as part of my IEEE Internship, where I worked as the Team Leader for the Resume Screening AI module. My leadership and technical contributions included:

👩‍💼Leadership Responsibilities
-Led a team working on resume screening automation
-Assigned tasks, reviewed code, and coordinated weekly progress
-Managed deployment and final presentation of the project
-Ensured timely completion and integration of all components

🧑‍💻 Technical Contributions
-Designed the complete front-end UI on HuggingFace Spaces
-Implemented PDF resume text extraction pipeline
-Developed the TF-IDF + Cosine Similarity model for match scoring
-Created Regex-based skill extraction system
-Integrated lightweight LLM for candidate summary generation
-Handled testing, optimization, and deployment

📊 Output Includes
-Job Match Score (%)
-Required vs Present vs Missing Skills
-Extracted Keywords
-Candidate Summary
-Clean, readable UI

🧑‍💻 Author

Nivedita Balunavar
GitHub: https://github.com/NiveditaB

HuggingFace: https://huggingface.co/Nivedita01
