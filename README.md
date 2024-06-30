# Library-Acquisitions---Data-Scraper || Automated Library Acquisitions Data Scraping

## Authors:
 - **Birva Dave** | GitHub: [Birva1809](https://github.com/Birva1809)
 - **Brijraj Kacha** | GitHub: [BR-Kacha](https://github.com/BR-Kacha)

## Project Overview

This project aims to streamline and improve the accuracy of library acquisitions data management for a university library. The system is built using Python and focuses on automating the extraction of book details from online source using given 10-digit ISBN numbers. It handles over 60,000 entries, ensuring efficiency and precision in data scraping.

## Features

- **Web Scraping:** Extracts 13-digit ISBN numbers, book titles, author names, and publication details from the web.
- **Automated Sign-In:** Facilitates automated sign-in to online resource for efficient data retrieval.
- **Data Cleaning:** Removes duplicate entries and marks entries as 'NOT FOUND' when data is unavailable.
- **Excel Export:** Outputs the cleaned and enriched data into Excel sheets for easy integration into the library's acquisition processes.


## Usage

1. **Configure the script:**
   - Update the script with the relevant Chrome driver path and login credentials for automated sign-in.
   - Download your suitable chrome-drive from here: [https://googlechromelabs.github.io/chrome-for-testing/]

2. **Run the script:**
   - Run the code file. While the code is running, the Chrome browser will open automatically, so do not close it. Also, ensure that the Excel file being read and written to during the execution of the program is not open.
     
4. **Check the output:**
   - The output Excel file will be generated in the specified directory with the cleaned data.

