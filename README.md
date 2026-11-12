# AI Resume and Invoice Extraction

## Project Overview
This project uses Google's Gemini AI to extract structured information from resume and invoice text.

## Features
- Resume information extraction
- Invoice information extraction
- Structured data validation using Pydantic
- JSON output generation

## Technologies Used
- Python
- Google Gemini API
- Pydantic
- Python-dotenv

## Project Files
- `main.py` – Main application
- `extractor.py` – AI extraction functions
- `schemas.py` – Data validation schemas
- `.gitignore` – Excludes private and unnecessary files

## Installation

Install the required packages:

```bash
pip install google-genai pydantic python-dotenv
```

## API Key Setup

Create a `.env` file in the project folder and add:

```text
GEMINI_API_KEY=your_api_key_here
```

Never upload your actual API key to GitHub.

## Run the Project

```bash
python main.py
```

Choose Resume Extraction or Invoice Extraction, paste your document text, and type `END` on a new line.

The extracted data is saved as JSON in the `output` folder.
