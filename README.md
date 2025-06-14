

# EzHunt | Smart Recruitment Assistant

**EzHunt** is an AI-powered recruitment assistant designed to streamline and automate the job screening process. It parses job descriptions, analyzes resumes, computes match scores, and helps shortlist top candidates with minimal manual intervention.

---

## Table of Contents
- [Description](#description)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## Description

EzHunt simplifies the recruitment workflow by automating repetitive tasks such as job description analysis, resume parsing, candidate shortlisting, and interview scheduling. The tool provides a user-friendly web interface built with Streamlit, leveraging advanced AI models for accurate and efficient candidate evaluation[4].

---

## Key Features

- **Job Description Parsing:** Upload or paste job descriptions in PDF or CSV format. The system extracts and summarizes key elements (job title, required skills, experience, qualifications, etc.).
- **Resume Analysis:** Upload multiple resumes in PDF format. The system extracts text and evaluates each candidate against the job requirements.
- **AI-Powered Match Scoring:** Uses Google’s Gemini AI to compute match percentages for skills, experience, and qualifications.
- **Candidate Shortlisting:** Set a threshold for match scores and generate a shortlist of top candidates.
- **Interview Scheduling:** Generate personalized interview invitations with proposed time slots and send them directly via email.
- **Interactive Dashboard:** Visualize candidate match scores, strengths, and areas for improvement in a clean, intuitive interface.
- **Customizable Workflow:** Navigate through recruitment steps (Import, Upload, Review, Shortlist, Schedule) with clear progress indicators.

---

## Tech Stack

- **Frontend:** Streamlit (Python)
- **AI/NLP:** Google Gemini API, PyPDF2
- **Data Handling:** Pandas
- **Email:** smtplib, email.mime
- **Environment Management:** dotenv
- **Other:** re, json, datetime, random, io, base64

---

## Getting Started

### Prerequisites

- **Python 3.8+**
- **Google API Key** (for Gemini AI)
- **Optional:** Gmail account (for sending interview invitations)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/EzHunt_Submission
   cd ezhunt
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(If you don’t have a `requirements.txt`, use:*
   ```bash
   pip install streamlit google-generativeai pypdf2 python-dotenv pandas
   ```

3. **Create a `.env` file:**
   ```
   GOOGLE_API_KEY=your_api_key_here
   COMPANY_NAME=Your Company Name
   ```

### Running the App

1. **Start the Streamlit app:**
   ```bash
   streamlit run app.py
   ```
2. **Follow the prompts in your browser to begin the recruitment process.**

---

## Usage

1. **Import Job Description:** Upload a PDF/CSV or paste the job description text.
2. **Upload Resumes:** Upload candidate resumes (PDF format).
3. **Review Analysis:** View detailed match scores, strengths, and areas for improvement.
4. **Shortlist Candidates:** Set a match threshold and generate a shortlist.
5. **Schedule Interviews:** Generate and send personalized interview invitations.

---

## Project Structure

```
ezhunt/
│── app.py                # Main Streamlit app
│── .env                  # Environment variables
│── README.md             # Project documentation
│── requirements.txt      # Python dependencies
```

---

## Roadmap

- **Integrate more AI models for enhanced resume parsing and multiple job description.**
- **Add support for additional file formats (e.g., DOCX, images).**
- **Implement candidate feedback collection.**
- **Enhance email automation (calendar invites, reminders).**
- **Add multi-language support.**

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss your ideas.

---

## License

This project is licensed under the MIT License.

---

## Contact

**Aarchi Kothari**  
Email: [support@ezhunt.com](mailto:support@ezhunt.com)

---

## Acknowledgments

- **Streamlit** for the intuitive web interface.
- **Google Gemini** for advanced AI capabilities.
- **Open-source community** for inspiration and best practices.

---

*EzHunt AI Recruitment Assistant | Aarchi Kothari | © 2025*[4]

