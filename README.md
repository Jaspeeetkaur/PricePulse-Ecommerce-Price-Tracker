# PricePulse-Ecommerce-Price-Tracker
A full-stack web app to track and compare Amazon product prices with visual graphs and AI-based comparison across platforms like Flipkart, Meesho, and BigBasket.
PricePulse – E-Commerce Price Tracker

Track Amazon product prices over time and get visual insights, alerts, and comparisons across platforms using AI.

🚀 Features

- Enter an Amazon product URL
- Automatically track price every 30–60 minutes
- Visualize price trends using Chart.js
- Optional: Compare same product across Flipkart, Meesho, etc.
- Optional: Email alert when price drops below your target

🛠 Tech Stack

- Frontend: HTML, JavaScript, Chart.js
- Backend: Python, Flask
- Database: SQLite
- Scraping: BeautifulSoup + Requests
- Scheduler: APScheduler / cron
- Deployment: Render / Railway / Vercel
- AI (Bonus): OpenAI / Gemini for product comparison

📂 Project Structure

- /static – CSS/JS files
- /templates – HTML files
- /scraper – Web scraping logic
- /db – Database schema and storage
- app.py – Main backend logic
- scheduler.py – Handles cron/APS scheduler
- README.md – Documentation

📈 How it Works

1. User submits an Amazon URL.
2. The backend fetches product details and price using scraping.
3. Every 30–60 mins, a scheduler updates the price and stores it.
4. The frontend shows a graph of price trends.
5. AI finds the same product on other platforms and compares prices.
6. Email alerts users when price drops below a threshold.

