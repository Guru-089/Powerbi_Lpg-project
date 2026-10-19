# 🇮🇳 LPG Consumption Analysis Dashboard — India

An interactive **Power BI dashboard** for exploring LPG consumption across Indian states and over time. The project transforms consumption data into visual insights that support trend analysis, state-wise comparisons, and data-driven decision-making.

## 📌 Project Overview

Liquefied Petroleum Gas (LPG) is an important household fuel in India. Understanding how consumption changes over time and varies across states can help users explore regional patterns and identify areas for further analysis.

This project uses Microsoft Power BI to present LPG consumption data through interactive visuals and summary metrics.

## 🎯 Objectives

- Analyze LPG consumption trends across years.
- Compare consumption between Indian states.
- Summarize consumption using key metrics such as total, average, and maximum consumption.
- Present data through an interactive and easy-to-understand dashboard.
- Support exploratory analysis using Power BI visualizations and filters.

## ✨ Dashboard Features

- **Year-wise trend analysis:** Explore how LPG consumption changes over time.
- **State-wise comparison:** Compare LPG consumption across states.
- **KPI metrics:** View total, average, and maximum consumption measures.
- **Interactive visuals:** Explore patterns by interacting with report visuals and filters where configured.
- **Consumption trend chart:** The provided Power BI template includes a line and clustered column combination chart using Year, State, and LPG Consumption fields.

## 🧰 Tools & Technologies

- **Microsoft Power BI Desktop** — data modeling and visualization
- **Power Query** — data cleaning and transformation workflow
- **DAX** — measures and calculated metrics, where implemented
- **Power BI Template (`.pbit`)** — reusable report template

## 📁 Project Files

```text
LPG-Consumption-Analysis/
├── LPG PROJECT.pbit
└── README.md
```

> The `.pbit` file is a Power BI template. It contains report structure and configuration, but it may require the original data source to be connected when opened. Add screenshots or the source dataset to the repository if you want others to reproduce the full report.

## 🚀 How to Open the Dashboard

1. Install **Microsoft Power BI Desktop**.
2. Download or clone this repository.
3. Open `LPG PROJECT.pbit` in Power BI Desktop.
4. If prompted, connect the template to the required LPG consumption data source.
5. Review or update Power Query steps and data types if needed.
6. Select **Load** or **Apply changes** to load the data.
7. Explore the report visuals and save a working `.pbix` copy.

## 📊 Analysis Approach

1. **Data input:** Connect the LPG consumption dataset.
2. **Data preparation:** Review column names, data types, missing values, and consistency.
3. **Data modeling:** Use the relevant fields, including Year, State, and LPG Consumption.
4. **Metric analysis:** Calculate or review total, average, and maximum consumption metrics as configured in the report.
5. **Visualization:** Use trend charts, state comparisons, and KPI visuals to explore the data.
6. **Interpretation:** Identify patterns and differences, then validate conclusions against the underlying dataset.

## 📈 Expected Insights

The dashboard can be used to investigate questions such as:

- How does LPG consumption change from year to year?
- Which states report comparatively higher or lower consumption?
- Are there notable changes in consumption over the selected period?
- How do total, average, and maximum consumption compare for the available data?

Actual findings depend on the dataset connected to the template; this README does not assert specific state rankings or numerical results.

## 📷 Dashboard Preview

Add screenshots of your report here after opening it in Power BI Desktop.

```markdown
![LPG Consumption Dashboard](images/lpg-dashboard.png)
```

To use the preview, create an `images` folder in the repository, add a dashboard screenshot named `lpg-dashboard.png`, and keep the Markdown image path in sync with the filename.

## ⚠️ Notes

- This repository currently includes a `.pbit` template, not necessarily the original data file or a populated `.pbix` report.
- Data source paths, credentials, and refresh settings may need to be configured on another computer.
- KPI definitions and units should be checked against the dataset before publishing results.
- Do not upload confidential data, credentials, or restricted datasets to a public repository.

## 🔮 Future Improvements

- Add a clear dashboard overview page with key KPIs.
- Include more time-period and regional filters where the dataset supports them.
- Add documented DAX measures and data dictionary.
- Include a data source citation and update date.
- Add dashboard screenshots and a sample dataset when licensing permits.
- Publish the report through an appropriate Power BI sharing method, if applicable.

