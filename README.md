Data Science Project: School Milk Bid Rigging Analysis

📌 Project Overview
This project involves a detailed investigation into potential bid rigging and market manipulation within the school milk supply contracts in Kentucky, USA. As a Data Scientist, the objective is to analyze historical bidding data to identify anti-competitive patterns between two major suppliers, Meyer and Trauth, particularly within the "tri-county" region.
+2

📊 Dataset Description
The dataset consists of 392 observations covering a 9-year period. It includes both quantitative and qualitative variables to analyze market behavior:
+2


YEAR: The year the milk supply contract was signed.


MARKET: Market area (TRI-COUNTY vs. SURROUND).


WINNER: The name of the winning milk vendor.


WWBID, LFWBID, LFCBID: Winning bid prices for whole milk, low-fat white milk, and low-fat chocolate milk.
+2


KYFMO: Raw milk floor price regulated by FMO (Input Cost).


MILESM / MILEST: Distance from Meyer and Trauth processing plants to the school district.

🔍 Analytical Tasks
The analysis is structured around Exploratory Data Analysis (EDA) and Statistical Modeling:


Market Share Analysis: Calculating and visualizing the market share of Meyer and Trauth from 1983 to 1991 to detect collusive patterns.


Incumbency Rate: Evaluating the contract retention rate in the tri-county area versus surrounding areas.


Bid Dispersion: Using Standard Deviation to assess if price variance aligns with a competitive or rigged market.


Price Trend Analysis: Comparing average winning prices across different regions over time.


Regression Analysis: Modeling the relationship between input costs (raw milk prices) and winning bids to identify economic anomalies.

🛠 Tech Stack
Language: Python


Libraries: Pandas (Data Manipulation), Matplotlib/Seaborn (Data Visualization), Scikit-learn/Statsmodels (Regression Analysis).

💡 Key Findings & Goals
The project aims to provide data-driven evidence regarding:

Abnormalities in winning bid prices and market share distribution.

Correlation (or lack thereof) between bid prices and transportation distances/input costs.

Actionable insights for legal or management teams to mitigate procurement risks.
