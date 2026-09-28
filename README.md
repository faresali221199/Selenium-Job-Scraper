# 🕸️ Naukrigulf Job Scraper (Selenium)

## 📌 Overview
This project is an automated web scraping tool built with **Python** and **Selenium**. It dynamically navigates through the Naukrigulf job portal to extract real-time job listings for "Data Engineer" roles across multiple pages and exports the cleaned data into a structured CSV file.

## 🛠️ Tech Stack
* **Language:** Python
* **Web Scraping:** Selenium WebDriver
* **Data Storage:** CSV Module

## 📊 Data Extracted
For each job listing, the script extracts:
* Job Title
* Company Name
* Job Location
* Required Experience
* Full Job Description

## 🚀 Features
* **Bypass Anti-Bot Detection:** Utilizes Chrome stealth options to bypass basic scraping detection.
* **Smart Waits:** Implements `WebDriverWait` instead of hardcoded sleeps for faster execution.
* **Pagination Handling:** Automatically loops through multiple search result pages.

## ⚙️ How to Run
1. Install Selenium: `pip install selenium`
2. Run the script: `python scraper.py` (or run the Jupyter Notebook).
3. The output will be saved automatically as `data_engineer_jobs.csv`.
