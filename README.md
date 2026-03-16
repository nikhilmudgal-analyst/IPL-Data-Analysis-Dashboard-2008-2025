# IPL Data Analysis Dashboard (2008–2025)

This project analyzes Indian Premier League (IPL) match data from **2008 to 2025**.
The project focuses on cleaning and transforming raw datasets using **Python (Pandas)** and building an **interactive Power BI dashboard** to analyze team and player performance.

---

## Project Workflow

Raw Data → Data Cleaning (Python) → Data Transformation (Power Query & Excel) → Data Modeling (DAX) → Power BI Dashboard

---

## Data Preparation

### Python (Pandas)

Python scripts were used to clean and preprocess the raw IPL datasets.

Main tasks included:

* Loading raw datasets
* Replacing team ID numbers with team names using `teams_data.csv`
* Removing unnecessary columns
* Creating a **result column** describing match outcomes (win by runs or wickets)
* Flagging the **final match of each IPL season**
* Saving cleaned datasets for analysis

### Excel Transformations

Excel was used for minor transformations such as:

* Adding **image URLs** for teams and players

### Power Query

Power Query was used in Power BI to:

* Perform additional data transformations
* Prepare datasets for data modeling and visualization

---

## Data Modeling & Measures

**DAX** was used to create:

* Measures for KPIs
* Calculated tables for analysis
* Metrics used in the dashboard visuals

---

## Tools Used

* Python (Pandas)
* Power BI
* Power Query
* DAX
* Microsoft Excel

---

## Project Structure

data

* raw → original IPL datasets
* cleaned → processed datasets after cleaning

scripts

* Python scripts used for data cleaning

dashboard

* Dashboard preview files and information

images

* Dashboard screenshots used in documentation

## Dashboard Access

The full Power BI dashboard file is not publicly shared.
If you would like to explore the interactive dashboard, feel free to connect with me on LinkedIn.

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

---

## Author

Nikhil Mudgal

---

## Dashboard Preview

![image alt](Dashboard/ipl_match_powerbi_image.pdf)


