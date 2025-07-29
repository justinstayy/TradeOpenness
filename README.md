#The Impact of Trade Openness on Inflation in European Countries (2000–2021)

This project investigates the relationship between trade openness and inflation across 20 European countries using panel data from 2000 to 2021. The research explores whether increased integration into global trade—measured as the ratio of total trade (exports + imports) to GDP—has a significant effect on domestic inflation rates.

The analysis is grounded in economic theory (New Trade Theory, Phillips Curve models) and supported by an extensive literature review. Key macroeconomic variables such as GDP growth, foreign direct investment (FDI), government consumption, and exchange rates are included as controls. The dataset is compiled from World Bank and IMF sources and processed using Python (pandas, seaborn, linearmodels).

The core methodology involves estimating fixed effects panel regression models with clustered standard errors. Additional model refinements include lagged variables, Eurozone dummies, and robustness checks (e.g. excluding outliers, testing different clustering levels). Diagnostic tests confirm the reliability of the regression results.

Key Findings:
	•	Lagged inflation is the dominant predictor of current inflation, confirming inertia in European price dynamics.
	•	Trade openness has a weak and statistically insignificant direct effect on inflation once other macroeconomic controls are included.
	•	Model fit is strong, with adjusted R² values above 0.83 and further improvement when outlier countries are excluded.

The codebase includes the full empirical workflow: data import, reshaping, exploratory analysis, regression estimation, and diagnostic testing.

⸻

Let me know if you’d like a shorter version, or if you want it split into separate sections like “Background,” “Methodology,” “Results,” and “Tools Used.”
