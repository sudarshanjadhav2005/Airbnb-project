![Stunning Paris Airbnb](https://www.smarthouse.com.au/wp-content/uploads/2024/03/image-airbnb-scaled-1.jpg)
# 🏠Airbnb-project

## 🎯Overview

This project analyzes the impact of regulations on the Airbnb market in Paris, focusing on how host participation, pricing, and locality-level dynamics evolved over time. Using listing and review datasets from Airbnb, the study explores trends in affordability, distribution of prices across neighborhoods, and how policy interventions reshaped supply and demand.


## 📊Key Objectives
Assess Airbnb supply and host participation trends in Paris.
Evaluate the impact of regulation on new host entries and listing activity.
Explore pricing dynamics, including distribution, affordability, and shifts over time.
Compare neighbourhood-level average prices to understand premium vs. budget areas.
Generate business insights for hosts, customers, and policymakers.

## 🚀Quick Summary of Findings
Strong growth pre-2017: Rapid expansion of listings with competitive pricing.
Regulation slowdown (2017 onward): Noticeable dip in new host entries, with supply growth stabilizing.
Demand resilience: Despite supply restrictions, customer demand and occupancy remained steady.
Pricing patterns: Competition pre-2017 kept prices moderate; post-regulation, supply constraints drove price increases in popular neighbourhoods.
Locality insights: Central Paris remains premium, while outer arrondissements attract budget-conscious travelers.

## 🛠️Tech Stack
Python (pandas, numpy): Data cleaning & processing
Matplotlib / Seaborn: Data visualization
Scipy / Statsmodels (optional): Statistical analysis
Jupyter Notebook: Interactive analysis

## 📂Repo Structure
├── data/
│   ├── raw/                # Original Airbnb listings & reviews datasets
│   ├── cleaned/            # Processed/filtered datasets for Paris
├── notebooks/
│   ├── airbnb-impact-of-regulation.ipynb
├── images/                 # Visualizations (price distributions, neighbourhood insights)
├── requirements.txt        # Python dependencies
├── README.md               # Project overview
├── LICENSE                 # MIT License

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
