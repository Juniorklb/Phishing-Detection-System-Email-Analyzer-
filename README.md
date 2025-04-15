
# Phishing Email Analyzer

This tool scans and analyzes email files (.eml) to detect phishing attempts using heuristics, regex, and natural language processing (NLP).

## Features

- Extracts sender, subject, body, and links from emails
- Applies phishing detection rules (domain spoofing, suspicious links, etc.)
- Optional NLP-based classification
- Generates readable reports

## Getting Started

Put email samples in the `emails/` folder. Then run:

```bash
python analyzer/main.py

