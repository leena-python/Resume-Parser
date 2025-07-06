Automated Resume Parser using Python & spaCy

The "Automated Resume Parser" is a beginner-friendly Python project that extracts key details like Name, Email, Phone Number, Skills, and Experience from uploaded resumes in PDF format. This tool is useful for HR professionals, recruiters, and job portals to automate the shortlisting process and organize candidate data efficiently.

Features

  - Upload resume in PDF format
  - Automatically extracts:
  - Name
  - Email
  - Phone number
  - Skills
  - Experience (if available)
  - Fast and lightweight using **spaCy** and **PDFPlumber**
  - Built with **Flask** for a simple web interface

 Technologies Used

- Python 
- Flask
- spaCy (NLP processing)
- pdfplumber (PDF text extraction)
- re (Regex for pattern matching)

Install required libraries:- pip install -r requirements.txt & python -m spacy download en_core_web_sm

Run the Flask app - python app.py
