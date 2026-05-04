# Assignment 1 - Transliteration Accuracy Testing

## Description
This project automates testing of the Chat Sinhala transliteration 
function available at:
https://www.pixelssuite.com/chat-translator

The objective is to evaluate the correctness of Chat Sinhala 
transliteration by testing it with words, phrases, and sentence 
structures commonly used in informal Sinhala typing.

## Prerequisites
- Python 3.13
- pip

## Installation

### Step 1: Clone the repository
git clone https://github.com/YOUR_USERNAME/itpm-assignment1.git
cd itpm-assignment1

### Step 2: Install dependencies
python -m pip install playwright openpyxl

### Step 3: Install browser
python -m playwright install chromium

## How to Run Tests

### Using Edge browser:
python test_automation.py --browser edge --excel "test_automation\Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 7000 --retries 12 --retry-wait-ms 1200 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1

### Using Chrome browser:
python test_automation.py --browser chrome --excel "test_automation\Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 7000 --retries 12 --retry-wait-ms 1200 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1

### Using default Chromium:
python test_automation.py --excel "test_automation\Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 7000 --retries 12 --retry-wait-ms 1200 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1

## Project Structure
