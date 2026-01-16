# Application Tracking System (ATS Resume Analyzer)

A resume screening application that analyzes resumes against job descriptions to determine relevance, ATS compatibility, and improvement areas. The system generates match scores, highlights strengths and gaps, extracts critical keywords, and provides actionable recommendations to improve resume quality.

---

## Features

* **Upload PDF Resume**
  Upload candidate resumes in PDF format for analysis.

* **Input Job Description**
  Paste the target job description into the application for comparison.

* **Resume Evaluation**
  Analyzes the resume against the job description and highlights strengths, weaknesses, and alignment issues.

* **Keyword Extraction**
  Identifies important skills and keywords required for maximum ATS impact. Output is provided in JSON format.

* **Percentage Match**
  Calculates an overall match percentage between the resume and job description, lists missing keywords, and provides final recommendations.

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/RushabBelokar/Application-Tracking-System.git
cd Application-Tracking-System
```

### 2. Install Dependencies

Ensure Python 3.8+ is installed, then run:

```bash
pip install -r requirements.txt
```

> **Note:** `pdf2image` requires Poppler to be installed on your system.
>
> * **Ubuntu/Debian:** `sudo apt install poppler-utils`
> * **Windows:** Download Poppler and add it to the system PATH

### 3. Run the Application

```bash
streamlit run app.py
```

---

## Usage

1. Launch the Streamlit application in your browser.
2. Paste the job description into the provided text area.
3. Upload the resume using the **Upload your resume (PDF)** option.
4. Click the required action buttons to:

   * Evaluate the resume
   * Extract keywords
   * View percentage match and improvement suggestions

---

## Technologies Used

* **AWS EC2** – Application hosting
* **Python** – Core application logic
* **Streamlit** – User interface
* **pdf2image** (Poppler) – PDF processing
* **Google Gemini API** – Resume and job description analysis

---

## Output Overview

* Resume strengths and weaknesses
* ATS compatibility insights
* Missing and recommended keywords
* Match percentage score
* Actionable suggestions with pros and cons

---

## Future Enhancements (Optional)

* Support for DOCX resumes
* Multi-job comparison
* Resume version tracking
* Export analysis as PDF/JSON

---

## License

This project is intended for educational and personal use. Add a license file if you plan to distribute or commercialize the application.
