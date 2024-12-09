# ATS-Resume-Analyzer
# 📄 Smart ATS Resume Analyzer

A Streamlit-powered application designed to optimize resumes for Applicant Tracking Systems (ATS). It analyzes resumes against job descriptions, identifies missing keywords, and provides actionable suggestions to improve your resume's match score.

---

## 🎯 Features

- **Resume Analysis**: Upload your PDF resume and get insights on how well it matches a given job description.
- **Keyword Identification**: Detect missing keywords that are critical for the job.
- **Profile Summary**: Receive a detailed analysis and personalized suggestions for improvement.
- **Easy-to-Use Interface**: A user-friendly sidebar and streamlined workflow.

---

## 🛠️ Technology Stack

- **Frontend**: [Streamlit](https://streamlit.io)
- **Backend**: [FastAPI](https://fastapi.tiangolo.com/)
- **AI Integration**: Google Generative AI (`gemini-pro`)
- **Utilities**:
  - PDF Text Extraction: `PyPDF2`
  - Environment Variable Management: `python-dotenv`

---
## 🚀 Getting Started  

### Prerequisites

- Python 3.8+
- A Google API key with access to Generative AI (`gemini-pro` model)

# Installation
**Installation**
1. Clone the Repository
```bash
git clone <repository-url>
cd smart-ats-resume-analyzer
```

2. Create Virtual Environment
```bash
conda create -p env python=3.10 -y
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Environment Configuration Create a .env file in the root directory:
```bash
GOOGLE_API_KEY =your_api_key_here
```

5. Run the Application
```bash
streamlit run app.py
```
 
 ---
 
## 🎥 Usage
 - Open the app in your browser (default: http://localhost:8501).
 - Enter the job description in the text area.
 - Upload your resume in PDF format.
 - Click the Analyze Resume button.
 - Review the match score, missing keywords, and improvement suggestions.

---

## 📧 Contact

### Feel free to reach out if you have any questions or suggestions:
 - Author: Dhruv Tambekar
 - GitHub: DhruvTambekar24
 - LinkedIn: https://www.linkedin.com/in/dhruv-tambekar-190a1728a/
