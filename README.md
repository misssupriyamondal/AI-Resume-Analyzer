# AI Resume Analyzer

An AI-powered Resume Analysis and ATS Optimization application developed using Python, Streamlit, Groq API, and Llama 3.3.

The application analyzes resumes to estimate ATS compatibility, identify relevant technical skills and keywords, detect key resume sections, and provide AI-generated recommendations for improvement.

## Live Demo

https://ai-resume-analyzer-by-supriya.streamlit.app/

## Project Overview

The AI Resume Analyzer is designed to help students, graduates, and job seekers evaluate and improve their resumes before submitting applications.

The system combines AI-powered analysis, rule-based text processing, and Large Language Model (LLM) capabilities to extract meaningful information from resumes and generate actionable feedback.

This project demonstrates the practical application of Artificial Intelligence, Natural Language Processing, text analysis, API integration, and web application development to a real-world career development problem.

## Key Features

- PDF Resume Upload
- AI-Powered Resume Analysis
- ATS Compatibility Estimation
- Resume Keyword Analysis
- Technical Skills Detection
- Experience Detection
- Education Detection
- Resume Completeness Analysis
- Resume Statistics
- AI-Generated Improvement Recommendations
- Downloadable Analysis Report

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Core programming language and application development |
| Streamlit | Interactive web application framework |
| Groq API | High-performance AI inference |
| Llama 3.3 | Large Language Model for resume analysis |
| PyPDF2 | PDF text extraction |
| Regular Expressions (Regex) | Pattern matching and structured information detection |

## System Workflow

Resume (PDF)
        ↓
PDF Text Extraction
        ↓
Text Preprocessing
        ↓
Rule-Based Analysis + AI Analysis
        ↓
Resume Evaluation
        ↓
ATS Score + Keyword Analysis + Skills Detection
        ↓
Experience & Education Detection
        ↓
Resume Completeness Analysis
        ↓
AI-Generated Recommendations
        ↓
Downloadable Analysis Report

## Methodology

The application follows a multi-stage resume analysis process.

### 1. Resume Upload

The user uploads a resume in PDF format through the Streamlit interface.

### 2. Text Extraction

Resume content is extracted from the uploaded PDF using PyPDF2.

### 3. Text Processing

The extracted text is processed to identify important patterns, keywords, sections, and resume-related information.

### 4. Structured Analysis

Rule-based techniques and Regular Expressions (Regex) are used to detect information such as:

- Technical skills
- Education
- Experience
- Keywords
- Resume sections
- Resume statistics

### 5. AI Analysis

The processed resume content is analyzed using Llama 3.3 through the Groq API.

### 6. ATS Evaluation

The system estimates ATS compatibility based on resume structure, content, and keyword relevance.

### 7. Recommendation Generation

The AI generates suggestions to improve the resume's content, structure, skills presentation, and keyword relevance.

### 8. Report Generation

The analysis results can be downloaded as a report for further review.

## Academic & Technical Relevance

This project demonstrates practical implementation of:

- Artificial Intelligence
- Large Language Models (LLMs)
- Natural Language Processing
- Text Processing
- Pattern Recognition
- Prompt-Based AI Analysis
- API Integration
- Python Programming
- Web Application Development
- Data Extraction
- Resume and Career Technology

The project demonstrates the integration of an AI model into a practical, user-oriented software application.

## Project Objectives

The primary objectives of this project are to:

1. Develop an AI-assisted resume evaluation system.
2. Analyze resume content using both rule-based and AI-based approaches.
3. Estimate ATS compatibility of resumes.
4. Identify relevant skills and keywords.
5. Detect important resume sections such as education and experience.
6. Provide actionable recommendations for resume improvement.
7. Demonstrate practical integration of Large Language Models into a web application.

## Installation & Local Setup

### 1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Configure the Groq API Key

Create a .env file in the project directory and add your API key:

GROQ_API_KEY=your_groq_api_key

Never upload your API key, .env file, or other sensitive credentials to GitHub.

### 4. Run the Application

streamlit run app.py

The application will then be available through the local Streamlit URL displayed in the terminal.

## Project Structure

AI-Resume-Analyzer/
│
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
├── .gitignore
│
└── assets/
    └── screenshots/

## Use Cases

The application can be useful for:

- Students preparing resumes
- University graduates
- Internship applicants
- Job seekers
- Software developers
- Fresh graduates
- Professionals preparing for job applications
- Candidates seeking ATS-friendly resume improvements

## Future Scope

The project can be further enhanced with:

- Job Description vs. Resume Matching
- Advanced ATS Scoring
- Job-Specific Keyword Recommendations
- Automated Resume Section Improvement
- Personalized Resume Rewriting
- Multiple Resume Format Support
- Resume Comparison
- Multilingual Resume Analysis
- Job Recommendation System
- LinkedIn Profile Analysis
- Industry-Specific Resume Evaluation

## Limitations

The ATS score provided by the application is an estimated evaluation and should not be considered an official score from any specific Applicant Tracking System.

Different organizations may use different ATS platforms, configurations, ranking methods, and recruitment criteria. Therefore, the analysis should be used as a guidance tool for improving resume quality rather than as a guaranteed measure of recruitment success.

## Application Preview

The application provides an interactive interface for uploading a resume and reviewing AI-powered analysis, ATS compatibility, keyword insights, detected skills, and improvement recommendations.

## Live Application

AI Resume Analyzer:

https://ai-resume-analyzer-by-supriya.streamlit.app/

## Author

Ayan

Independent AI and Software Development Project

## Acknowledgements

This project was developed using open-source technologies and AI tools, including:

- Python
- Streamlit
- Groq API
- Llama 3.3
- PyPDF2

## Project Highlights

Artificial Intelligence • Large Language Models • Natural Language Processing • ATS Analysis • Resume Optimization • Python • Streamlit • Groq API • Llama 3.3

## License

This project is licensed under the MIT License.

See the LICENSE file for more information.
