# Cyber Park Job Vacancy Scraper

A Python-based project that uses Selenium and webdriver-manager to scrape job vacancy information from Cyber Park's job search page and export the data into Excel and CSV formats.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Introduction

This project is designed to automatically scrape job listings from [Cyber Park's job search page](https://infopark.in/companies/job-search). It collects details such as job title, company name, and the last date of submission from each page of listings, iterating through multiple pages as needed. The retrieved data are then saved in both Excel and CSV formats.

## Features

- **Automated Web Scraping:** Utilizes Selenium to navigate and extract job vacancy data.
- **Dynamic Pagination:** Determines the total number of pages dynamically and iterates through them.
- **Data Export:** Saves the collected data into Excel and CSV files for easy analysis.

## Prerequisites

- Python 3.x
- Google Chrome browser

The project uses the following Python libraries:
- `selenium`
- `webdriver-manager`
- `pandas`
- `python-dotenv` (if environment variables are used)

## Installation

1. Clone the repository:

2. Install the required packages using pip:
   
## Usage

1. Open the Jupyter Notebook file named `web scrapping cyber park job vacancy.ipynb` in your preferred environment.
2. Run all the cells in the notebook. The script will:
- Launch a Chrome browser using Selenium.
- Navigate to the Cyber Park job listings URL.
- Extract job information (job title, company name, and last date of submission) from each page.
- Save the results in both Excel and CSV files in your Downloads folder.
3. Monitor the console output for progress updates and completion confirmation.

## Project Structure

| File/Folder                                   | Description                                 |
| --------------------------------------------- | ------------------------------------------- |
| `web scrapping cyber park job vacancy.ipynb`  | Jupyter Notebook containing the scraper code. |
| `README.md`                                   | This project README file.                   |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please feel free to reach out.

- **Your Name** – [your.email@example.com](mailto:your.email@example.com)
- GitHub: [https://github.com/yourusername](https://github.com/yourusername)

## Acknowledgements

- [Selenium Documentation](https://www.selenium.dev/documentation/) for guidance on browser automation.
- [webdriver-manager](https://pypi.org/project/webdriver-manager/) for simplifying driver management.
- [Pandas Documentation](https://pandas.pydata.org/docs/) for data manipulation and export functionalities.

