# IT3040 - Assignment 1: Transliteration Accuracy Testing

## Overview

This project contains automated test cases for testing the Singlish to Sinhala transliteration feature at https://www.pixelssuite.com/chat-translator

## Prerequisites

- Python 3.11 or 3.12
- Google Chrome browser

## Installation

Run the following commands:

```
py -m pip install playwright openpyxl
py -m playwright install
```

## How to Run Tests

```
py IT23334106_test_automation.py --excel "IT23334106_Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

## Files

- `IT23334106_test_automation.py` - Playwright automation script
- `IT23334106_Test cases.xlsx` - Test cases with results
- `requirements.txt` - Python dependencies
- `Repository_Link.txt` - GitHub repository link
