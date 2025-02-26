# 📚 BooksToScrape - Web Scraping & Data Cleaning Project  

## 📌 Project Overview  
This project involves **scraping book data** from [BooksToScrape](http://books.toscrape.com/), **cleaning the data**, and performing basic **data analysis**.  

## 🔧 Technologies Used  
- **Python** (BeautifulSoup, pandas)  
- **Data Cleaning & Transformation** (pandas)  
- **Data Storage** (CSV)  

## 📂 Data Pipeline  
1️⃣ **Web Scraping**  
- Extracted **book title, price, availability, and star rating** using **BeautifulSoup**.  

2️⃣ **Data Cleaning**  
- Removed **£ sign** from prices and converted them to numeric values.  
- Extracted the **exact stock count** from availability text.  
- Converted **star ratings** from words (e.g., "Three") to numbers (e.g., `3`).  

3️⃣ **Final Analysis**  
- Added a **new column for discounted prices** (10% discount on each book).  
- Calculated **average book price**.  
- Counted **books that are "In Stock" vs. "Out of Stock"**.  

4️⃣ **Data Export**  
- The cleaned dataset was saved as **`books_cleaned.csv`**. 
