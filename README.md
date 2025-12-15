# Python Assignment – Data Science 

##  Overview

This repository contains my **Python Assignment for Data Science**, designed to evaluate core Python skills required for real-world data and AI projects. The assignment covers **date/time handling, mathematical logic, file processing, NumPy usage, and API-based data analysis** with proper error handling and documentation.

---

##  What I Learned

* Writing **robust Python programs** with input validation and exception handling
* Working with **datetime** for age calculations and format conversions
* Implementing **prime number algorithms** efficiently
* Processing structured data using **NumPy arrays**
* Reading from and writing to files safely
* Integrating **external APIs (OpenWeatherMap)** using `requests`
* Handling **real-world issues** like API errors and Unicode encoding problems
* Writing clean, readable, and well-commented Python code

---

## 📂 Project Structure

```
Python_Assignment_Week3/
│
├── students.txt
├── weather_log.csv
└── README.md
```

---

##  1.Age Calculator

**Concepts Used:**

* `datetime` module
* Input validation
* Exception handling

**Features:**

* Accepts birth date in `mm/dd/yyyy` format
* Calculates current age
* Converts date to European format (`dd/mm/yyyy`)
* Handles invalid inputs gracefully

---

## 2. Prime Number Generator

**Concepts Used:**

* Loops and conditions
* Mathematical optimization
* Exception handling

**Features:**

* Accepts a valid positive integer range
* Generates prime numbers within the range
* Displays output formatted as **10 numbers per line**
* Handles invalid inputs safely

---

##  3.Student Marks Processor

**Concepts Used:**

* File handling
* NumPy structured arrays
* Sorting and statistics

**Features:**

* Reads student marks from file
* Computes weighted overall marks
* Assigns grades based on rules
* Sorts students by performance
* Writes results to output file
* Displays grade distribution statistics

---

## 4. Weather Data Fetcher & Analyzer

**Concepts Used:**

* REST API integration
* `requests` library
* JSON parsing
* CSV file handling
* Unicode-safe file writing

**Features:**

* Fetches live weather data using OpenWeatherMap API
* Classifies weather as Cold / Mild / Hot
* Generates alerts for high wind and humidity
* Logs weather data to CSV using UTF-8 encoding
* Graceful handling of API, network, and data errors

---

## Technologies Used

* Python 3.x
* NumPy
* Requests
* CSV module
* OpenWeatherMap API

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/BhagyalaxmiAinapur_week3.git
```

2. Navigate to the project directory

```bash
cd DataScience_week3
```

3. Run any exercise

```bash
python Datascience_week3.ipynb
```

>  For Exercise 4, replace the API key with your own OpenWeatherMap API key.

---

##  Submission Details

* Repository is **public** as per instructions
* Each exercise is implemented in a **separate `.py` file**
* Code includes **line-by-line comments**
* Output files generated and tested
* Assignment added to portfolio to showcase practical Python skills

---

## Conclusion

This assignment strengthened my Python fundamentals and exposed me to real-world challenges such as API integration, data processing, and encoding issues. It reflects my readiness to work on **Data Science and AI projects** with clean, maintainable, and professional-quality code.

---
 *Feel free to explore the code and reach out for feedback or collaboration!*
