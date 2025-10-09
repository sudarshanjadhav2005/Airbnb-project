![Stunning Paris Airbnb](https://i.ytimg.com/vi/kNdMA4LXhSA/hq720.jpg?sqp=-oaymwEXCK4FEIIDSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLCW3ZZcC8bABmib3FhTQNzooyd3cA)
# 🏠Airbnb-project

# 🏠 Airbnb Paris Analysis

This project explores the evolution of the Airbnb market in Paris, focusing on how regulations, locality trends, and pricing dynamics have influenced both **host participation** and **customer demand**.

The analysis covers **data cleaning, exploratory data analysis (EDA), and insights generation** with clear visualizations and business recommendations.

---

## 📌 Objectives

* Understand Airbnb supply trends in Paris (2008–2021).
* Analyze the impact of the **2017 rental regulations** on host participation.
* Explore **locality-wise pricing patterns** and affordability.
* Study the relationship between **accommodation capacity** and average price.
* Provide **business insights & recommendations** for stakeholders.

---

## 📊 Key Insights

* **Rapid Growth (2008–2016):** Strong host entry and expansion of listings.
* **Regulatory Shift (2017):** Significant slowdown in new hosts entering the market.
* **Resilient Demand:** Despite fewer new listings, customer demand stayed stable.
* **Pricing Trends:** Competition lowered prices pre-2017, but post-regulation supply constraints pushed prices upward.
* **Locality Insights:** Central Paris commands premium prices, while outer neighborhoods attract budget travelers.

---

## 🚀 Recommendations

* Focus on **premium central areas** while maintaining offerings in budget-friendly neighborhoods.
* Implement **dynamic pricing** to balance supply-demand fluctuations.
* Diversify listings, especially targeting **medium-capacity stays (3–6 guests)**.
* Strengthen **customer experience** with quality listings and repeat-stay strategies.
* Stay compliant and adapt to evolving **local regulations** for long-term sustainability.

---

## 🛠️ Tech Stack

* **Python** (pandas, numpy) – Data cleaning & processing
* **Matplotlib / Seaborn** – Data visualization
* **Jupyter Notebook** – Interactive analysis

---

## 📂 Project Structure

```
├── data/                  # Raw & cleaned datasets
├── notebooks/             # Jupyter notebooks
├── images/                # Visualizations exported from notebooks
├── requirements.txt       # Dependencies
├── LICENSE                # License file (MIT)
├── README.md              # Project overview (this file)
```

Dataset link - (https://www.kaggle.com/datasets/mysarahmadbhat/airbnb-listings-reviews)


# Here are some key visualizations from the analysis:

* **Growth of Airbnb Listings in Paris**
  ![Listings Growth](https://github.com/sudarshanjadhav2005/Airbnb-project/blob/main/image/listings_growth.png)

* **Average Price by Locality**
  ![Price by Locality](https://github.com/sudarshanjadhav2005/Airbnb-project/blob/main/image/price_locality.png)

* **Impact of 2017 Regulation on Host Entries**
  ![Regulation Impact](https://github.com/sudarshanjadhav2005/Airbnb-project/blob/main/image/regulation_impact.png)

## 📊Results

The analysis produced several insights into the Paris Airbnb market and the effect of regulations:

📈 Market Growth & Regulation Impact
2008–2016: Strong upward growth in the number of hosts and listings, fueled by rising tourism and market attractiveness.
2017 Regulation Shift: Introduction of stricter rental policies led to a noticeable slowdown in new host entries. Growth stabilized, but demand continued to hold steady.

💶 Pricing Trends
Pre-2017: Competitive environment pushed prices down in many categories, improving affordability.
Post-2017: Supply constraints and regulation compliance led to higher average prices, especially in high-demand neighbourhoods.

🏙️ Locality Insights
Central Paris (1st–7th arrondissements): Premium zones commanding significantly higher nightly rates.
Outer neighbourhoods: More affordable, attracting long-stay guests and budget-conscious travelers.

👥 Capacity vs. Pricing
Small units (1–2 guests): Most common, with high competition and moderate pricing.
Medium capacity (3–6 guests): Balanced segment with strong demand and attractive revenue potential.
Large capacity (7+ guests): Less common, higher variability in pricing.

📊 Key Visualizations
Growth of Airbnb listings in Paris (2008–2021)
Price distribution (boxplot, histogram, KDE)
Average price by neighbourhood
Regulation impact on host participation

## 👉Reproducibility & Notes
All analysis is contained in the Jupyter notebook airbnb-impact-of-regulation.ipynb.
The environment requires Python 3.8+ with packages listed in requirements.txt.
Random seeds (where applicable) are set for reproducibility of sampling or statistical checks.
The datasets used come from publicly available Airbnb data snapshots on Kaggle / Inside Airbnb. Ensure you have the same raw snapshot for consistent results.

## 🚀Future Work
Extend the study to cross-city comparisons (e.g., Paris vs. Berlin, Amsterdam, London).
Add time-series forecasting (e.g., ARIMA, Prophet) to predict pricing and demand.
Build an interactive dashboard (Plotly Dash, Power BI, or Tableau) for stakeholders.
Incorporate geospatial analysis with geopandas to visualize neighbourhood trends in detail.
Run counterfactual simulations to estimate market behaviour without regulation.

## 👉Contributing

Contributions are welcome! 🚀
You can help improve this project by:

Adding enhanced data-cleaning scripts or validation checks
Improving visualizations (e.g., interactive dashboards)
Extending analysis with predictive modelling
Providing clearer documentation or additional insights

To contribute:

Fork this repository
Create a feature branch (git checkout -b feature-name)
Commit changes and push (git push origin feature-name)
Open a Pull Request  

## 🙌Acknowledgements
Inside Airbnb and Kaggle datasets for providing the listing and review data used in this project.
Paris city housing regulations & policy reports for regulatory context.
Open-source Python community for libraries that made this analysis possible.
