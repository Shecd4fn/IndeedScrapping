# Job Scraper for Quantitative Roles

## Overview

This project uses Selenium to scrape job postings from a job board (e.g., Indeed) based on a specified search query. The extracted data includes job titles, company names, locations, and salaries, and the results are saved to an Excel file for further analysis.

## Features

- **Automated Web Scraping**:
  - Extract job postings dynamically from a job board using Selenium.
  - Handles pagination to scrape multiple pages until a specified number of postings is reached.

- **Data Extraction**:
  - Retrieves job titles, company names, job locations, and salary details (if available).

- **Data Export**:
  - Saves the extracted job postings into an Excel file for easy access and analysis.

## Prerequisites

### Required Software
1. **Python 3.8+**: Make sure Python is installed on your machine.
2. **Edge WebDriver**: Ensure the correct version of Microsoft Edge WebDriver is installed and matches your Edge browser version.

### Python Libraries
Install the required Python libraries:
```bash
pip install selenium pandas openpyxl
