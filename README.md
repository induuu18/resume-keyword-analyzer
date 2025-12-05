# resume-keyword-analyzer
A Streamlit-based ATS Resume Keyword Analyzer that extracts keywords from job descriptions, compares them with resume content, calculates match score, and visualizes missing skills using NLP.

A simple tool that compares a resume with a job description and shows how well they match. It extracts keywords, highlights what is missing, and gives an ATS-style match score. The goal is to help users improve their resume based on the requirements of a job.
Features
* Upload resume (PDF or DOCX)
* Paste job description
* See matched and missing keywords
* Get ATS match percentage
* Wordcloud of job keywords
* Clean Streamlit UI

Tech Used
* Python
* Streamlit
* NLTK
* PDFPlumber / Docx2txt
* WordCloud

 How to Run

1. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
2. Run the app:

   ```
   streamlit run app.py
   ```
