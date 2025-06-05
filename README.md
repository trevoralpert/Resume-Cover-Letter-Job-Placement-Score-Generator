# Personalized Resume & Cover Letter Generator

A modern, AI-powered web app to generate, polish, and customize resumes and cover letters with perfect formatting and honest placement scores. Built with Streamlit, OpenAI GPT-4, and a modular Python DOCX template.

---

## Features
- **Resume Polisher:** Upload or paste your resume, polish it for a specific job, and download a perfectly formatted DOCX.
- **Cover Letter Generator:** Instantly create a tailored cover letter for any job using your resume and the job description.
- **Placement Scores:** Get honest, explainable scores for how well you fit a job—and how well the job fits you.
- **Section-by-Section Editing:** Review and edit every section of your resume before downloading.
- **Dynamic Bullet Points:** Add, remove, or regenerate bullet points for each job using GPT-4.
- **Custom Output Filenames:** Downloads are named like `Trevor Alpert Resume for OpenAI (2024-06-04).docx`.

---

## Tech Stack
- **Frontend:** [Streamlit](https://streamlit.io/)
- **AI/NLP:** [OpenAI GPT-4 API](https://platform.openai.com/)
- **Document Generation:** [python-docx](https://python-docx.readthedocs.io/)
- **Backend/Logic:** Python 3.12+

---

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone <repo-url>
   cd Personalized\ Resume:Cover\ Letter\ Generator
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Set up environment variables:**
   - Create a `.env` file with your OpenAI API key:
     ```env
     OPENAI_API_KEY=sk-...
     ```

4. **Run the app:**
   ```sh
   streamlit run main_app.py
   ```

---

## Usage

1. **Resume Polisher:**
   - Upload a DOCX resume or paste your content.
   - Enter the job title and description.
   - Polish your resume with GPT-4 and review the output.
   - Edit any section, add/remove bullet points, and download your resume as a DOCX.

2. **Cover Letter Generator:**
   - Enter the company, position, and job description.
   - Generate a tailored cover letter and download as DOCX or PDF.

3. **Placement Scores:**
   - Get honest fit scores for any job and resume combination.

**Output files are named automatically:**
- `Your Name Resume for Company (YYYY-MM-DD).docx`
- `Your Name Cover Letter for Company (YYYY-MM-DD).docx`

---

## Customization
- The resume template is fully modular and code-driven. You can adjust formatting, add new sections, or change the output style by editing `full_resume_template.py` and its helper templates.
- The app is designed for easy extension (e.g., add PDF output, new scoring features, or more advanced parsing).

---

## Credits
- Built by Trevor Alpert with help from OpenAI GPT-4.
- Uses [Streamlit](https://streamlit.io/), [python-docx](https://python-docx.readthedocs.io/), and [OpenAI](https://platform.openai.com/).

---

## License
MIT License (or specify your preferred license) 