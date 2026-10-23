# 🇿🇦 SA Household Economic Simulator

### Explore how macroeconomic changes can affect South African household finances.

The **SA Household Economic Simulator** is an interactive web-based tool that explores how changes in interest rates and global crude oil prices can influence borrowing costs, petrol prices, inflation and monthly household budgets.

By adjusting economic assumptions and switching between household scenarios, users can explore the potential financial pressures associated with changing macroeconomic conditions in South Africa.

The project aims to make economic relationships easier to understand through interactive visualisation and scenario-based exploration.

---

## ✨ Features

- **🏠 Household scenario comparison:** Switch between a low-income household model based on the National Minimum Wage (NMW) and a middle-income household model with a bond repayment.
- **📈 Interactive repo-rate control:** Adjust the South African Reserve Bank (SARB) repo rate to explore its modelled effects on the prime lending rate, borrowing costs and household affordability.
- **🛢️ Brent crude oil price control:** Change the assumed international oil price and examine its modelled effect on inland 95-octane petrol prices, transport costs and inflation.
- **📊 Economic indicator dashboard:** View key indicators, including the prime rate, petrol price, headline Consumer Price Index (CPI) and net monthly household balance.
- **💰 Household budget analysis:** Explore the relationship between assumed household income and essential expenses.
- **📉 Interactive data visualisation:** Examine changes in household finances through a dynamic chart.
- **🌗 Light and dark appearance:** Supports light and dark themes, including system colour-scheme preferences.
- **🌐 Browser-based experience:** Runs as a web page without requiring a traditional application installation.

## 🚀 Try the simulator

**Live demo:** https://rmngqibisa.github.io/SA-Household-Economic-Simulator/

Explore different scenarios, adjust the controls and consider how changes in the economic environment could affect households differently.

## 🧮 What can you explore?

| Indicator | What it represents |
|---|---|
| Repo rate | The assumed SARB policy interest rate |
| Prime rate | The modelled prime lending rate derived from the repo rate |
| Brent crude | The assumed international crude oil price in US dollars per barrel |
| Inland 95 petrol | The modelled petrol price in South African rand per litre |
| Headline CPI | The model's projected inflation indicator |
| Net monthly balance | Estimated household income less the modelled essential expenses |

### Household scenarios

**1. Low-income household**

Uses a monthly income assumption based on the National Minimum Wage displayed in the simulator. The model includes food, transport and utilities as essential expenses.

**2. Middle-income household**

Uses a monthly income assumption of R32,000 and includes food, transport, utilities and a bond repayment that varies with the modelled repo rate.

These scenarios are simplified representations intended to facilitate comparison. They do not represent every South African household or its individual financial circumstances.

## ⚙️ How it works

The simulator uses predefined assumptions and mathematical relationships to recalculate the displayed indicators when users change the controls.

The current model includes the following relationships:

- **Prime rate:** Calculated as the repo rate plus 3.50 percentage points.
- **Petrol price:** Estimated using a baseline price, the assumed Brent crude price and a fixed USD/ZAR exchange-rate assumption.
- **Inflation:** Estimated using a simplified relationship with Brent crude prices and the repo rate.
- **Household balance:** Calculated by subtracting the modelled essential expenses from the assumed household income.

The model also applies scenario-specific expense assumptions to calculate the resulting monthly balance.

These calculations are deliberately simplified for interactive exploration. They are not a complete macroeconomic forecasting system, and their relationships should not be interpreted as proof of causation.

## 🎯 Project objectives

This project is intended to:

- Make economic concepts more accessible to the public.
- Demonstrate how selected macroeconomic variables interact within a simplified household budget model.
- Encourage critical thinking about the cost of living and household affordability.
- Support discussion, education and economic awareness through interactive experimentation.
- Provide a foundation for future improvements to economic modelling and visualisation.

## ⚠️ Important disclaimer

**This simulator is for educational and illustrative purposes only.**

The results are estimates generated from predefined assumptions and simplified formulas. They are not official forecasts, live economic data, personalised financial advice or guaranteed predictions of future prices, inflation, interest rates or household outcomes.

The model's default values and assumptions may not reflect current market conditions or official statistics. Users should verify relevant information against authoritative sources, including the [South African Reserve Bank](https://www.resbank.co.za/), [Statistics South Africa](https://www.statssa.gov.za/) and the [Department of Mineral and Petroleum Resources](https://www.dmpr.gov.za/).

## 🤝 Contributing

Contributions, suggestions and constructive feedback are welcome.

Potential areas for improvement include:

- Refining the economic assumptions and documenting their sources.
- Introducing configurable household income and expense categories.
- Incorporating verified economic data and clearly identified update dates.
- Improving accessibility, mobile usability and visualisation.
- Adding further household scenarios and sensitivity analyses.
- Introducing tests to validate calculations and prevent regressions.

To contribute:

1. Fork the repository.
2. Create a branch for your proposed change.
3. Commit your improvements.
4. Submit a pull request describing the change and its purpose.

Please explain any changes to the model's formulas, assumptions or data sources so that results remain transparent and reproducible.

## 📄 Licence

No licence has been specified yet.

Before reusing, modifying or redistributing this project, check the repository's licensing status. If you intend to publish it as an open-source project, consider adding an appropriate licence file.

---

**Built to encourage curiosity, economic awareness and informed discussion about the financial pressures facing South African households.**

If you find the simulator useful, consider sharing it, providing feedback or contributing to its development.
