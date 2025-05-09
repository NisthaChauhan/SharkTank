# 🦈 SharkTank Data Analysis Project 🦈

Welcome to the *fin-tastic* world of Shark Tank data analysis! This project dives deep into the tank to uncover the secrets behind successful pitches, shark behavior, and business trends.

## 🚀 Overview

Ever wondered what *really* makes the sharks bite? This repository contains a fun and insightful analysis of Shark Tank deals across multiple seasons of everyone's favorite business reality TV show. We're swimming through the data to reveal investment patterns, success factors, and what happens after entrepreneurs leave the tank!

## ✨ Features

- **Deal Analysis**: Find out which industries make the sharks open their wallets 💰
- **Shark Behavior**: Discover each shark's investment style (Is Mr. Wonderful really that wonderful?)
- **Success Factors**: Learn the secret sauce of successful pitches 🥫
- **Cool Visualizations**: Pretty charts that make data go "wow!" 📊
- **Prediction Model**: Our crystal ball for pitch success probability 🔮

## 📊 Dataset

Our analysis uses a treasure trove of Shark Tank episodes data, including:
- Company details and valuations
- Entrepreneur information 
- Deal terms and negotiations
- Which sharks jumped in (or out!)
- What happened after the show aired

## 📚 Data Dictionary

| Column Name | Description | Data Type | Example Values |
|-------------|-------------|-----------|---------------|
| `episode_id` | Episode identifier | String | S01E01, S12E15 |
| `company_name` | Name of the company | String | Scrub Daddy, Ring |
| `industry` | Business category | String | Food & Beverage, Tech, Fashion |
| `entrepreneur` | Entrepreneur name(s) | String | John Smith, Jane Doe |
| `ask_amount` | Amount requested ($) | Integer | 50000, 150000 |
| `ask_equity` | Equity offered (%) | Float | 10.0, 25.5 |
| `valuation` | Company valuation ($) | Integer | 500000, 1000000 |
| `deal_made` | Whether a deal was made | Boolean | True, False |
| `shark_investor` | Shark(s) who invested | String | Mark Cuban, Lori Greiner |
| `deal_amount` | Final investment amount ($) | Integer | 60000, 125000 |
| `deal_equity` | Final equity given (%) | Float | 15.0, 30.0 |
| `deal_debt` | Debt financing offered ($) | Integer | 0, 50000 |
| `deal_royalty` | Royalty terms if applicable | String | $1 per unit, 5% revenue |
| `pitch_duration` | Length of pitch (minutes) | Integer | 15, 45 |
| `post_show_success` | Success after the show | String | Operating, Acquired, Failed |
| `annual_revenue` | Annual revenue at time of pitch ($) | Integer | 100000, 500000 |
| `patent_status` | Patent information | String | None, Pending, Granted |
| `location` | Business location | String | Austin TX, New York NY |
| `episode_date` | Air date of episode | Date | 2014-05-16, 2020-11-20 |

## 🏁 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook/Lab
- A curious mind and love for business pitches!

### Quick Start

1. Clone this repo and dive right in!
   ```bash
   git clone https://github.com/NisthaChauhan/SharkTank.git
   cd SharkTank
   ```

2. Start exploring the notebooks to uncover shark secrets! 🕵️‍♀️

## 🔮 Future Work

- Add more recent seasons (Mr. Wonderful's getting nicer with age - we need to track this!)
- Analyze social media buzz after episodes air
- Build a "Shark Predictor" - which shark will bite on your idea?
- Create a fun quiz: "Would Your Business Survive the Tank?"

So grab your swim trunks and dive in! This data lake is full of insights just waiting to be discovered! 🏊‍♂️