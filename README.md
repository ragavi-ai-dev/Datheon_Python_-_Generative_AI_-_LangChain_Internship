# AI Resume and Invoice Extraction

<<<<<<< HEAD
## Project Description
This project uses Google's Gemini AI to extract structured information from resume and invoice text.

## Features
- Extracts information from resumes.
- Extracts information from invoices.
- Uses Pydantic models to validate extracted data.
- Saves extracted information as JSON files.
=======
## Project Overview
This project uses Google's Gemini AI to extract structured information from resume and invoice text.

## Features
- Resume information extraction
- Invoice information extraction
- Structured data validation using Pydantic
- JSON output generation
>>>>>>> origin/main

## Technologies Used
- Python
- Google Gemini API
- Pydantic
<<<<<<< HEAD
- python-dotenv

## Project Structure
```text
DAtheon_task1/
├── .env
├── .gitignore
├── schemas.py
├── extractor.py
├── main.py
└── output/
```

## Setup Instructions

1. Install Python.
2. Install the required packages:
=======
- Python-dotenv

## Project Files
- `main.py` – Main application
- `extractor.py` – AI extraction functions
- `schemas.py` – Data validation schemas
- `.gitignore` – Excludes private and unnecessary files

## Installation

Install the required packages:
>>>>>>> origin/main

```bash
pip install google-genai pydantic python-dotenv
```

<<<<<<< HEAD
3. Create a `.env` file in the project folder and add your Gemini API key:
=======
## API Key Setup

Create a `.env` file in the project folder and add:
>>>>>>> origin/main

```text
GEMINI_API_KEY=your_api_key_here
```

<<<<<<< HEAD
4. Run the project:
=======
Never upload your actual API key to GitHub.

## Run the Project
>>>>>>> origin/main

```bash
python main.py
```

<<<<<<< HEAD
5. Select Resume Extraction or Invoice Extraction.
6. Paste the document text and type `END` on a new line.
7. The extracted information will be saved as a JSON file inside the `output` folder.

## Note
Keep your Gemini API key private. Do not upload your `.env` file to GitHub.
=======
Choose Resume Extraction or Invoice Extraction, paste your document text, and type `END` on a new line.

The extracted data is saved as JSON in the `output` folder.
>>>>>>> origin/main
