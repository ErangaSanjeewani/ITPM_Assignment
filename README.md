# Transliteration Accuracy Testing - ITPM Assignment 1

This repository contains the automated test suite for evaluating the accuracy of the Singlish-to-Sinhala transliterator available at:
https://www.pixelssuite.com/chat-translator

## Project Structure
- `IT23828452_Assignment 1 - Test cases.xlsx`: The Excel file containing 50 negative test cases and their results.
- `test_automation.py`: The Playwright script used to automate the testing process.
- `README.md`: Project documentation.
- `Git_Link.txt`: Link to the public Git repository.

## Prerequisites
- Python 3.11 or higher
- Google Chrome browser

## Setup Instructions
1. Install the required Python dependencies:
   ```bash
   pip install playwright openpyxl pandas
   ```
2. Install the Playwright browser binaries:
   ```bash
   playwright install chromium
   ```

## Running the Tests
To execute the automated test suite and update the Excel results:
```bash
python test_automation.py --excel "IT23828452_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## Student Information
- **Student ID**: IT23828452
- **Module**: IT3040 – ITPM
