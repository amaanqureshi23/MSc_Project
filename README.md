# Polymer Property Extraction from Scientific Papers

This repository contains a Python-based tool for extracting polymer names and their associated properties from scientific papers in PDF format. It uses a combination of regex, natural language processing (NLP) with spaCy, and data processing with pandas to create a structured dataset of polymer properties.

---

## Features

- Extracts text from PDFs using `PyMuPDF` (`fitz` library).
- Identifies polymer names (e.g., **polyethylene**, **nylon**) using regex patterns.
- Extracts polymer-related properties (e.g., **melting point**, **density**, **tensile strength**) and their values from surrounding text.
- Creates a structured dataset in CSV format for further analysis or reporting.

---

## Requirements

- Python 3.8+
- Libraries:
  - `PyMuPDF` (`fitz`)
  - `spaCy`
  - `pandas`
  - `re` (built-in)
