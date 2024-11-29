# ATS Resume Assistant

ATS Resume Assistant is an AI-powered tool designed to help job seekers tailor their resumes for specific job descriptions by providing detailed feedback and evaluating the match percentage using cutting-edge AI models. This tool leverages the capabilities of Google Generative AI's `gemini-1.5-flash` model to analyze resumes and job descriptions effectively.

---

## Features

- **Resume Review**: Get professional feedback on your resume based on a provided job description.
- **Percentage Match**: Evaluate how well your resume aligns with a job description, including missing keywords and suggestions for improvement.
- **Interactive UI**: A user-friendly interface built with Streamlit for easy usage.
- **PDF Processing**: Upload and analyze resumes in PDF format.

---

## Tech Stack

- **Programming Language**: Python
- **Framework**: Streamlit
- **AI Model**: Google Generative AI `gemini-1.5-flash`
- **PDF Processing**: pdf2image
- **Image Handling**: PIL (Pillow)
- **Environment Variables Management**: python-dotenv

---

### Prerequisites
- Python 3.8 or higher
- Poppler installed and added to your system PATH for PDF processing ([Download Poppler](https://github.com/oschwartz10612/poppler-windows/releases))
- Google Generative AI API key

---

## Installation

Follow these steps to set up and run the ATS Resume Assistant on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/grvgeet03/ATS-Resume-Assistant.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ATS-Resume-Assistant
    ```

3. Set up a virtual environment:
   - **Windows**:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Set up the `.env` file with your **Google API key**:
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

6. Run the application:
    ```bash
    streamlit run main.py
    ```
