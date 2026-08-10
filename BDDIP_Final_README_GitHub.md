# Bihar District Intelligence & Recommendation System

## Power BI Portfolio Project

**Author:** Prashant Kumar  
**Project Type:** Power BI Data Analytics & Business Intelligence  
**Domain:** District-level development intelligence  
**Geographic Scope:** Bihar, India  
**Last Updated:** August 2026

---

## 📌 Project Overview

The **Bihar District Intelligence & Recommendation System** is an interactive Power BI portfolio project designed to provide district-level insights across four major development areas:

- Population
- Agriculture
- Education
- Rainfall

The project combines multiple datasets into an integrated analytical model and presents the results through interactive dashboards that can support data-driven development planning and district-level decision-making.

---

## 🎯 Project Objective

The primary objective is to create a centralized district intelligence dashboard for Bihar by integrating population, agriculture, education, and rainfall information.

The dashboard supports:

- District-level comparison
- Identification of high- and low-performing districts
- Agricultural production and yield analysis
- Education infrastructure analysis
- Rainfall and deviation analysis
- District-specific profile analysis
- Interactive exploration through slicers and navigation buttons

---

## 📊 Dashboard Pages

### 1. Home

The Home page acts as the project landing page and provides:

- Project overview
- Data source summary
- Navigation buttons
- Project ownership and update information

![Home Dashboard](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2826%29.png)

---

### 2. Executive Dashboard

Provides a high-level overview of Bihar using KPIs and comparative visuals.

Key analysis includes:

- Total population
- Average literacy rate
- Total agricultural production
- Average crop yield
- Total schools
- Average actual rainfall
- Most populated districts
- Most densely populated districts
- Literacy rate versus population
- Bihar district population map

![Executive Dashboard](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2827%29.png)

---

### 3. Agriculture Intelligence

Provides district-wise and crop-wise agricultural analysis.

Key analysis includes:

- Crop count
- Total agricultural area
- Total production
- Average yield rate
- Production by district
- Production by crop
- Production trend by year
- Yield comparison across Bihar divisions
- Interactive crop selection

![Agriculture Intelligence](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2828%29.png)

---

### 4. Education Intelligence

Analyzes education infrastructure and teacher availability across Bihar districts.

Key analysis includes:

- Total schools
- Total teachers
- Primary schools
- Upper-primary schools
- Top districts by schools
- Top districts by teachers
- Schools versus teachers relationship
- Year-based filtering
- District-based filtering

![Education Intelligence](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2829%29.png)

---

### 5. Rainfall Intelligence

Provides district-level rainfall distribution and deviation analysis for 2026.

Key analysis includes:

- Average actual rainfall
- Average normal rainfall
- Average rainfall deviation
- Rainfall variance
- Districts with highest rainfall deviation
- Districts with highest actual rainfall
- Actual versus normal rainfall comparison
- Bihar rainfall map

![Rainfall Intelligence](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2830%29.png)

---

### 6. District Profile

Provides an integrated profile for an individual Bihar district.

After selecting a district, users can examine:

- Total population
- Literacy rate
- Agricultural production
- Total schools
- Actual rainfall
- Primary versus upper-primary teachers
- Crop-wise yield
- Sex ratio
- Primary versus upper-primary schools
- Crop-wise production
- Actual versus normal rainfall

![District Profile](./BDDIP_Project%20Final%20report/Screenshots/Screenshot%20%2831%29.png)

---

## 🗂️ Data Model

### Dimension Table

**DimDistrict**

The district dimension provides a consistent district reference used for filtering and analysis across the subject areas.

### Fact Tables

**FactPopulation**
- District
- Population
- Literacy rate
- Population growth
- Sex ratio
- Population density

**FactAgriculture**
- District
- Crop
- Year
- Area
- Production
- Yield

**FactEducation**
- District
- Data year
- Primary schools
- Upper-primary schools
- Primary teachers
- Upper-primary teachers

**FactRainfall**
- District
- Actual rainfall
- Normal rainfall
- Rainfall deviation

---

## 🔄 Data Preparation & ETL

The project includes a Power Query-based data preparation workflow.

Major preparation activities include:

- Importing source datasets
- Cleaning and standardizing columns
- Removing unnecessary records
- Handling totals rows
- Standardizing district names
- Standardizing crop names
- Creating district identifiers
- Structuring fact and dimension tables
- Setting appropriate data types
- Preparing tables for Power BI relationships
- Building the analytical model

---

## 🧮 DAX & Analytics

DAX measures were created to support the dashboard's KPI cards and analytical visuals.

The project includes measures related to:

- Population
- Agriculture
- Production
- Yield
- Education
- Schools
- Teachers
- Rainfall
- Rainfall variance/deviation
- District-level analytical comparisons

Detailed DAX documentation is available in the **Documentation** folder.

---

## 🎨 Dashboard Design

The dashboard follows a consistent visual design across pages:

- Green-based visual theme
- KPI cards for important metrics
- Clean white dashboard canvas
- Consistent page headers
- Navigation buttons
- Interactive slicers
- Maps for geographic analysis
- Bar charts for ranking comparisons
- Scatter charts for relationship analysis
- District-level filtering experience

---

## 📚 Project Documentation

The repository contains supporting documentation covering the development and analytical structure of the project.

Documentation includes:

- Data Dictionary
- DAX Documentation
- Data Model / Relationship Documentation
- Power Query / ETL Documentation
- Dashboard / Visualization Documentation
- Project Methodology
- Performance Analysis
- Project Presentation / Case Study
- Supporting screenshots

Please refer to the **Documentation** folder for the detailed files.

---

## 🗃️ Data Sources

The project combines information from multiple datasets covering Bihar districts.

Major source categories represented in the dashboard are:

- **Population Census (2011)**
- **Agriculture Statistics (2020–2024)**
- **Education Statistics**
- **Rainfall Data (2026)**
- **District Master**

The exact source details, fields, transformations, assumptions, and limitations are documented separately in the project documentation.

---

## ⚠️ Data & Project Limitations

The dashboard is intended primarily as a **portfolio and analytical demonstration project**.

Important limitations include:

- Population information is based on Census 2011.
- Agriculture data covers the documented 2020–2024 period.
- Rainfall analysis shown in the dashboard is for 2026.
- Education data availability varies by the documented reporting years.
- The dashboard should not be treated as an official real-time government decision system.
- Results depend on the quality, coverage, definitions, and reporting periods of the underlying datasets.

Users should refer to the source documentation before using results for operational or policy decisions.

---

## 💡 Key Skills Demonstrated

### Power BI

- Data modeling
- Power Query
- DAX
- Interactive dashboards
- KPI design
- Data visualization
- Map visualization
- Slicers and filtering
- Report navigation
- Dashboard performance analysis

### Data Analytics

- Data cleaning
- ETL
- Dimensional modeling
- Data integration
- Comparative analysis
- Trend analysis
- Geographic analysis
- KPI development
- Insight generation

### Documentation

- Data dictionary creation
- DAX documentation
- Data model documentation
- ETL documentation
- Dashboard documentation
- Performance documentation
- Portfolio presentation

---

## 📁 Repository Structure

```text
Bihar-District-Decision-Intelligence-Platform-Project/
│
├── BDDIP_Project Final report/
│   │
│   ├── Documentation/
│   │
│   ├── Presentation/
│   │
│   └── Screenshots/
│       ├── Screenshot (26).png
│       ├── Screenshot (27).png
│       ├── Screenshot (28).png
│       ├── Screenshot (29).png
│       ├── Screenshot (30).png
│       └── Screenshot (31).png
│
└── README.md
```

> **Note:** The Power BI project file is intentionally not included in the public repository. The repository focuses on the portfolio presentation, documentation, screenshots, and analytical methodology.

---

## 🚀 How to Explore the Project

Recommended order:

1. **Home**
2. **Executive Dashboard**
3. **Agriculture Intelligence**
4. **Education Intelligence**
5. **Rainfall Intelligence**
6. **District Profile**
7. **Documentation**
8. **Project Presentation**

The screenshots above demonstrate the final report layout and the type of interactive analysis available in the original Power BI report.

---

## 🔗 Project Resources

- [Documentation Folder](./BDDIP_Project%20Final%20report/Documentation/)
- [Presentation Folder](./BDDIP_Project%20Final%20report/Presentation/)
- [Dashboard Screenshots](./BDDIP_Project%20Final%20report/Screenshots/)

---

## 👤 Author

**Prashant Kumar**

Power BI & Data Analytics Portfolio Project  
**Bihar District Intelligence & Recommendation System**  
August 2026
