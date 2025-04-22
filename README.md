# Puppeteer Scraper + Flask Host (Multi-Stage Docker)

This project demonstrates a multi-stage Docker build that:
- Scrapes a website using Node.js and Puppeteer
- Hosts the scraped data via a Python Flask app

## 🔧 Build the Docker Image

```bash
docker build --build-arg SCRAPE_URL="https://example.com" -t scraper-flask-app .

