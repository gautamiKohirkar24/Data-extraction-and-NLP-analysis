# Data-extraction-and-NLP-analysis

## Overview

This project involves the extraction and analysis of textual data from a set of URLs provided in an input file. The extracted articles are analyzed for various textual metrics, including sentiment and readability scores.

## Objectives

1. **Data Extraction:** Extract article text from URLs, excluding website headers, footers, and any non-article content.
2. **Data Analysis:** Perform text analysis to compute metrics such as sentiment scores, readability indices, and various other textual statistics.

## Project Structure

- **data_extraction.py:** Python script for extracting article text from the provided URLs.
- **text_analysis.py:** Python script for performing text analysis on the extracted articles.
- **Input.xlsx:** Excel file containing URLs of articles to be processed.
- **Output Data Structure.xlsx:** Template for the output format required for the analysis results.
- **Text Analysis.docx:** Document explaining the methodology for text analysis.

## Getting Started

### Prerequisites

- Python 
- Required Python libraries:
  - `beautifulsoup4`
  - `pandas`
  - `nltk`
  - `openpyxl`
  - `requests`
  - `lxml`
  - `re`

## Installation and Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/gautamiKohirkar24/yourrepository.git
    cd yourrepository
    ```

2. **Install dependencies:**

    Ensure you have Python 3.x installed. Install required Python libraries using pip:

    ```bash
    pip install -r requirements.txt
    ```

3. **Prepare your data:**

    - Place your `Input.xlsx` file in the project directory.
    - Ensure `Text Analysis.docx` and `Output Data Structure.xlsx` are in the project directory.

## Usage

1. **Run the Python script:**

    ```bash
    python data_extraction_and_analysis.py
    ```

    This will extract article text from the URLs listed in `Input.xlsx`, perform the specified text analysis, and save the results in `output.csv`.

2. **Check the output:**

    - Open `output.csv` to view the results of the text analysis.

## Analysis Metrics

The following metrics are computed for each article:

- **POSITIVE SCORE**
- **NEGATIVE SCORE**
- **POLARITY SCORE**
- **SUBJECTIVITY SCORE**
- **AVG SENTENCE LENGTH**
- **PERCENTAGE OF COMPLEX WORDS**
- **FOG INDEX**
- **AVG NUMBER OF WORDS PER SENTENCE**
- **COMPLEX WORD COUNT**
- **WORD COUNT**
- **SYLLABLE PER WORD**
- **PERSONAL PRONOUNS**
- **AVG WORD LENGTH**




