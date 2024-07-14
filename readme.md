# Version 1.1: Scraping Indeed

## Overview

This project provides a Python script for scraping job listings from Indeed. The notebooks included are designed to help you understand how the code functions.

## Instructions

### Step 1: Prepare Your Data

1. **Search for Jobs**:
   - Go to [Indeed](https://www.indeed.com) and search for jobs by specifying your desired job title and location.

2. **Locate the Job Listings**:
   - Find the `<div>` element with the class `mosaic-jobResults` in the HTML of the search results page.

3. **Copy the Element**:
   - Copy the entire contents of this `<div>` element and paste it into a file named `temp.txt`.

### Step 2: Run the Script

1. **Execute the Script**:
   - Run the `modular_script.py` Python script.

2. **Enter Page Details**:
   - When prompted, enter the page number,location,and jobtitle of Indeed that you scraped.

3. **Repeat for All Pages**:
   - Repeat the above steps for each page of search results.

### Important Note

**Ensure that you have scraped all pages before running `modular_script.py`.**

### Output

- The script will combine all data and save the results into a CSV file in the datasets folder.

### Example of the Output File Naming

The output file will be named based on the job role and location extracted from the first file in the directory. For example:

- If the first file is named `AI-Cincinnati-Page(1).csv`, the output file will be named `combined_AI_Cincinnati_data.csv`.

### Additional Instructions

After merging the datasets, any old datasets will be moved to the `old_files` folder within the `onepage-csvfiles` directory, provided there is a new file in the `datasets` folder.

