# Wikipedia Diseases Scraper


This project aims to scrape information about diseases from the Wikipedia page: [List of Epidemics](https://en.wikipedia.org/wiki/List_of_epidemics). We utilize the powerful **Scrapy framework** to extract relevant data from the web page efficiently. The gathered data can be utilized for various purposes, such as research, analysis, or educational resources.

### type : 
freelancing project 

### client : 
andorthas

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The internet is a vast source of information, and Wikipedia, being one of the most comprehensive knowledge bases, contains valuable data on various topics, including epidemics and diseases. This project presents a simple yet effective solution to extract disease-related information from the Wikipedia page "List of Epidemics" using Scrapy, a Python web scraping framework.

## Installation

To run this project locally, follow these steps:

1. Ensure you have Python 3.x installed on your system.
2. Clone this repository to your local machine or download the ZIP archive.
3. Open a terminal or command prompt and navigate to the project's root directory.
4. Install the required dependencies using the following command:

```bash
pip install scrapy
```
## Usage
Once you have installed the necessary dependencies, you can start scraping disease information from the Wikipedia page. Follow these steps:

1. Navigate to the project's root directory using the terminal or command prompt.
2. Execute the Scrapy spider by running the following command:

```bash
scrapy crawl diseases -o diseases.json
```


Scrapy will start fetching data from the Wikipedia page and store it in a file named "diseases.json" in the project directory.
## Features
- Efficient Web Scraping: Scrapy is a fast and efficient web scraping framework, ensuring quick data extraction from Wikipedia.
- JSON Output: The scraped data is stored in a JSON file for easy access and further processing.
- Open-Source: This project is open-source, and contributions from the community are welcome!



