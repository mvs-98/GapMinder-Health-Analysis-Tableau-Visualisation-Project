---

# **GapMinder Health Analysis – Tableau Visualisation Project**

This repository contains a Tableau dashboard that explores global health trends using the **GapMinder Health Dataset**.
The project examines life expectancy, cancer cases, BMI, blood pressure, population growth, and demographic health indicators across continents and genders.

The aim is to derive insights that can support health organisations—such as the NHS—in understanding disease patterns and allocating resources effectively.

---

## **Dataset**

The GapMinder Health Dataset includes multiple global indicators:

* Life Expectancy
* Cancer Cases (Lung, Liver, Stomach)
* BMI (Men & Women)
* Blood Pressure (Men & Women)
* Population Growth
* Cholesterol Levels
* Gender and Continent breakdown

This dataset was imported into Tableau via **Connect to a File → Text File**.

---

## **Visualisations Created**

### **1. Life Expectancy Over Time – Line Chart**

This line chart shows how life expectancy has changed across continents over several decades.

**Trends Identified:**

* All continents show a gradual increase in life expectancy.
* Africa shows the **most significant rise** over the last 6 years.

---

### **2. Cancer Cases by Type and Continent**

A multi-chart view showcasing Lung, Liver, and Stomach cancer cases across continents.

**Trends Identified:**

* **Asia** has the highest number of cancer cases across all three cancer types.
* **Africa** shows nearly double the number of liver cancer cases compared to lung and stomach cancer.
* **Americas and Europe** show a higher predisposition to **lung cancer**.
* **Oceania** has the lowest cancer case counts overall.

---

### **3. BMI vs Blood Pressure Comparison (Men vs Women)**

Designed to compare average BMI and average Blood Pressure across genders.

**Trends Identified:**

* Men generally have **higher blood pressure**.
* Women have a **slightly higher average BMI**.

---

### **4. Population Growth of Continents Over Time**

A line chart reflecting population growth trends from 1990 onwards.

**Trends Identified:**

* **Americas** show a declining population growth trend.
* **Asia** experienced a decline between 1991–1999, followed by growth thereafter.
* **Oceania** remains stable with minimal fluctuations.

---

### **5. Life Expectancy & Cholesterol Levels vs Gender**

A gender-based comparison of two key health indicators.

**Trends Identified:**

* Life expectancy is **slightly higher for men**.
* Women show **slightly higher average cholesterol levels**.

---

## **Dashboard – Global Health Insights**

An interactive dashboard combining all key visualisations to give a multidimensional view of the dataset.

**Dashboard Features:**

* Trend charts for life expectancy, population growth, and cancer cases
* Side-by-side gender health comparisons
* Intuitive navigation and colour-coded visuals
* Consolidated layout for easier analysis

**Purpose:**
The dashboard enables quick scanning of global health patterns and helps highlight demographic groups most affected by different health issues.

---

## **Key Insights**

* Health risks and disease trends vary significantly across continents.
* Gender differences exist in blood pressure, BMI, and cholesterol.
* Cancer case distribution is heavily skewed by continent and type.
* Population and life expectancy trends offer context for long-term planning.

---

## **Real-World Relevance**

These insights can support organisations like the **NHS** by:

* Identifying demographic groups at higher risk
* Informing preventive care initiatives
* Supporting resource allocation decisions
* Understanding long-term global health shifts

---

## **Tools & Technologies**

* **Tableau Desktop**
* **GapMinder Health Dataset (CSV)**
* Line charts, comparative bar charts, dual-axis visuals, and dashboards
* Filters, colour encoding, and calculated fields where necessary

---

## **Repository Structure**

```
/data                # GapMinder dataset (if included)
/tableau             # Tableau workbook (.twbx)
README.md            # Project documentation
```

---

## **Summary**

This Tableau project provides a comprehensive exploration of global health data.
Through multiple visualisations and an interactive dashboard, it uncovers meaningful patterns in life expectancy, disease prevalence, gender-based health metrics, and population trends—offering valuable insights for health researchers and decision-makers.

---
