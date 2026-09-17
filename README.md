# Python Job Listings Scraper

A web scraping tool built with Python, BeautifulSoup, and Requests to collect job listings from [Fake Python Jobs](https://realpython.github.io/fake-jobs/) and export the structured data into a CSV file.

## Features

* **Data Extraction**: Scrapes key job details including **Job Title**, **Company Name**, **Location**, and **Job Description URL**.
* **Automated Export**: Automatically cleans and saves extracted data into a structured `jobs.csv` file.
* **Lightweight & Modular**: Clean code structure, easy to customize for other job portals or scraping tasks.

## Tech Stack

* **Python 3.x**
* **Requests** - For fetching HTML web pages
* **BeautifulSoup4** - For parsing and extracting HTML elements
* **Pandas** - For data processing and CSV export

---

## Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/MTrung94/Python-Job-Listings-Scraper.git](https://github.com/MTrung94/Python-Job-Listings-Scraper.git)
   cd Python-Job-Listings-Scraper
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

Run the main scraper script:
```bash
python scraper.py
```

After execution, a file named `jobs.csv` will be generated in the root directory.

---

## Sample Output (`jobs.csv`)

| Job Title | Company Name | Location | URL |
| :--- | :--- | :--- | :--- |
| Senior Python Developer | Payette Group | Futuredale, AA | https://realpython.github.io/fake-jobs/jobs/senior-python-developer-0.html |
| Energy engineer | Vasquez-Hopkins | South Thomasfort, AP | https://realpython.github.io/fake-jobs/jobs/energy-engineer-1.html |

---

## Project Structure

```text
Python-Job-Listings-Scraper/
│
├── scraper.py          # Main Python script for scraping
├── requirements.txt    # Project dependencies
├── jobs.csv            # Output CSV file (generated after running)
└── README.md           # Project documentation
```

## License

Distributed under the MIT License. See `LICENSE` for more information.
