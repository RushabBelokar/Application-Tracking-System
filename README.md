# Application-Tracking-System
A resume screening application that analyzes resumes against job descriptions, provides match scores, highlights strengths and gaps, and offers actionable suggestions along with pros, cons, and recommended changes to improve resume quality and ATS compatibility

Features
Upload PDF Resume: Users can upload their resume in PDF format.
Input Job Description: Users can input the job description in a text area.
Tell Me About the Resume: Provides an evaluation of the candidate's profile against the job description, highlighting strengths and weaknesses.
Get Keywords: Identifies specific skills and keywords necessary for the resume to have maximum impact, provided in JSON format.
Percentage Match: Evaluates the percentage match of the resume with the job description, along with keywords missing and final thoughts.

Installation
Clone the repository:

git clone 

Install the required dependencies:
pip install -r requirements.txt
Run the Streamlit app:

streamlit run app.py
Usage
Open the Streamlit app in your browser. Input the job description in the text area provided. Upload the PDF resume using the "Upload your resume(PDF)..." button. Click on the desired action buttons to perform various analyses.

Technologies Used
AWS EC2 Instance 
Python
Streamlit
pdf2image (Poopler)
Google Gemini API
