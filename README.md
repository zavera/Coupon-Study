# Coupon Acceptance Analysis

This project analyzes a dataset from the UCI Machine Learning repository to
explore the factors influencing customer acceptance of driving coupons.
The dataset was collected via a survey on Amazon Mechanical Turk and describes
different driving scenarios, including destination, time, weather, passenger, etc., asking
whether the user would accept the coupon.

## Overview

The goal is to identify differences between customers who accepted coupons and those who did not,
utilizing visualizations and probability distributions.
This analysis aims to determine which factors make a driver more likely to accept a coupon once it is delivered.

## Files

*   `coupons.csv`: The dataset used for analysis.
*   `prompt-2.ipynb`: Jupyter Notebook containing the data analysis and visualizations.

## How to View the Analysis

The complete analysis, including code and visualizations, can be viewed in this Jupyter Notebook:

[https://nbviewer.org/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/prompt-2.ipynb](https://nbviewer.org/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/prompt-2.ipynb)

## Findings

A detailed analysis is performed to study the usage for two types of coupons - Bar and Restaurants<20 (cheap
restaurants). The study shows that different factors affect utility of each type of coupon.
Bar coupons are used by drivers that have prior habit of visiting bar frequently in the last month. However the
driver is likely to use the coupon if the passenger is not a kid . On the other hand drivers likely to use
Restaurant<20 type coupon are motivated by standard meal times ,weather conditions and destination of a non-urgent
type . This pattern implies that different coupon type has maximum usability under very different conditions.This
data can be leveraged by restaurants to expand their client base.

## Author

Ambreen Zaver
