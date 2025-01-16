# ATS Project with Google Gemini API

# Project Overview:
This project is an Application Tracking System (ATS) built using Google’s Generative AI model API, currently updated to use the Gemini 1.5 Flash model. The application provides end-to-end functionality to analyze resumes, compare them with job descriptions, and suggest improvements based on missing keywords and relevance.

# Objectives

1) Provide a simple tool to help analyze resumes.
2) Help users compare their resumes against job descriptions.
3) Offer actionable suggestions for improving resumes based on job requirements.

# Features
1) Resume Upload: Users can upload their resume in PDF format.
2) Job Description Input: A text input field allows users to paste the job description they are targeting.
3) AI-Powered Analysis: Utilizing Gemini AI, the application provides a detailed analysis of the resume in context with the job description.
4) Feedback on different aspect:
   - Resume Analysis: Extracts technical skills, soft skills, educational qualifications, and experience from the uploaded resume.
   - Keyword Analysis: Compares the job description with the resume, Identifies missing keywords and skills, Suggests ways to incorporate relevant keywords for a better match.
   - Job Match Evaluation: Generates a detailed table showcasing strengths, weaknesses, and match levels (high, medium, low) for each category.
  
# Technology Stack

- Programming Language: Python
- Web Framework: Streamlit
- Generative AI API: Google Gemini 1.5 Flash
- File Processing: pdf2image, Pillow
- Environment Variables: python-dotenv

# Usage
1) Open the application in your browser.
2) Enter a Job Description in the text area.
3) Upload your resume in PDF format.
4) Use the following buttons to perform specific actions:
  - Tell Me About the Resume: Get an evaluation of your resume based on the job description.
  - Keywords Missing in My Resume: Identify missing keywords and receive improvement suggestions.
  - Match with Job Description: View a detailed match analysis.

# Future Enhancements
- Support for multiple-page PDFs for more detailed resume analysis.
- Integration with LinkedIn for importing job descriptions and resumes.
- Improved visualizations for match evaluation.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any suggestions or improvements.
linkedin: https://www.linkedin.com/in/winifred-igbokwe-754136245
