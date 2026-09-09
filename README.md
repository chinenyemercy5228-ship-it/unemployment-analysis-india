# 📊 Unemployment Analysis in India: A COVID-19 Impact Study

An exploratory data analysis and time-series study of unemployment trends in India, examining how unemployment changed across states, regions, and rural/urban areas—with a particular focus on the impact of the COVID-19 lockdown.

## 📌 Project Overview

Unemployment is not just a number—it changes across locations and over time.

In this project, I analyzed unemployment data from India to understand regional differences, monthly trends, and how the COVID-19 pandemic reshaped the labour market.

Using exploratory data analysis and time-series visualization, I investigated questions such as:

* Which states experienced the highest average unemployment?
* How did unemployment change over time?
* What happened to unemployment during the COVID-19 lockdown?
* Did different states experience the pandemic shock differently?
* How did rural and urban labour markets compare?
* What relationships exist between unemployment, employment, and labour participation?

The analysis focuses on understanding the **story behind the numbers by placing unemployment data in its time context**.

---

## 🎯 Project Objectives

The objectives of this project were to:

* Perform data cleaning and preprocessing.
* Explore unemployment trends across Indian states and regions.
* Analyze monthly unemployment patterns.
* Perform time-series analysis across major states.
* Identify the states with the highest average unemployment rates.
* Examine relationships between unemployment, employment, and labour participation.
* Compare unemployment before and after the COVID-19 lockdown.
* Investigate differences between rural and urban unemployment patterns.

---

## 📂 Dataset

The dataset contains unemployment statistics across different states and areas in India.

### Key Features

| Feature                                 | Description                                                    |
| --------------------------------------- | -------------------------------------------------------------- |
| Region                                  | State or Union Territory                                       |
| Date                                    | Date of observation                                            |
| Frequency                               | Frequency of data collection                                   |
| Estimated Unemployment Rate (%)         | Percentage of the labour force that is unemployed              |
| Estimated Employed                      | Estimated number of employed individuals                       |
| Estimated Labour Participation Rate (%) | Percentage of the population participating in the labour force |
| Area                                    | Rural or Urban                                                 |

### Data Cleaning

The dataset was cleaned before analysis by:

* Removing 28 completely empty rows.
* Stripping unnecessary spaces from column names.
* Converting the `Date` column to datetime format.
* Converting numerical columns to appropriate numeric data types.
* Converting categorical variables such as `Region` and `Area` to category data types.

After cleaning, the dataset contained **740 valid observations** covering **27 states/Union Territories** across rural and urban areas.

---

## 🛠️ Tools and Technologies

* **Python**
* **Pandas** — Data manipulation and analysis
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Analysis and documentation

---

## 🔍 Analysis Performed

### 1. Data Exploration and Cleaning

The dataset was inspected for:

* Dataset shape
* Missing values
* Data types
* Column formatting
* Blank rows

The raw dataset contained 28 completely empty rows, which were removed before further analysis.

---

### 2. Region-Wise Unemployment Analysis

Average unemployment rates were calculated across states and broader geographic zones.

This analysis helped identify areas with consistently higher unemployment levels.

---

### 3. Monthly Unemployment Trends

Unemployment rates were aggregated by month to understand how unemployment changed over time.

The analysis revealed a relatively stable unemployment pattern before the pandemic, followed by a major disruption during the COVID-19 period.

---

### 4. Time-Series Analysis

A time-series analysis was performed to track unemployment rates over time.

The analysis compared four major states:

* Maharashtra
* Uttar Pradesh
* Tamil Nadu
* Bihar

The goal was to understand how unemployment patterns changed over time and whether different states experienced the COVID-19 shock differently.

---

### 5. Top 10 States with the Highest Average Unemployment

States were ranked based on their average unemployment rate across the study period.

This analysis identified regions with consistently high unemployment and highlighted the significant differences between states.

---

### 6. Correlation Analysis

A correlation heatmap was created to examine the relationship between:

* Estimated Unemployment Rate
* Estimated Employed
* Estimated Labour Participation Rate

This helped explore how labour market indicators move together.

---

### 7. COVID-19 Impact Analysis

To examine the impact of the pandemic, the data was divided into:

* **Pre-COVID:** Before India's nationwide lockdown
* **Post-COVID:** After the lockdown began

The lockdown began on **25 March 2020**, creating a clear point for comparing labour market conditions before and after the COVID-19 shock.

---

### 8. Rural vs Urban Analysis

An additional analysis compared unemployment trends between:

* Rural areas
* Urban areas

This helped determine whether the COVID-19 disruption affected both labour markets equally.

---

# 📈 Key Findings

## 🦠 COVID-19 Caused a Major Unemployment Shock

Before the pandemic, unemployment generally remained within a relatively stable range of approximately **7–9%**.

However, unemployment rose sharply in **April 2020 to approximately 23%**, shortly after India's nationwide COVID-19 lockdown.

This represented a major disruption to the labour market.

---

## 📍 Unemployment Varied Significantly Across States

The analysis showed considerable regional differences in unemployment rates.

**Haryana, Tripura, and Bihar** recorded some of the highest average unemployment rates during the study period.

This demonstrates that unemployment was not evenly distributed across India.

---

## 📈 Time Revealed the Full Story

Looking at unemployment as a single number provided only a snapshot.

However, plotting unemployment across time revealed:

* Monthly fluctuations
* Major pandemic-related spikes
* Differences in recovery patterns
* Variation between states

The time-series analysis showed that the COVID-19 shock did not affect every state in the same way.

---

## 🏙️ Urban Areas Experienced a Larger Shock

Both rural and urban areas experienced a sharp increase in unemployment after the lockdown.

However, the increase was larger in urban areas.

This may reflect the significant impact of lockdown restrictions on sectors such as:

* Services
* Retail
* Construction
* Manufacturing

---

## 🔗 Labour Market Relationships

The correlation analysis showed a strong relationship between unemployment and employment indicators.

Labour participation, however, showed a weaker relationship with unemployment.

This suggests that changes in unemployment do not necessarily mean people stopped participating in the labour force.

---

# 📊 Visualizations

The project includes the following visualizations:

* Region-wise average unemployment rates
* Monthly unemployment trends
* Time-series unemployment trends across major states
* Top 10 states with the highest average unemployment
* Correlation heatmap
* Pre-COVID vs post-COVID comparison
* Rural vs urban unemployment comparison

---

# 📁 Project Structure

```text
unemployment-analysis-india/
│
├── Unemployment_Analysis_India.ipynb
├── Unemployment_in_India.csv
└── README.md
```

---

# 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/chinenyemercy5228-ship-it/unemployment-analysis-india.git
```

### 2. Navigate to the project directory

```bash
cd unemployment-analysis-india
```

### 3. Install the required libraries

```bash
pip install pandas matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open and run

```text
Unemployment_Analysis_India.ipynb
```

---

# 🔮 Future Work

This project focused on exploratory and time-series analysis rather than forecasting.

Possible next steps include:

* Building a time-series forecasting model.
* Forecasting future unemployment rates.
* Comparing different forecasting techniques.
* Exploring ARIMA and other time-series models.
* Performing deeper statistical analysis of unemployment patterns.
* Expanding the analysis with more recent unemployment data.

---

# 💡 What I Learned

This project reinforced an important lesson about data analysis:

> **A data point tells you what happened. A time series helps you understand when and how it happened.**

By placing unemployment data on a timeline, it became easier to identify patterns, major disruptions, and differences in how regions responded to the COVID-19 pandemic.

This project also served as an introduction to deeper **time-series analysis** and sparked my interest in exploring how historical data can eventually be used for forecasting.

---

## 👩‍💻 Author

**Elechi Chinenye**

Public Health Professional | Aspiring Data Analyst | AI & Machine Learning Learner

📌 Interested in exploring the intersection of **data, public health, AI, and technology**.

🔗 **GitHub:** https://github.com/chinenyemercy5228-ship-it
