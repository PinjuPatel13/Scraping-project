# Book Information Scraper

## Overview

This project is designed to scrape book information from a specified website. The scraper collects details such as book title, author, price, and availability, and stores the data in a structured format (e.g., CSV, JSON). This scraper is built using Python and Scrapy, and it provides an efficient way to gather and organize book data for further analysis or use.

---
## Features

Scrapes multiple pieces of book information: title, author, price, availability.
Data is stored in both CSV and JSON formats for flexibility.
Built using Scrapy framework for robust scraping.
Easily customizable to scrape data from any other book-related website by adjusting the spider's rules.


## Installation Guide

If you'd like to get started with this project, follow the steps below.

### Step 1 - Install & Activate Your Python Virtual Environment

To install and activate the Python virtual environment, follow the instructions based on your operating system:

- **For MacOS**: [Virtual Environment Setup for MacOS](https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-macos)
- **For Windows**: [Virtual Environment Setup for Windows](https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-windows)
- **For Linux**: [Virtual Environment Setup for Linux](https://thepythonscrapyplaybook.com/freecodecamp-beginner-course/freecodecamp-scrapy-beginners-course-part-2-scrapy-environment/#setting-up-your-python-virtual-environment-on-linux)

Once set up, activate the virtual environment:

```bash
source venv/bin/activate
```

---

### Step 2 - Clone the Project

Clone the repository from GitHub:

```bash
git clone https://github.com/yourusername/book-scraper.git
cd book-scraper
```

---

### Step 3 - Install the Required Python Modules

Install the dependencies required to run the project by executing the following:

```bash
pip install -r requirements.txt
```

---

### Step 4 - Run the Project / Follow the Course

To run the project and start scraping, follow these steps:

1. Navigate to the `bookscraper` directory:

    ```bash
    cd bookscraper
    ```

2. View the available spiders:

    ```bash
    scrapy list
    ```

3. Run the spider:

    ```bash
    scrapy crawl bookspider
    ```

---

## Troubleshooting Tips

If you encounter any issues during setup or execution, consider these solutions:

- **Upgrade pip** if you face issues with dependency installations:

    ```bash
    pip install --upgrade pip
    ```

- **Resolve `NotADirectoryError`** by setting the `PKG_CONFIG` environment variable:

    ```bash
    export PKG_CONFIG=/path/to/pkg-config
    ```

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contributing
Feel free to fork this repository, submit issues, and create pull requests. If you'd like to contribute new features or improvements, follow these steps:

Fork the repository.
Create a new feature branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Submit a pull request.
