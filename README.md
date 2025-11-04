## 📚 Book Review Dashboard

Explore and analyze book ratings and prices scraped from [Books to Scrape](https://books.toscrape.com/catalogue/page-1.html)
.
This interactive dashboard lets you filter, visualize, and understand pricing trends across book ratings.

The complete scraping code and visualization app are included in this [repository](https://github.com/imdwipayana/scrapping_book_review_webpage/blob/main/book_review_scrapping.ipynb)

## 🧾 How It Works

Data was scraped from all 50 pages of Books to Scrape using requests + BeautifulSoup.

Cleaned data was saved into books_scraped.csv.

A Streamlit app (app.py) visualizes the data interactively.

## 📊 Features

Filter books by rating and price range

View average price per rating

Explore price distribution with a histogram

See all results in an interactive table

🔗 Live App on [Streamlit Cloud](https://scrappingbookreviewwebpage.streamlit.app/)

## 🧠 Tech Stack

Python 3

BeautifulSoup / Requests

Pandas / Matplotlib

Streamlit (for web dashboard)

## ⚙️ Run Locally
git clone https://github.com/imdwipayana/scrapping_book_review_webpage
cd books-scraping-dashboard
pip install -r requirements.txt
streamlit run app.py

## ⚠️ Disclaimer

This project is for educational and data visualization purposes only.
All data was collected from books.toscrape.com
 — a public demo site for web scraping practice.

## 👨‍💻 Author

Developed by Eka Dwipayana
🔗 [View the deployed interactive dashboard](https://scrappingbookreviewwebpage.streamlit.app/)

🔗 [LinkedIn](https://www.linkedin.com/in/eka-dwipayana/)
