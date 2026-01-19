# Housing Price Dataset – Exploratory Data Analysis (EDA)

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on a housing dataset to understand how different **categorical and numerical features** are distributed and how they describe typical houses in the dataset. The goal of this project is to gain insights into housing characteristics and prepare the data for further analysis and modeling in the future.

This project focuses mainly on **data understanding and visualization**, not prediction.

---

## Dataset Description
The dataset contains information about houses with features related to:
- Location (main road, preferred area)
- Amenities (guest room, basement, hot water heating, air conditioning)
- Structure (bedrooms, bathrooms, stories)
- Parking facilities
- Furnishing status

The dataset includes both **categorical** and **numerical** variables, making it suitable for exploratory analysis and regression-based modeling.

---

## Tools and Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## Steps Performed

### 1. Data Loading and Inspection
- Loaded the dataset using Pandas
- Checked dataset shape, column names, data types
- Generated summary statistics for numerical features

### 2. Categorical Data Analysis
- Analyzed value counts for categorical variables such as:
  - Main road
  - Guest room
  - Basement
  - Hot water heating
  - Air conditioning
  - Preferred area
  - Furnishing status
- Visualized distributions using bar charts

**Key Insight:**  
Most houses have common features like main road access and semi-furnishing, while luxury amenities are relatively rare.

---

### 3. Numerical Data Analysis
- Analyzed distributions of:
  - Bedrooms
  - Bathrooms
  - Stories
  - Parking
- Used bar plots to understand frequency distributions

**Key Insight:**  
The dataset mainly represents **small to medium-sized residential houses**, suitable for typical families.

---

## Overall Conclusions
- The dataset represents **average or middle-range housing**, not luxury housing.
- Most features are **unevenly distributed**, with a few categories dominating.
- Rare features (like multiple bathrooms or hot water heating) may indicate higher-value houses.
- The dataset appears realistic and suitable for further analysis.

---

## Future Work
In future updates, the project can be extended by:
- Analyzing relationships between house price and other features
- Visualizing price trends across different categories
- Encoding categorical variables for modeling
- Building simple regression models to predict house prices

---

## Author
KARTHIC
2nd Year Data Science Student  
Exploratory project created for learning data analysis, visualization, and interpretation.
