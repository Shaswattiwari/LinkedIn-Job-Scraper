# LinkedIn Job Scraper

LinkedIn Job Scraper is a Python script designed to simplify the process of collecting job listings from LinkedIn based on specific search criteria. Whether you're a job seeker looking for opportunities or a data enthusiast interested in analyzing the job market, this tool provides a convenient way to scrape, analyze, and visualize LinkedIn job data.

## Features

- **Effortless Job Scraping:** The script automates the job scraping process, eliminating the need for manual data collection. You can specify the job position and location you're interested in, and the script will gather relevant job listings from LinkedIn.

- **Comprehensive Data:** It extracts essential job details, including job titles, company names, locations, salary information, job statuses, and posting dates.

- **Data Profiling:** The script generates a detailed data profile report using the Pandas Profiling library. This report offers insights into the data's structure, statistics, and potential issues.

- **Interactive Data Visualizations:** Using Plotly Express, the script creates interactive data visualizations, such as bar charts and timelines, to help you gain a better understanding of the job market. Visualizations include job listing statuses, salary ranges, job locations, and the distribution of job listings over time.

## Dependency Installation Guide

To run the LinkedIn job scraper code in any Python development environment, you'll need to install the necessary dependencies. These dependencies include Python packages and external tools. Follow these steps to install them:

### 1. Install Python

If Python is not already installed on your system, download and install the latest version of Python from the [official Python website](https://www.python.org/downloads/).

### 2. Create a Virtual Environment (Optional but Recommended)

It's a good practice to create a virtual environment to isolate your project dependencies. Use the following commands to create and activate a virtual environment:

```bash
# Create a virtual environment (optional)
python -m venv myenv
# Activate the virtual environment
# On Windows:
myenv\Scripts\activate
# On macOS and Linux:
source myenv/bin/activate
```

### 3. Install Python Packages

Within your virtual environment (if you created one), install the required Python packages using pip. Run these commands:

```bash
pip install selenium
pip install bs4
pip install pandas-profiling[notebook,html]
```

These commands will install the following packages:

- `selenium`: For web automation.
- `bs4` (Beautiful Soup 4): For HTML parsing.
- `pandas-profiling`: For generating data profiles and reports.

### 4. Install Chromium WebDriver

The code uses Chromium WebDriver for web automation. Install it as follows:

**On Ubuntu/Debian:**

```bash
sudo apt-get update
sudo apt-get install chromium-chromedriver
sudo cp /usr/lib/chromium-browser/chromedriver /usr/bin
```

**On macOS:**

You can use Homebrew to install Chromium and the WebDriver:

```bash
brew install --cask chromium
brew install chromedriver
```

**On Windows:**

You can download the Chromium WebDriver for Windows from the Chromium project's [official website](https://sites.google.com/chromium.org/driver/) and add it to your system's PATH.

### 5. Clone the GitHub Repository

Clone this GitHub repository to your local machine:

```bash
git clone https://github.com/YourUsername/LinkedIn-Job-Scraper.git
cd LinkedIn-Job-Scraper
```

### 6. Import and Run the Code

- Copy the provided code into a Python file (e.g., `linkedin_scraper.py`) within your project directory.
- Open your preferred text editor or Python IDE.
- Load the Python file containing the code.
- Run the program by executing the Python script.

### 7. Input Job Details

When prompted, enter the job title and location you want to search for on LinkedIn.

### 8. View the Results

The program will scrape job listings from LinkedIn, save them to a CSV file named `linkedin_job_records.csv`, and generate a profile report. You can view the report and visualizations as needed.

## How to Contribute

Contributions to this open-source project are encouraged! If you have ideas for enhancements, bug fixes, or additional features, please feel free to contribute by creating pull requests or opening issues.
