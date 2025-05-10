# 🦈 SharkTank India Data Analysis

An analysis of deals, investments, and trends from India's popular business reality show.

## 📊 Overview

This project analyzes Shark Tank India data across multiple seasons to uncover:
- Investment patterns by sharks (Namita, Vineeta, Anupam, Aman, Peyush, Amit, Ashneer)
- Success factors for pitches
- Industry trends and valuations
- Deal structures and negotiations

## 🔑 Key Features

- Deal analysis by industry and shark
- Visualization of investment patterns
- Success factor identification
- Valuation trends across seasons


## 📚 Data Dictionary

| Column Name                 | Description                                                     | Data Type | Example Values                       |
| --------------------------- | --------------------------------------------------------------- | --------- | ------------------------------------ |
| `Season Number`             | Season of Shark Tank                                            | Integer   | 1, 2, 3                              |
| `Startup Name`              | Name of the pitching company                                    | String    | BluArmor, Hammer & Mop               |
| `Episode Number`            | Episode within the season                                       | Integer   | 1, 2, 3                              |
| `Pitch Number`              | Sequence of the pitch in the episode                            | Integer   | 1, 2, 3                              |
| `Season Start`              | Season start date                                               | Date      | 2021-12-20                           |
| `Season End`                | Season end date                                                 | Date      | 2022-02-04                           |
| `Original Air Date`         | Air date of the episode                                         | Date      | 2021-12-20                           |
| `Episode Title`             | Title of the episode                                            | String    | "Season Premiere"                    |
| `Anchor`                    | Highlight or focus of the episode                               | String    | "First pitch of the season"          |
| `Industry`                  | Sector or category of the business                              | String    | Technology, Food & Beverage          |
| `Business Description`      | Short description of the startup                                | String    | "Smart helmet with cooling solution" |
| `Company Website`           | Website URL                                                     | String    | bluarmor.com                         |
| `Started in`                | Year the business was founded                                   | Integer   | 2016, 2019                           |
| `Number of Presenters`      | Total number of pitchers                                        | Integer   | 1, 2, 3                              |
| `Male Presenters`           | Number of male presenters                                       | Integer   | 0, 1, 2                              |
| `Female Presenters`         | Number of female presenters                                     | Integer   | 0, 1, 2                              |
| `Transgender Presenters`    | Number of transgender presenters                                | Integer   | 0, 1                                 |
| `Couple Presenters`         | Whether presenters are a couple                                 | Boolean   | True, False                          |
| `Pitchers Average Age`      | Average age of all presenters                                   | Float     | 28.5, 35.0                           |
| `Pitchers City`             | City of the business                                            | String    | Mumbai, Delhi                        |
| `Pitchers State`            | State of the business                                           | String    | Maharashtra, Karnataka               |
| `Yearly Revenue`            | Annual revenue in ₹                                             | Integer   | 5,000,000; 10,000,000                |
| `Monthly Sales`             | Monthly sales in ₹                                              | Integer   | 500,000; 1,000,000                   |
| `Gross Margin`              | Gross margin percentage                                         | Float     | 60.0, 75.5                           |
| `Net Margin`                | Net margin percentage                                           | Float     | 15.0, 25.0                           |
| `EBITDA`                    | Earnings before interest, taxes, depreciation, and amortization | Integer   | 1,000,000; 2,500,000                 |
| `Cash Burn`                 | Monthly cash burn in ₹                                          | Integer   | 200,000; 500,000                     |
| `SKUs`                      | Number of unique product types                                  | Integer   | 5, 12, 20                            |
| `Has Patents`               | Whether the business owns patents                               | Boolean   | True, False                          |
| `Bootstrapped`              | Whether the business is self-funded                             | Boolean   | True, False                          |
| `Original Ask Amount`       | Investment amount requested in ₹                                | Integer   | 10,000,000; 50,000,000               |
| `Original Offered Equity`   | Equity percentage offered by founders                           | Float     | 5.0, 10.0, 15.0                      |
| `Valuation Requested`       | Implied valuation from pitch                                    | Integer   | 100,000,000; 200,000,000             |
| `Received Offer`            | Whether the business received any offer                         | Boolean   | True, False                          |
| `Accepted Offer`            | Whether the entrepreneur accepted an offer                      | Boolean   | True, False                          |
| `Total Deal Amount`         | Final deal amount in ₹                                          | Integer   | 10,000,000; 30,000,000               |
| `Total Deal Equity`         | Final equity given in the deal                                  | Float     | 15.0, 25.0                           |
| `Total Deal Debt`           | Debt component of the deal in ₹                                 | Integer   | 0; 5,000,000                         |
| `Debt Interest`             | Interest rate on the debt                                       | Float     | 10.0, 12.0                           |
| `Deal Valuation`            | Final valuation based on deal terms                             | Integer   | 100,000,000; 150,000,000             |
| `Number of Sharks in Deal`  | Number of sharks involved in the deal                           | Integer   | 1, 2, 3                              |
| `Deal Has Conditions`       | Whether the deal includes conditions                            | Boolean   | True, False                          |
| `Royalty Deal`              | Whether the deal involves royalty                               | Boolean   | True, False                          |
| `Advisory Shares Equity`    | Equity offered for advisory role                                | Float     | 0.0, 2.0, 5.0                        |
| `Namita Investment Amount`  | Namita's investment amount in ₹                                 | Integer   | 0, 10,000,000                        |
| `Namita Investment Equity`  | Namita's equity share                                           | Float     | 0.0, 10.0, 15.0                      |
| `Namita Debt Amount`        | Namita's debt contribution in ₹                                 | Integer   | 0, 5,000,000                         |
| `Vineeta Investment Amount` | Vineeta's investment amount in ₹                                | Integer   | 0, 10,000,000                        |
| `Vineeta Investment Equity` | Vineeta's equity share                                          | Float     | 0.0, 10.0, 15.0                      |
| `Vineeta Debt Amount`       | Vineeta's debt contribution in ₹                                | Integer   | 0, 5,000,000                         |
| `Anupam Investment Amount`  | Anupam's investment amount in ₹                                 | Integer   | 0, 10,000,000                        |
| `Anupam Investment Equity`  | Anupam's equity share                                           | Float     | 0.0, 10.0, 15.0                      |
| `Anupam Debt Amount`        | Anupam's debt contribution in ₹                                 | Integer   | 0, 5,000,000                         |
| `Aman Investment Amount`    | Aman's investment amount in ₹                                   | Integer   | 0, 10,000,000                        |
| `Aman Investment Equity`    | Aman's equity share                                             | Float     | 0.0, 10.0, 15.0                      |
| `Aman Debt Amount`          | Aman's debt contribution in ₹                                   | Integer   | 0, 5,000,000                         |
| `Peyush Investment Amount`  | Peyush's investment amount in ₹                                 | Integer   | 0, 10,000,000                        |
| `Peyush Investment Equity`  | Peyush's equity share                                           | Float     | 0.0, 10.0, 15.0                      |
| `Peyush Debt Amount`        | Peyush's debt contribution in ₹                                 | Integer   | 0, 5,000,000                         |
| `Amit Investment Amount`    | Amit's investment amount in ₹                                   | Integer   | 0, 10,000,000                        |
| `Amit Investment Equity`    | Amit's equity share                                             | Float     | 0.0, 10.0, 15.0                      |
| `Amit Debt Amount`          | Amit's debt contribution in ₹                                   | Integer   | 0, 5,000,000                         |
| `Ashneer Investment Amount` | Ashneer's investment amount in ₹                                | Integer   | 0, 10,000,000                        |
| `Ashneer Investment Equity` | Ashneer's equity share                                          | Float     | 0.0, 10.0, 15.0                      |
| `Ashneer Debt Amount`       | Ashneer's debt contribution in ₹                                | Integer   | 0, 5,000,000                         |
| `Guest Investment Amount`   | Guest shark's investment amount in ₹                            | Integer   | 0, 10,000,000                        |
| `Guest Investment Equity`   | Guest shark's equity share                                      | Float     | 0.0, 10.0, 15.0                      |
| `Guest Debt Amount`         | Guest shark's debt contribution in ₹                            | Integer   | 0, 5,000,000                         |
| `Invested Guest Name`       | Name of guest shark who invested                                | String    | "Ghazal Alagh", "Ritesh Agarwal"     |
| `All Guest Names`           | All guest sharks in the episode                                 | String    | "Ghazal Alagh, Ritesh Agarwal"       |
| `Namita Present`            | Whether Namita was present                                      | Boolean   | True, False                          |
| `Vineeta Present`           | Whether Vineeta was present                                     | Boolean   | True, False                          |
| `Anupam Present`            | Whether Anupam was present                                      | Boolean   | True, False                          |
| `Aman Present`              | Whether Aman was present                                        | Boolean   | True, False                          |
| `Peyush Present`            | Whether Peyush was present                                      | Boolean   | True, False                          |
| `Amit Present`              | Whether Amit was present                                        | Boolean   | True, False                          |
| `Ashneer Present`           | Whether Ashneer was present                                     | Boolean   | True, False                          |
| `Guest Present`             | Whether a guest shark was present                               | Boolean   | True, False                          |ent | Boolean | True, False |
| `Amit Present` | Whether Amit was present | Boolean | True, False |
| `Ashneer Present` | Whether Ashneer was present | Boolean | True, False |
| `Guest Present` | Whether a guest shark was present | Boolean | True, False |

## 🚀 Getting Started

```bash
git clone https://github.com/YourUsername/SharkTankIndia.git
cd SharkTankIndia
# Install requirements and explore notebooks
```


*Inspired by the entrepreneurs who dare to dive into the tank!*