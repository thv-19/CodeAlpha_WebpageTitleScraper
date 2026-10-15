# Webpage Title Scraper

## Project Overview

The Webpage Title Scraper is a Python program that retrieves a webpage and extracts its title automatically.

This project was created as part of a Python programming internship task to practice working with HTTP requests, HTML, and web scraping.

## Features

- Connects to a fixed webpage using Python.
- Retrieves the webpage's HTML content.
- Parses HTML using BeautifulSoup.
- Extracts the webpage title.
- Displays the title in the terminal.

## Technologies Used

- Python 3
- Requests
- BeautifulSoup4

## Python Libraries

### Requests

The `requests` library is used to send an HTTP request to the webpage and retrieve its HTML content.

### BeautifulSoup

The `BeautifulSoup` library is used to parse the HTML and locate the webpage's `<title>` element.

## Installation

Make sure Python 3 is installed on your computer.

Install the required libraries using:

```bash
pip install requests beautifulsoup4
```
## How to Run
1.Open the project folder in VS Code.
2.Open the terminal.
3.Run the following command:
```bash
python webpage_title_scraper.py
```
4. The program will retrieve the webpage and display its title.

## Example

The program uses the following fixed webpage:

https://example.com

Example output:

Webpage Title: Example Domain

## How It Works

1. Imports the `requests` and `BeautifulSoup` libraries.
2. Stores the webpage URL in a variable.
3. Sends a request to the webpage.
4. Receives the webpage's HTML content.
5. Parses the HTML using BeautifulSoup.
6. Finds the `<title>` element.
7. Displays the webpage title in the terminal.

## Project Purpose

This project demonstrates basic web scraping concepts in Python, including making HTTP requests, processing HTML, and extracting specific information from a webpage.

