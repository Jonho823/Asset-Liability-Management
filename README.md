## Introduction

This project delves into the principles of Asset Liability Management, drawing inspiration from the comprehensive content of the course provided by EDHEC Business School. Through the application of techniques learned, the aim is to demonstrate a nuanced understanding of dynamic risk budgeting and its practical applications in real-world investment contexts.

## Data

This project utilizes two primary datasets, each with distinct characteristics and sources:

**1. Monte Carlo Simulation for Bond Portfolio and Equity Portfolio**

Monte Carlo Simulation is employed to generate price sets for both bond and equity portfolios, with 5000 scenarios utilized. For the bond portfolio, a 10-year bond with a 3% initial coupon rate is assumed, utilizing the Cox-Ingersoll-Ross (CIR) model to simulate random interest rates and compute a series of bond prices based on interest rate fluctuations. Similarly, for the equity portfolio, assumed with an average return of 7% annually and a 15% volatility, the geometric Brownian motion is employed to simulate stock prices with these specified parameters.

**2. 30 Industry Portfolios**

The dataset was obtained from the Kenneth French website and contains monthly returns spanning from July 1926 to March 2024. Kenneth French classifies each stock listed on the NYSE, AMEX, and NASDAQ into industry portfolios based on their four-digit SIC code, resulting in a total of 30 industries represented in the dataset.

Data source: https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html

## Installation Instruction

1. Clone the project repository from GitHub.
2. Import the provided dataset file into `main.ipynb`.
3. Execute the code in `main.ipynb` with the use of `edhec_risk_kit.py` as a toolkit for portfolio optimization.

## Coding Contributions

[1] EDHEC Business School (2019) Investment Management with Python and Machine Learning Specialization. Coursera. https://www.coursera.org/learn/portfolio-optimization

## Disclaimer

The code in this repository is for educational purposes and is based on principles learned from the Portfolio Construction and Analysis with Python course provided by EDHEC Business School. It is intended to showcase the application of these principles and does not imply any affiliation with or endorsement by EDHEC Business School. All rights to the course content belong to EDHEC Business School.