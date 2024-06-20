# PriceWise: Amazon Price Tracker

## Project Overview
PriceWise is a comprehensive Amazon price tracking application designed to help users stay informed about product price fluctuations and stock status in real-time. Built with a modern tech stack, PriceWise automates the web scraping process and sends timely email notifications to users.

## Features
- **Dynamic User Interface:** Developed with Next.js, Tailwind CSS, and Headless UI for a responsive and visually appealing experience.
- **Automated Web Scraping:** Utilized Bright Data and Cheerio to periodically scrape product data from Amazon.
- **Real-Time Data Updates:** Automated cron jobs ensure the latest data is always available.
- **Email Notifications:** Integrated Nodemailer and SendGrid for reliable email alerts on price drops and stock changes.
- **Scalable Data Management:** Leveraged MongoDB for robust storage and efficient retrieval of product and user data.

## Tech Stack
- **Frontend:**
  - Next.js
  - Tailwind CSS
  - Headless UI
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - MongoDB
- **Web Scraping:**
  - Bright Data
  - Cheerio
- **Automation:**
  - Node-cron
- **Email Notifications:**
  - Nodemailer
  - SendGrid

## Installation and Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/pricewise.git
   cd pricewise
