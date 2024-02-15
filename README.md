# AI Skills Harvest

Welcome to AI Skills Harvest! This project aims to develop a supervised scoring model based on BERT for skill analysis from resumes in PDF format. Additionally, it involves setting up a Flask API to call the prediction model and creating an interactive dashboard using Streamlit for client relationship managers.

## Project Structure
AI-SkillHarvest/
│
├── data/
│ ├── raw_data/ # Raw project data
│ └── processed_data/ # Processed data
│
├── models/
│ ├── bert_skills_matching_model.pkl # Saved BERT model
│ └── ... # Other models (if necessary)
│
├── notebooks/
│ ├── pdf_parser.ipynb # Notebook for PDF parsing with BERT
│ └── ... # Other notebooks (if necessary)
│
├── src/
│ ├── app.py # Main file for Flask API
│ └── dashboard.py # Main file for Streamlit dashboard
│
├── requirements.txt # Python dependencies file
├── Procfile # File for Heroku deployment
├── README.md # Main project documentation
└── ...
