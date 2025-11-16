# Youth Unemployment Analysis – South Africa (Stats SA QLFS)

This project is a simple exploratory data analysis (EDA) of **youth unemployment in South Africa by province**, using data from the Quarterly Labour Force Survey (QLFS).

The goal of this project is to practice Python-based data analysis while exploring a real social and economic issue that affects young people.

---

## Project Goals

- Load and explore a real-world dataset (Stats SA QLFS youth unemployment by province and sex)
- Filter the data by **year** and **total youth**
- Summarise youth unemployment by province
- Create a clear visualisation (bar chart)
- Practice writing insights and communicating findings

---

## Data

The dataset used is:

- `ZA110,DF_UNE_SEX_PROV,1.0+all.csv`

Key columns:

- `REF_AREA` – Province code (e.g. GP, KZN, WC)  
- `SEX` – Sex category (`_T` = total, `M` = male, `F` = female)  
- `TIME_PERIOD` – Quarter & year (e.g. `2023-Q1`)  
- `OBS_VALUE` – Number of unemployed youth (in thousands)  
- `UNIT_MEASURE` – Unit of measure (`PS` = persons)  
- `UNIT_MULT` – Multiplier (`3` = thousands)

In this first version of the project, the analysis focuses on:

- **Total youth unemployment (`SEX = "_T"`)**
- **Year 2023**
- **Average number of unemployed youth per province in 2023**

---

## Tools & Technologies

- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook / Google Colab  
- GitHub (for version control and portfolio)

---

## Notebook

Main analysis notebook:

- `youth_unemployment_eda.ipynb`

This notebook includes:

1. Loading the dataset  
2. Filtering to total youth (`SEX = "_T"`)  
3. Filtering to a specific year (`2023`)  
4. Mapping province codes to province names  
5. Calculating average youth unemployment per province  
6. Visualising the results using a bar chart  
7. Writing short insights based on the chart

---

## Example Visualisation

- **Bar chart:** Average youth unemployment (thousands) by province for 2023

This gives a quick view of which provinces have the highest and lowest numbers of unemployed youth (in this dataset).

---

## Possible Extensions

Future improvements and ideas:

- Compare trends across **multiple years** (e.g. 2015 vs 2023)
- Break down youth unemployment by **sex** (male vs female)
- Add **rates** instead of just counts, if population data is available
- Explore links between youth unemployment and other indicators (education, migration, province-level economic factors)

---

## About Me

This project is part of my journey as an **MSc Data Science student** with a background in **Development Studies and Population Studies**. I am interested in using data and technology to address social and economic challenges affecting young people in South Africa and beyond.

---
