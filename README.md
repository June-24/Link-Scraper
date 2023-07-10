# Link-Scraper

This repository contains a Django Link Scraper website that you can run locally. Follow the instructions below to get started.

## Prerequisites

Make sure you have the following software installed on your system:

- Python (version 3.7 or higher)
- pip (Python package manager)

## Installation

1. Clone this repository to your local machine or download and extract the ZIP file.

2. Open a terminal or command prompt and navigate to the project's root directory.

3. Create a virtual environment by running the following command:

   ```bash
   python3 -m venv myenv
   ```
4. Activate the Virual environment:
   - on macOS and linux:
   ```bash
   source myenv/bin/activate
   ```
    - on windows:
   ```bash
   myenv\Scripts\activate
   ```
4. Install the project dependencies from the requirements.txt file:
  ```bash
pip install -r requirements.txt
```

## Running the Website
To run the Django website, execute the following command in the project's root directory:
```bash
python manage.py runserver
```
After running the command, the website will be accessible at http://localhost:8000 in your web browser.

# Description
- This is a django webapp, in which when you input a link, it will scrape all the embedded links from that website.
- It displays those webites and stores them it its local SQLite database
- I used two python libraries
  - BeautifulSoup
  - Requests
- For the frontend I used bootstrap, for some basic designing

# Images Below Show the functioning of the website
## 1. Base page
![image](https://github.com/June-24/Link-Scraper/assets/123622678/e83ab7a5-a96a-45f1-ae39-48da99364202)
## 2. Entering the website link
![image](https://github.com/June-24/Link-Scraper/assets/123622678/62855198-ab36-44f5-8317-d19df066fbb2)
## 3. Output after Scraping
![image](https://github.com/June-24/Link-Scraper/assets/123622678/96037bbd-4cac-44f6-8de2-9fa6525bb593)
![image](https://github.com/June-24/Link-Scraper/assets/123622678/67bbf6e9-ee22-4611-8939-4ff3b9848cd2)
## 4. Clearing the output of all the links
![image](https://github.com/June-24/Link-Scraper/assets/123622678/0260a717-8d89-41c3-8e0a-00a1e9ff62bc)
> after delete
![image](https://github.com/June-24/Link-Scraper/assets/123622678/33dc24d3-0ddb-4700-9f68-6414c47f73e3)








   


 

 
