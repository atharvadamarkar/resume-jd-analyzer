# Resume vs Job Description Analyzer

## 🧠 Introduction

This is a personalized and enhanced version of a Resume–Job Description Analyzer built using Python and NLP. The tool helps job seekers understand how well their resume aligns with a given job description by extracting technical keywords and calculating a semantic similarity score using word embeddings.

Originally inspired by [subhash-vadlamani/resume-job-description-analyzer](https://github.com/subhash-vadlamani/resume-job-description-analyzer), this version has been customized by [Atharva Damarkar](https://github.com/atharvadamarkar).

---

## 🚀 Features

- **PDF Upload Support**: Upload your resume and job description in PDF format.
- **Keyword Extraction**: Extracts relevant and technical keywords from both documents using `spaCy` and `nltk`.
- **Semantic Matching**: Calculates match score using word vector similarity instead of raw keyword matching.
- **User-Friendly Interface**: GUI built with `tkinter` for ease of use.

---

## ⚙️ Setup and Installation

### ✅ Prerequisites

- Python 3.6 or higher
- Recommended: Create and activate a virtual environment

### 🔧 Installation Steps

```bash
git clone https://github.com/yourusername/resume-jd-analyzer.git
cd resume-jd-analyzer

# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

# Install requirements
pip install -r requirements.txt
python -m spacy download en_core_web_md
