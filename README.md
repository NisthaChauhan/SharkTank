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
| `Season Number` | Season of Shark Tank | Integer | 1, 2, 3 |
| `Startup Name` | Name of the pitching company | String | BluArmor, Hammer & Mop |
| `Episode Number` | Episode within the season | Integer | 1, 2, 3 |
| `Pitch Number` | Sequence of pitch in the episode | Integer | 1, 2, 3 |
| `Season Start` | Season start date | Date | 2021-12-20 |
| `Season End` | Season end date | Date | 2022-02-04 |
| `Original Air Date` | Date when episode was aired | Date | 2021-12-20 |
| `Episode Title` | Title of the episode | String | "Season Premiere" |
| `Anchor` | Main highlight of the episode | String | "First pitch of the season" |
| `Industry` | Business category | String | "Technology", "Food & Beverage" |
| `Business Description` | Brief description of business | String | "Smart helmet with cooling solution" |
| `Company Website` | Website URL | String | "bluarmor.com" |
| `Started in` | Year business was founded | Integer | 2016, 2019 |
| `Number of Presenters` | Count of pitchers | Integer | 1, 2, 3 |
| `Male Presenters` | Count of male presenters | Integer | 0, 1, 2 |
| `Female Presenters` | Count of female presenters | Integer | 0, 1, 2 |
| `Transgender Presenters` | Count of transgender presenters | Integer | 0, 1 |
| `Couple Presenters` | Whether presenters are a couple | Boolean | True, False |
| `Pitchers Average Age` | Average age of presenters | Float | 28.5, 35.0 |
| `Pitchers City` | City of business | String | "Mumbai", "Delhi" |
| `Pitchers State` | State of business | String | "Maharashtra", "Karnataka" |
| `Yearly Revenue` | Annual revenue (₹) | Integer | 5000000, 10000000 |
| `Monthly Sales` | Monthly sales (₹) | Integer | 500000, 1000000 |
| `Gross Margin` | Gross profit percentage | Float | 60.0, 75.5 |
| `Net Margin` | Net profit percentage | Float | 15.0, 25.0 |
| `EBITDA` | Earnings before interest, taxes, etc. | Integer | 1000000, 2500000 |
| `Cash Burn` | Monthly cash burn rate | Integer | 200000, 500000 |
| `SKUs` | Number of products/variations | Integer | 5, 12, 20 |
| `Has Patents` | Whether business has patents | Boolean | True, False |
| `Bootstrapped` | Self-funded without external investment | Boolean | True, False |
| `Original Ask Amount` | Investment requested (₹) | Integer | 10000000, 50000000 |
| `Original Offered Equity` | Equity percentage offered | Float | 5.0, 10.0, 15.0 |
| `Valuation Requested` | Implied business valuation | Integer | 100000000, 200000000 |
| `Received Offer` | Whether any shark made an offer | Boolean | True, False |
| `Accepted Offer` | Whether entrepreneur accepted an offer | Boolean | True, False |
| `Total Deal Amount` | Final investment amount (₹) | Integer | 10000000, 30000000 |
| `Total Deal Equity` | Final equity percentage | Float | 15.0, 25.0 |
| `Total Deal Debt` | Debt component of deal (₹) | Integer | 0, 5000000 |
| `Debt Interest` | Interest rate on debt | Float | 10.0, 12.0 |
| `Deal Valuation` | Final business valuation | Integer | 100000000, 150000000 |
| `Number of Sharks in Deal` | Count of investing sharks | Integer | 1, 2, 3 |
| `Deal Has Conditions` | Whether deal has conditions | Boolean | True, False |
| `Royalty Deal` | Whether deal includes royalties | Boolean | True, False |
| `Advisory Shares Equity` | Equity for advisory role | Float | 0.0, 2.0, 5.0 |
| `Namita Investment Amount` | Namita's investment (₹) | Integer | 0, 10000000 |
| `Namita Investment Equity` | Namita's equity percentage | Float | 0.0, 10.0, 15.0 |
| `Namita Debt Amount` | Namita's debt component (₹) | Integer | 0, 5000000 |
| `Vineeta Investment Amount` | Vineeta's investment (₹) | Integer | 0, 10000000 |
| `Vineeta Investment Equity` | Vineeta's equity percentage | Float | 0.0, 10.0, 15.0 |
| `Vineeta Debt Amount` | Vineeta's debt component (₹) | Integer | 0, 5000000 |
| `Anupam Investment Amount` | Anupam's investment (₹) | Integer | 0, 10000000 |
| `Anupam Investment Equity` | Anupam's equity percentage

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