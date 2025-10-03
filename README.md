## **PHASE 1 PROJECT**
## **Business Understanding**
### **Overview**
Skyway Airlines is a new airline that wants to enter the aviation industry. It wants to purchase aircrafts to operate for commercial and private enterprises. As a startup, one of the most important things is buying aircrafts that are safe and reliable for their operations. This project uses data from past aviation accidents between 1919 and 2023 to get potential risks of different aircrafts and determine the lowest risk aircraft. It also aims to show how important a specific airline's practices are having the best aircrafts or not. The goal is to provide Skyway Airlines with information to build a strong foundation of safety and efficiency for its operations.

### **Problem Statement**
An airline company comes with high risks such as ensuring passenger safety and maintaining operational reliability. There are many issues that cause aviation accidents including the type of aircraft. Therefore, choosing the wrong type of aircraft would result in safety challenges and damage the brand reputation. Being unaware of the issues that cause accidents would also make it hard to ensure less accidents or little to no damage during accidents. All this may bring down the company as it is new in stead of growing it.

### **Objectives**
1. Determine the aircraft with the lowest risk to purchase for the business.
2. Find the potential risks of aircrafts and explain them to the stakeholders.
3. Demonstrate how important good airline practices are in ensuring safety regardless of the aircraft type.

### **Solution**
The project aims to guide Skyway Airlines to making informed decisions on purchasing aircrafts and on ensuring operational reliabilty. That is, it provides aircraft and operator safety insights. This is by analyzing past aviation accident data to identify potential risks and the safest aircraft type. The analysis also aims to show that a specific airline can be the cause of an accident even though the type of aircraft is the best.

## **Data Understanding and Data Cleaning**
### **Data Understanding**
The dataset for this project contained information on aviation accidents from 1919 to 2023. It had 23967 entries. It also had 9 columns with accident and aircraft details which are date, registartion, country, location, category, fatalities, type, operator and year. The category column had factors causing the accident together with the damage level. These factors are A=Accident, I=Incident, H=Hijacking, C=Criminal Occurence, O=Other Occurence, U=Unknown Occurence, and the damage levels are 1=Hull Loss(non-repairable damage) and 2=Repairable Damage.

### **Data Cleaning**
The data also contained missing values and duplicates. I dropped the duplicates then dropped some missing values by dropping rows that have a null value in any of the type, category or fatalities column. This is because the three columns are what I mostly using for my analysis. Also filled the remaining missing values. After all this I generated a new dataset with 20019 entries and 9 columns.

## **Data Analysis and Visualization**
### **Data Analysis**
For analysis, I created a pivot table for the three columns with rows as types, columns as categories and values as total fatalities. I used this to get all the potential factors and the lowest risk aircraft. This was by getting the maximum and minimum total fatalities for each category(factor plus damage level).

### **Data Visualization**
#### **Python Visualizations**
For python visalizations, I plotted bar graphs for the following;
10 Most Dangerous types Vs Total Fatalities 
10 Safest types Vs Total Fatalities
Total Fatalities vs Categories
10 Poor Operators Vs Total Fatalities
10 Good Operators Vs Total Fatalities

#### **Tableau Visualizations**
I also plotted the following tableau visualization sheets;
Time Series for Total Fatalities
Regional Map for Countries with their Total Fatalities
Total Fatalities Vs Aircraft Type Bar Chart
Categories(Factors plus Damage Level) Vs Total Fatalities Bar Chart
Total Fatalities Vs Operators Bar Chart
I then created a Tableau Dashboard;
The link to the [SkyWay Airlines Aviation Analysis Dashboard](https://public.tableau.com/authoring/Phase1Project_17593596944020/SkywayAirlineAviationAnalysisDashboard/Skyway%20Airlines%20Aviation%20Analysis%20Dashboard#1)
