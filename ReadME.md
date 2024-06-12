# Job Posting Web Scraper

This project is a web scraper for job postings on Indeed. It extracts job data such as job title, company name, location, date posted, and required skills from job descriptions. The data is saved to an Excel file and visualized using Matplotlib and Seaborn.

## Features

- Extracts job postings for Data Scientist roles from Indeed
- Retrieves job title, company name, location, date posted, and job link
- Navigates to each job link to extract job description and required skills
- Saves the extracted data to an Excel file
- Provides a visualization of the most commonly required skills

## Requirements

- Python 3.8+
- Google Chrome
- ChromeDriver

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/job-posting-web-scraper.git
    cd job-posting-web-scraper
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Update the job title and location in the script if needed.
2. Run the Jupyter Notebook to extract job data and visualize the skills:

    ```bash
    jupyter notebook
    ```

3. Open the notebook and run the cells to perform the extraction and visualization.

## Files

- `job_scraper.ipynb`: The main Jupyter Notebook for extracting job data and visualizing skills.
- `job_data.xlsx`: The output Excel file with the extracted job data.
- `.gitignore`: Specifies which files and directories to ignore in the Git repository.
- `README.md`: This file, providing an overview of the project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.