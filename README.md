# Dubizzle Property Scraper

A Python-based web scraper for extracting property listings from [Dubizzle Egypt](https://www.dubizzle.com.eg/), including location, price, beds, baths, area, seller name, and phone number. The results are saved into a CSV file for analysis.

---

## Features

- Scrapes listing cards on Dubizzle property search pages.
- Extracts:
  - Location
  - Short description
  - Price
  - Number of beds
  - Number of baths
  - Area in SQM
  - Seller name
  - Phone number
- Opens detail pages in new tabs to get seller and phone info.
- Saves all scraped data to a CSV file (`dubizzle_listings.csv`).

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/dubizzle-scraper.git
cd dubizzle-scraper

pip install selenium webdriver-manager pandas

