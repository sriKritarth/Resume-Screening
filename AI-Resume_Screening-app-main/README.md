
# AI-Powered Resume Screening Tool

A web-based application that automates the evaluation of job applicants' resumes using AI and Natural Language Processing (NLP).

## Description

The AI-Powered Resume Screening Tool is designed to assist recruiters by automatically evaluating resumes based on a provided job description and keywords. This tool leverages the Groq API for NLP to analyze resumes and determine candidate suitability.

## How It Works

1. **Upload Resumes**: Upload any number of resumes or CVs and click submit.
   ![Upload Interface](/Image%20file/Interface1.png)
2. **AI Analysis**: The AI will analyze the resumes or CVs according to your specified criteria and provide results with detailed explanations.
   ![Result Interface](/Image%20file/result%20interface.png)

## Features

- **Resume Upload**: Upload multiple resumes in PDF format through a web interface.
- **Job Description Input**: Provide a job description and specify mandatory keywords.
- **AI-Powered Analysis**: Extract text from resumes using `pdfplumber` and evaluate relevance based on job description and keywords.
- **Suitability Classification**: Classify candidates as "Suitable", "Maybe Suitable", or "Not Suitable" with detailed comments.
- **Real-time Processing**: Rapid processing of resumes with dynamic results display.
- **CSV Export**: Export evaluation results for further review or record-keeping.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/username/ai-resume-screening-tool.git
   cd ai-resume-screening-tool
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. SetUp the flask app:
   ```bash
   set FLASK_APP=app.py
   ```
3. Start the server:
   ```bash
   flask run
   ```

## Usage

1. Upload as many resumes as you want through the web interface.
2. Enter a job description and specify mandatory keywords.
3. Review the AI-generated suitability classification and comments for each resume.
4. Export results as a CSV file for further analysis.

## Technologies Used

- **Backend**: Flask (Python) for handling requests and processing resumes.
- **Frontend**: HTML, CSS, and JavaScript for user interaction.
- **AI Model**: Groq API for resume evaluation and suitability classification.
- **File Handling**: `pdfplumber` for extracting text from PDF resumes.
- **Data Storage**: CSV files for exporting evaluation results.

## Contribution Guidelines

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

## License

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT/)

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.