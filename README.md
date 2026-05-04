# IT23845046 - IT3040 Assignment 1

## Install Dependencies
pip install playwright openpyxl
python -m playwright install

## Run Tests
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
