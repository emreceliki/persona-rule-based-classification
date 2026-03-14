# Persona — Rule-Based Classification for Potential Customer Revenue Estimation

## Business Problem

A gaming company aims to create **level-based** customer definitions (personas) using customer characteristics and build segments from these personas to estimate **how much revenue** a new customer could generate on average.

**Example:** Estimating the average revenue from a 25-year-old male iOS user from Turkey.

## Dataset

`persona.csv` contains product prices from an international gaming company along with demographic information of the users who made those purchases. Each row represents an individual transaction — a user with the same demographic profile may have multiple purchases.

- **Observations:** 5,000
- **Features:** 5
- **Missing data:** None

## Features

| Feature | Description | Type | Unique Values |
|---------|-------------|------|---------------|
| `PRICE` | Amount spent by the customer | int | 9, 19, 29, 39, 49, 59 |
| `SOURCE` | Device type of the customer | str | android, ios |
| `SEX` | Gender of the customer | str | male, female |
| `COUNTRY` | Country of the customer | str | bra, tur, usa, can, deu, fra |
| `AGE` | Age of the customer | int | 15 – 66 |

