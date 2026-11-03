# Waste Collection & Recycling Analytics

## Project Overview

The **Waste Collection & Recycling Analytics** project is a Power BI-based data analytics project that explores waste generation, recycling performance, municipal efficiency, disposal methods, landfill capacity, and waste management costs across selected Indian cities and districts.

The dashboard transforms the dataset into interactive visual insights to help understand waste management patterns, compare recycling performance, and identify areas where operational improvements may be considered.

## Business Objectives

- Analyze waste generation across different waste categories and locations.
- Evaluate recycling rates across waste types and years.
- Compare municipal efficiency scores across cities and districts.
- Understand waste distribution by disposal method.
- Examine landfill capacity and waste management costs.
- Explore relationships between awareness campaigns and recycling performance.

## Dataset Information

**Dataset:** `Waste_Management_and_Recycling_India.csv`

| Dataset Attribute | Details |
|---|---:|
| Total Records | 850 |
| Total Columns | 13 |
| Cities / Districts | 34 |
| Waste Categories | 5 |
| Years Covered | 2019–2023 |
| Disposal Methods | 4 |
| Missing Values | 0 |
| Duplicate Rows | 0 |

### Key Dataset Fields

- City/District
- Waste Type
- Waste Generated (Tons/Day)
- Recycling Rate (%)
- Population Density (People/km²)
- Municipal Efficiency Score (1–10)
- Disposal Method
- Cost of Waste Management (₹/Ton)
- Awareness Campaigns Count
- Landfill Name
- Landfill Location (Lat, Long)
- Landfill Capacity (Tons)
- Year

## Key Performance Indicators (KPIs)

The Executive Dashboard includes five KPIs:

| KPI | Result |
|---|---:|
| Total Waste Generated | 4,472,912 |
| Average Recycling Rate | 57.08% |
| Average Municipal Efficiency Score | 7.40 |
| Total Records | 850 |
| Average Waste Management Cost | ₹2,778.46 |

**Calculation notes:**
- Total Waste Generated: Sum of the reported daily waste-generation values across all dataset records.
- Average Recycling Rate: Average of the recycling-rate percentages.
- Average Municipal Efficiency Score: Average score on a 1–10 scale.
- Total Records: Total number of dataset rows.
- Average Waste Management Cost: Average reported cost per ton.

*Note: Total Waste Generated represents the aggregate of reported daily values across records. It should not be interpreted as cumulative waste generated over the five-year period.*

## Dashboard Structure

The Power BI dashboard contains three pages and ten visualizations, in addition to five KPI cards.

### Page 1 – Waste Management Overview

- Total Waste Generated
- Average Recycling Rate
- Average Municipal Efficiency Score
- Total Records
- Average Waste Management Cost

### Page 2 – Recycling Performance

1. Average Waste Generation by Waste Type
2. Average Recycling Rate by Waste Type
3. Waste Distribution by Disposal Method
4. Average Recycling Rate by Year
5. Waste Generation vs Recycling Rate

### Page 3 – Location & Trends

1. Average Waste Generation by City/District
2. Average Municipal Efficiency by City/District
3. Average Waste Generation Trend by Year
4. Landfill Capacity by Landfill Name
5. Awareness Campaigns vs Recycling Rate

## Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization
- **Power Query** – Data inspection and preparation
- **DAX** – KPI calculations and measures
- **Microsoft Excel / CSV** – Dataset inspection and validation
- **GitHub** – Project documentation and version control

## Repository Structure

```text
waste-collection-and-recycling-analytics/
│
├── .gitignore
├── Executive_Dashboard.png
├── KPI_Calculations.docx
├── Recommendation_Justification.docx
├── WCRA1.pbix
├── Waste_Management_and_Recycling_India.csv
└── README.md
```

## Business Recommendations

The dashboard can support the following areas of investigation:

1. **Improve Recycling Performance:** Examine waste categories and locations with relatively lower recycling rates to identify potential improvement opportunities.
2. **Strengthen Waste Segregation:** Review disposal-method patterns to assess where better segregation and recycling processes may be useful.
3. **Monitor Municipal Efficiency:** Compare efficiency scores across locations to identify differences in reported performance.
4. **Review Landfill Capacity:** Monitor landfill capacity information when evaluating long-term waste-disposal planning.
5. **Evaluate Public Awareness:** Examine the relationship between awareness campaign counts and recycling rates to guide further investigation.

The detailed KPI calculations and recommendation justifications are available in the repository documents.

## Important Dataset Limitations

- The dataset does not contain a separate waste-collected quantity field. Therefore, actual collection efficiency cannot be calculated.
- The source authenticity of the dataset has not been independently verified. The dataset is used for analytics practice and should not be treated as an official municipal government dataset.
- Relationships shown in scatter charts indicate associations, not proof of causation.
- Recycling tonnage should not be estimated without confirming the denominator used to calculate the recycling rate.
- Landfill location coordinates have not been validated against the corresponding city names; therefore, geographic conclusions should not be drawn from them.

## How to Use This Project

1. Download or clone this repository.
2. Open `WCRA1.pbix` using Microsoft Power BI Desktop.
3. If Power BI requests the data source, connect it to `Waste_Management_and_Recycling_India.csv`.
4. Explore the three dashboard pages.
5. Refer to `KPI_Calculations.docx` for KPI formulas and explanations.
6. Refer to `Recommendation_Justification.docx` for the business reasoning behind the recommendations.

## Project Deliverables

| File | Description |
|---|---|
| `WCRA1.pbix` | Interactive Power BI dashboard |
| `Executive_Dashboard.png` | Executive dashboard screenshot |
| `Waste_Management_and_Recycling_India.csv` | Dataset |
| `KPI_Calculations.docx` | KPI calculations and explanations |
| `Recommendation_Justification.docx` | Business recommendation justifications |

## Author

**Yash Srivastava**  
MCA – Data Science  
Aspiring Data Analyst

**GitHub:** [yashjsri-hue](https://github.com/yashjsri-hue)

---

*This project was developed for data analytics practice and portfolio demonstration using Power BI.*