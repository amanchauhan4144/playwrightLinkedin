# LinkedIn Scraping Project

## Introduction

This project is a LinkedIn scraping tool developed using Playwright for scraping data from LinkedIn profiles. It allows users to extract information about companies based on specified search criteria, such as industry, company size, and location.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/amanchauhan4144/playwrightLinkedin/
    ```

2. Install the required dependencies using npm:

    ```bash
    npm install
    ```

## Usage

### Requirements

- Node.js installed on your machine.
- LinkedIn account credentials for login.

### Steps

1. Update the login credentials in the code:

    ```javascript
    await page.fill('input[name="session_key"]', "your-email@example.com");
    await page.fill('input[name="session_password"]', "your-password");
    ```

2. Run the script:

    ```bash
    node index.js
    ```

3. Wait for the scraping process to complete. The script will automatically generate an Excel file named `company_details.xlsx` containing the extracted company data.

## Features

- Scrapes data from LinkedIn profiles based on specified search criteria.
- Extracts information such as company name, website, foundation year, company size, and headquarters.
- Saves the scraped data in an Excel file for further analysis.

## Limitations

- This script interacts with LinkedIn's website, so it may be limited for data scraping.
- Use responsibly and consider LinkedIn's terms of service regarding automated scraping.


