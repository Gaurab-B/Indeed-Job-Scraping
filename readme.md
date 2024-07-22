# Version 1.2: Scraping Indeed

## Overview

This project provides a Python script for scraping job listings from Indeed using Selenium. The notebooks included are designed to help you understand how the code functions.

## Instructions

### Step 1: Prepare Your Environment

1. **Install Dependencies**:
   - Ensure you have Python installed.
   - Install Selenium: `pip install selenium`.
   - Download the appropriate WebDriver for your browser (e.g., ChromeDriver for Google Chrome).

2. **Search for Jobs**:
   - Go to [Indeed](https://www.indeed.com) and search for jobs by specifying your desired job title and location.

### Step 2: Run the Script

1. **Execute the Script**:
   - Run the `modular_script.py` Python script.

2. **Enter Search Details**:
   - When prompted, enter the page number, location, and job title for Indeed that you want to scrape.

3. **Scrape Data**:
   - The script will use Selenium to navigate through the pages and scrape job listings data.

4. **Repeat for Multiple Searches**:
   - You can run the script with different search parameters to gather data from various job listings.

### Important Note

**Ensure that you have configured Selenium and WebDriver correctly before running `modular_script.py`.**

### Output

- The script will combine all scraped data and save the results into a CSV file in the `datasets` folder.

### Example of the Output File Naming

The output file will be named based on the job role and location extracted from the search details. For example:

- If you search for AI roles in Cincinnati, the output file might be named `combined_AI_Cincinnati_data.csv`.

### Additional Instructions

After merging the datasets, any old datasets will be moved to the `old_files` folder within the `onepage-csvfiles` directory, provided there is a new file in the `datasets` folder.

## Next Steps

### 1. Improve Data Quality

- **Data Validation**: Add validation checks to ensure the data being scraped is accurate and complete.
- **Clean Data**: Implement data cleaning procedures to handle missing or inconsistent data.

### 2. Documentation and User Guide

- **Detailed README**: Expand your README to include setup instructions, usage examples, and troubleshooting tips.
- **User Manual**: Create a user manual or guide that provides step-by-step instructions for using the tool.

### 3. Testing

- **Unit Tests**: Write unit tests to verify that each function in your script works as expected.
- **Integration Tests**: Test the entire workflow to ensure that all components work together smoothly.

### 4. Deployment

- **Hosting**: Consider hosting your script on a cloud platform or a server if it needs to run regularly.
- **Scheduler**: Use a task scheduler (like cron jobs) to automate the script execution on a schedule.

### 5. Data Analysis and Reporting

- **Analyze Data**: Perform analysis on the scraped data to generate insights, such as trends in job postings or salary information.
- **Visualization**: Create visualizations (charts, graphs) to present the data more effectively.

### 6. Community and Feedback

- **Share with Others**: Share your project with the community for feedback and suggestions.
- **Open Source**: Consider open-sourcing your project to contribute to the community and get more feedback.
