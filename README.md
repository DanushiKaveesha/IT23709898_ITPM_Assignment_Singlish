# IT23709898_ITPM_Assignment_Singlish

## Description

This project tests the Sinhala transliteration feature of the PixelSuite Chat Translator using automated test cases.
It focuses on negative cases where Singlish inputs produce incorrect Sinhala outputs.

---

## Technologies

* Python
* Playwright
* OpenPyXL

---

## How to Run

Install dependencies:
pip install playwright openpyxl

Install browsers:
python -m playwright install

Run the script:
py -3.13 IT23709898.py --excel "IT23709898.xlsx" --url "https://www.pixelssuite.com/chat-translator"

---

## Output

The Excel file will be updated with:

* Actual Output
* Pass/Fail status

---
## Running the Tests

From the Command Prompt (inside D:\IT23709898), run the following command:

bash 
PS D:\IT23709898> py -3.13 IT23709898.py --excel "D:\IT23709898\IT23709898.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
