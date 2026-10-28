# AI Resume Analyzer

## About the Project
AI Resume Analyzer is a beginner-friendly Generative AI project
that analyzes a resume against a job description.

It identifies matching skills, highlights skills to improve,
calculates an estimated skill-match percentage, and can generate
AI-based feedback using a locally running Ollama language model.

## Features
- Upload and read a PDF resume
- Extract resume text using PyPDF
- Identify skills from the resume and job description
- Calculate an estimated skill-match percentage
- Highlight missing or relevant skills
- Generate AI feedback using Ollama
- Save an analysis report as a text file

## Technologies Used
- Python
- Jupyter Notebook
- PyPDF
- Requests
- Ollama and Llama 3.2 1B (for local AI feedback)

## Requirements
- Python
- Jupyter Notebook
- Required Python packages
- Ollama with the selected model downloaded for AI feedback

## Installation
Install the required packages:

    python -m pip install -r requirements.txt

Install Ollama from https://ollama.com/ and download the model:

    ollama run llama3.2:1b

## How to Run
1. Open AI_Resume_Analyzer.ipynb in Jupyter Notebook.
2. Run the notebook cells in order.
3. Select a PDF resume.
4. Enter or edit the job description.
5. Review the skill-match score and missing skills.
6. Generate AI feedback if Ollama is running.
7. Save the analysis report.

## Privacy
Use a sample or your own resume carefully. This project processes
resume information locally when using the local Ollama model.
Do not upload personal resumes or generated reports to GitHub.

## Disclaimer
The skill-match percentage is an estimate based on keyword matching.
It is not a hiring decision or a guarantee of job suitability.

## Author
Aiswarya
