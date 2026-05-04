<<<<<<< HEAD
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
python test_automation.py --excel "F:\Assignment_1_Test_cases_New.xlsx" --header-row 1 --input-col "Input" --expected-col "Expected output" --actual-col "Actual output" --status-col "Status" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```


