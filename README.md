# Forecasting Search Traffic with Prophet (MercadoLibre)

Acting as a growth analyst for MercadoLibre, Latin America's largest e-commerce company, this project analyzes hourly Google search traffic, relates it to stock price, and forecasts it with **Prophet**.

**Findings**
- Search traffic rose in May 2020, the month quarterly results came out (above the monthly median)
- Seasonality: traffic peaks around **midnight**, the busiest day is **Tuesday**, and the yearly low falls between **September and November**
- Lagged search traffic had only a weak, slightly negative correlation with next-hour stock volatility, so it isn't a strong trading signal

**Notebook:** `M8_Starter_Code/forecasting_net_prophet.ipynb`

**Tools:** Python, pandas, Prophet, matplotlib

*Coursework from the OSU AI Bootcamp.*
