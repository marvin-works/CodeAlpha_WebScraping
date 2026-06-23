 📚 CodeAlpha Data Science Internship – Web Scraping Project

 📌 Project Title
Book Data Web Scraper using Python and BeautifulSoup

 📖 Project Description
This project was completed as part of the **CodeAlpha Data Science Internship Program**.

The objective of this project is to extract book information from a website using web scraping techniques and save the collected data into a structured dataset for analysis.

The scraper collects information such as:

- 📖 Book Title
- 💲 Price
- ⭐ Rating

The extracted data is stored in a CSV file, making it easy to analyze and visualize later.

---

 🌐 Website Used
Books to Scrape 
https://books.toscrape.com/

This website is specifically designed for practicing web scraping and data extraction techniques.

---

 🛠️ Technologies Used

- Python 3
- Requests
- BeautifulSoup4
- Pandas
- VS Code

---

 📂 Project Structure

```text
CodeAlpha-WebScraping/
│
├── scraping.py        # Python script for scraping data
├── books.csv          # Extracted dataset
├── screenshots/       # Project screenshots
└── README.md          # Project documentation
```

---

 ⚙️ How It Works

1. Send a request to the website.
2. Retrieve the HTML content.
3. Parse the webpage using BeautifulSoup.
4. Extract book details:
   - Title
   - Price
   - Rating
5. Store the extracted data in a Pandas DataFrame.
6. Export the data to a CSV file.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/CodeAlpha-WebScraping.git
cd CodeAlpha-WebScraping
```

Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

Run the script:

```bash
python scraping.py
```

---

 📊 Sample Output

| Title | Price | Rating |
|-------|--------|---------|
| A Light in the Attic | £51.77 | Three |
| Tipping the Velvet | £53.74 | One |
| Soumission | £50.10 | One |

---

 🎯 Learning Outcomes

Through this project, I learned how to:

- Extract data from websites using Python
- Understand HTML structure and webpage elements
- Parse web pages using BeautifulSoup
- Organize data using Pandas
- Export datasets into CSV format
- Build a beginner-friendly web scraping workflow

---

 🚀 Internship Information

Program: CodeAlpha Data Science Internship  
Task: Task 1 – Web Scraping  
Intern: Marvin Nneji-Ohanogu

---

 📜 License

This project is created for educational and internship purposes.
