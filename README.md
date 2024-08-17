# Investments Course Project - Portfolio Construction (Spring 2024)

This repository contains the code and report for the Investments course project at the College of Management of Technology at EPFL. The project focuses on constructing optimal portfolios using various financial strategies and analyzing their performance.

## Project Overview

This project involves constructing and analyzing portfolios by combining different financial signals such as beta, idiosyncratic volatility, and momentum. The analysis includes assessing the performance of these portfolios against standard risk factors and exploring industry-neutral portfolio construction.

## Project Structure

The project is structured as follows:

1. **Data Collection**: 
   - Monthly stock returns from January 1, 1964, to December 31, 2023, for all common stocks traded on the NYSE and AMEX.
   - Market data includes the equal-weighted CRSP market return and 1-month T-bill returns as a risk-free rate.
   - [data](https://drive.google.com/file/d/1xqkG6gVdUf6Fb92CANxuP5KmQ5ory84Z/view?usp=sharing)

2. **Strategies Implemented**:
   - **Betting against Beta (BaB)**: Constructing portfolios based on the market beta of stocks and analyzing their performance.
   - **Momentum Strategy (MoM)**: Building portfolios based on momentum, using 11-month lagged returns to predict future performance.
   - **Idiosyncratic Volatility (IV)**: Forming portfolios by sorting stocks based on their idiosyncratic volatility and assessing their performance.
   - **Optimal Fund Portfolio (STRAT)**: Combining BaB, MoM, and IV strategies to create a portfolio with a targeted volatility of 10%.

3. **Performance and Risk Analysis**:
   - Regression analysis of the fund strategy against Fama-French 5 factors and 12 industry portfolios.
   - Industry-neutral strategy construction and comparison with previous strategies.

## Authors

This project was completed by:

- Amirmahdi Hosseinabadi (372234)
- Valentin Aolaritei (368867)
- Ekaterina Borisova (370328)
- Alberto De Laurentis (369229)


Under the supervision of:
- **Professor**: Pierre Collin-Dufresne
- **Teaching Assistant**: Florian Perusset
