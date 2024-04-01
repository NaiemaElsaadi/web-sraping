# Web Mining and Applied NLP (44-620)

## Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

### Student Name: Naiema Elsaadi

In this assignment, we'll explore web scraping and natural language processing (NLP) techniques using Python libraries such as Requests, BeautifulSoup, and spaCy. Web scraping allows us to extract useful information from websites, while NLP enables us to analyze and understand the extracted text data.This project is part of the Web Mining and Applied NLP (44-620) course. 

## Introduction

This project focuses on exploring the fundamentals of web scraping and natural language processing (NLP) techniques using Python. By leveraging libraries such as Requests, BeautifulSoup, and spaCy, we aim to extract valuable information from web pages and analyze text data to gain insights.

### Objectives
<b>This exercise is used to practice web scraping (fetching and extracting information) and processing the content from a web page.</b> 
1. Web Scraping: Learn how to extract structured data from websites using the Requests library for HTTP requests and BeautifulSoup for parsing HTML content.

2. Natural Language Processing (NLP): Dive into NLP techniques using spaCy, a powerful library for text processing and analysis. Explore tasks such as tokenization, part-of-speech tagging, lemmatization, and sentiment analysis.

3. Integration: Combine web scraping and NLP techniques to extract text data from web pages and perform various analyses, such as identifying key tokens, determining sentiment, and visualizing text data.

## Task Breakdown:
1. Task 1: Get Started
- Copy the base repository to your GitHub account.
- Clone your repository to your local machine.
2. Task 2: Open Notebook and Complete Tasks
- Add a clickable link to your GitHub repo in the Markdown introduction.
- Use Markdown headings for each question number.
- Complete the provided tasks in the Jupyter notebooks.
- Execute the notebooks, commit, and push changes to GitHub.
3. Task 3: Export to HTML and Finalize Repo
- Execute each notebook.
- Export each notebook to HTML format.
- Commit and push the HTML files along with the executed notebooks.

## Requirements

<br>Markdown introduction with name and clickable link is required.
<br>Markdown Section Headings for each Question are required. 
<br>Execute your code before exporting HTML and pushing notebooks. (See FAQ for help.)  
<br>Unexecuted code is not eligible for credit.

## Prerequisites
Before running the project, ensure you have the following prerequisites:

- Git
- Github
- Python 3.10+ installed
- VS studio Code
- juypterlab
- anaconda prompt (miniconda3) or windows PowerShell
- Required Python libraries (e.g., numpy) installed in your active environment

## Getting Started

- Before we begin, make sure you have the necessary dependencies installed in your Python environment. 
- If you haven't already, you'll need to install spaCy and spaCy NLP  using the following command:
<br>`python -m pip install beautifulsoup4`
<br>`python -m pip install html5lib`
<br>`python -m pip install requests`
<br>`python -m pip install spacy`
<br>`python -m pip install spacytextblob`
- Install them into our active virtual environment.
- Use an import statement in our Python. 
- Spelling and capitalization matters 
- The typical approach is to:
1. Create a virtual environment
2. Activate the virtual environment
3. Install into the active virtual environment (e.g. `python -m pip install beautifulsoup4`)
4. In your Python, import it (e.g. `from bs4 import BeautifulSoup`)
5. spaCy Import Error:
<br> Go to the `pyvenv.cfg` file in the Virtual environment folder
<br> Set the `include-system-site-packages` to `true` and save the change
<br> Reactivate the virtual environment.

## Before we start 

` Create and activate a Python virtual environment. `
<br>` Address any errors you get running this code cell by installing the necessary packages into your active Python environment.`
<br>` Before starting the project, try all these imports FIRST`
<br>from collections import Counter
<br>import pickle
<br>import requests
<br>import spacy
<br>from bs4 import BeautifulSoup
<br>import matplotlib.pyplot as plt
<br>!pip list
<br>print('All prereqs installed.')

## How to Run

<b><br> Follow these steps to run the project:  </b></br>

1. Get the starter repo into your GitHub account.
2. Clone down your repo to your local machine,
3. Start up Jupyter lab (or Jupyter Notebook),
4. Make edits to Markdown cells and Python code cells
5. Run the Python scripts provided in the `src` directory to analyze song lyrics and view polarity scores.
6. Explore the results and gain insights into the emotional content of your favorite songs!
7. Add and commit your changes using Git
8. Push your commit up to the GitHub repo.
9. Export your notebook as HTML (a web page) for submission using the menu



## Installation

Instructions for installing any dependencies or software needed to run the project. Include commands for installing packages or setting up environments.

To use the notebooks in this repository, follow these steps:

1. Clone the repository to your local machine:
git clone Repo
2. Navigate to the project directory:
cd file
3. Create a virtual environment (optional but recommended):
python -m venv venv
4. Activate the virtual environment:
 For Windows:
venv\Scripts\activate
5. Install the required packages:
pip install -r requirements.txt
6. Launch Jupyter Lab:
jupyter lab
7. Open the desired notebook and execute the code cells.

## Data Source 

The source of the repository for this project is available at:[GitHub Repository](https://github.com/wmnlp-materials/web-scraping)


## Contact

For any questions, feedback, or inquiries, you can reach out to me via  [My GitHub Repository](https://github.com/NaiemaElsaadi/web-sraping)


## Acknowledgments

Special thanks to the Web Mining and Applied NLP (44-620) course instructor Dr. Case for her guidance and support throughout the project.

## Reference
https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start
https://github.com/denisecase/620-mod6-web-scraping
https://github.com/denisecase/620-mod6-web-scraping/blob/main/web_scraping.ipynb



