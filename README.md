# Zenix Search

A fast, private, and lightweight custom search engine featuring a Google-style AI Overview card. Powered by Cloudflare Workers on the edge and deployed on Netlify.

---

## Features

- **Private & Secure:** Search queries are processed without tracking cookies, history logs, or third-party ads.
- **Serverless Edge Backend:** Powered by Cloudflare Workers for sub-second response times and secure hidden link indexing.
- **AI Overview:** Summarizes key highlights for queried entities and matched developer documentation.
- **Responsive UI:** Clean dark-mode interface built with vanilla HTML, CSS, and JavaScript, optimized for both mobile and desktop.
- **Curated Results:** Instantly searches personal social handles, portfolios, and key developer resources (MDN, Python, W3Schools).

---

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Hosting:** Netlify
- **Backend / API:** Cloudflare Workers (Serverless JavaScript runtime)
- **Data Source:** Inverted in-memory JSON index hosted on Cloudflare Edge

---

## Project Structure

```text
zenix-search/
├── index.html       # Frontend interface and API fetch logic
└── README.md        # Project documentation
