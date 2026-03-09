Climate Risk Exposure Analysis for Investment Portfolios
Overview

This project analyzes the climate risk exposure of an investment portfolio by combining portfolio allocation data with sector-level carbon intensity metrics. Using Python, the analysis estimates portfolio carbon exposure, identifies high-emission sectors, and evaluates how portfolio rebalancing can reduce climate-related risk.

The project demonstrates how climate and ESG data can be integrated into portfolio risk analysis to support more sustainable investment decisions.

Project Background

Climate change is increasingly recognized as a financial risk factor for investors and financial institutions. Carbon-intensive sectors such as Energy, Utilities, and Materials may face growing regulatory pressure, carbon pricing policies, and transition risks as the global economy moves toward lower-carbon energy systems.

As a result, portfolio managers and risk analysts are increasingly incorporating climate-related metrics into investment analysis.

This project demonstrates how portfolio data can be combined with sector-level carbon intensity information to estimate portfolio-level climate exposure and identify key risk drivers.

Project Objectives

The objectives of this analysis are to:

Estimate the carbon exposure of an investment portfolio

Identify sectors and holdings contributing most to climate risk

Calculate weighted carbon exposure based on portfolio allocation

Visualize how carbon exposure is distributed across sectors

Evaluate how portfolio rebalancing can reduce climate-related risk

Demonstrate how climate data can support risk-aware investment decisions

Dataset Description

The analysis uses two datasets:

Portfolio Dataset

A simulated investment portfolio containing 25 holdings across multiple sectors.

Columns include:

Column	Description
company	Name of the company
sector	Industry sector classification
portfolio_weight	Portfolio allocation weight
Sector Emissions Dataset

Sector-level carbon intensity values used to approximate relative emissions levels.

Column	Description
sector	Industry sector
carbon_intensity	Estimated carbon intensity level

These values represent simplified sector emission proxies used for portfolio climate risk analysis.

Methodology

The analysis follows these steps:

Load portfolio and sector emissions datasets

Merge portfolio data with sector carbon intensity metrics

Calculate weighted carbon exposure for each holding

Aggregate exposure by sector and company

Visualize portfolio climate risk distribution

Perform scenario analysis with a rebalanced portfolio

Simulate carbon price stress testing

Key Formula

Weighted Carbon Exposure:

Weighted Carbon Exposure = Portfolio Weight × Sector Carbon Intensity

Portfolio Carbon Cost under Carbon Pricing Scenario:

Carbon Cost = Weighted Carbon Exposure × Carbon Price
Key Insights

Key findings from the analysis include:

Carbon exposure is highly concentrated in Energy and Utilities sectors

Technology and Financial sectors contribute significantly less to total carbon exposure

A rebalanced portfolio allocation toward lower-carbon sectors can significantly reduce overall climate risk

Under a carbon pricing scenario, high-emission sectors face the largest potential cost impacts

Tools and Technologies

Python

Pandas

Matplotlib

Jupyter Notebook

Project Structure
climate-risk-portfolio-analysis
│
├── data
│   ├── portfolio_data.csv
│   └── sector_emissions.csv
│
├── notebook
│   └── climate_risk_portfolio_analysis.ipynb
│
├── images
│   ├── sector_exposure_chart.png
│   ├── portfolio_allocation.png
│   └── exposure_comparison.png
│
└── README.md
Conclusion

This project demonstrates how climate-related data can be incorporated into portfolio risk analysis. By linking portfolio allocation with sector-level carbon intensity metrics, investors can better understand their exposure to climate-related risks and explore strategies to reduce carbon exposure through portfolio rebalancing.

Author
Sara Seyda Yenigun
Financial Data Analyst & ML Engineer | Risk & Credit Analytics | Python • SQL • BI | AI-Driven Financial Systems
