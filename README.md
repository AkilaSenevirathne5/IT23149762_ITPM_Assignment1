# IT23149762 - ITPM Assignment 1
## Transliteration Accuracy Testing 

### Overview
This project evaluates the accuracy of the Chat Sinhala transliteration function at PixelsSuite. It identifies 50 failure scenarios where Singlish is incorrectly converted. The testing is automated using Playwright and Python.

**Student ID:** IT23149762

### Prerequisites
- Python 3.11+
- Playwright (`pip install playwright`)
- Openpyxl (`pip install openpyxl`)

### How to Run
Run the following command:
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 15000 --type-delay-ms 100 --slow-mo-ms 500 --save-every 1
