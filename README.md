# Do Uber Users Exploit the Booking System to Optimize Fares?

**An Exploratory Data Analysis (EDA) using R**

**Author:** Tlali Lemphane  
**Status:** Completed  
**Tools:** R (tidyverse, ggplot2)

---

## Background

Before the rise of ride-hailing platforms, urban transport in India relied heavily on taxis, auto-rickshaws, and informal pricing systems where bargaining, cash transactions, and personal trust were common.

Uber entered this environment promising price transparency, reliability, and predictability through algorithmic pricing and digital payments. This project explores how users interact with that system in practice, and whether traditional price-optimizing behaviors persist within a modern, platform-driven service.

---

## Project Objective

### Research Question
**Do Uber users exploit the Uber booking system to optimize fares?**

This exploratory data analysis investigates how urban commuter behavior manifests in ride-hailing usage, with a focus on:
- Price sensitivity  
- Ride cancellations  
- Payment method preferences  
- Reliability versus comfort trade-offs  

---

## Initial Assumptions

The analysis began with the following assumptions:

- **High price sensitivity**
  - Expected signal: Increased cancellations during surge pricing

- **Predominantly short-distance trips**
  - Expected signal: Majority of rides under 10 km

- **Persistence of “cash-era” psychology**
  - Expected signals:
    - Continued dominance of cash payments  
    - More customer-initiated cancellations than driver cancellations  
    - Repeated cancellations suggesting attempts to obtain lower fares or closer drivers  

- **Reliability prioritized over comfort**
  - Expected signal: Preference for standard vehicle categories over premium options

---

## Dataset

- **Source:** Uber Ride Analytics Dashboard (Kaggle)  
- **Geographic scope:** New Delhi  
- **License:** Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)

> ⚠️ Note: The dataset is anonymized and city-specific, limiting user-level tracking and generalizability.

---

## Key Findings (High-Level)

- No strong evidence of systematic fare exploitation by users
- Cancellation behavior appears situational rather than strategic
- Payment and vehicle choice patterns suggest convenience and reliability are prioritized
- Data limitations prevent definitive user-level behavioral conclusions

A detailed discussion is provided in the compiled EDA report.

---

## Repository Structure

├──  ncr_ride_bookings.csv

├── eda.Rmd

├── eda.html

└── README.md

---

## Conclusion

At the aggregate level represented in this dataset, Uber users appear to engage with the platform primarily as a reliable transportation service rather than as a system to be strategically exploited for fare optimization. While individual strategic behavior cannot be ruled out, no strong evidence of widespread exploitation is observed.

---

## Tools Used

- R for data cleaning, exploration, analysis, and visualization  
- R Markdown for reproducible reporting  

---

## Notes

This project was conducted as an exploratory analysis. Findings should be interpreted in light of dataset limitations and are not intended to generalize beyond the observed context.

**Full exploratory analysis:**

[View the rendered HTML report](https://lemphane.github.io/ride-hailing-behavior-eda/eda.html)

*(Includes all data cleaning steps, visualizaitons, and discussion)
