# Web Scraping — Books (Multi-page Scraper)

## TL;DR
Multi-page web scraper for books.toscrape.com. Extracts title, price, rating and exports CSV.

## Tech Stack
Python, Requests, BeautifulSoup, Pandas

## How to run
1. `git clone https://github.com/Neeraj-Chaurasiya/web-scraping-books.git`
2. `python -m venv venv && source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `python scraper.py` or run `web_scraping.ipynb`

## Files
- `analysis_multi_page.ipynb` — runnable script
- `analysis_single_page.ipynb` — runnable script
- `books_full.csv` — scraped dataset

## Output
- `books_full.csv` with columns: Title, Price, Rating

## License & Contact
MIT · neerajchaurasiya593@gmail.com
