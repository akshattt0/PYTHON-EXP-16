# Experiment 16: Basic Charts and Visual Encoding

---

## Title

Visualization of Data Using Matplotlib and Seaborn in Python

---

## Aim

To study and implement various data visualization techniques using Matplotlib and Seaborn libraries for effective representation of data.

---

## Objectives

- To understand the importance of data visualization  
- To create line charts for trend analysis  
- To visualize comparisons using bar charts  
- To represent data distribution using histograms  
- To analyze relationships using scatter plots  
- To enhance visualization using Seaborn  

---

## Theory

Data visualization is the process of representing data graphically to identify patterns, trends, and relationships. It helps in better understanding of complex data.

Python provides powerful libraries such as **Matplotlib** and **Seaborn** for visualization.

Common types of plots include:

- **Line Chart:** Used to show trends over time  
- **Bar Chart:** Used for comparison between categories  
- **Histogram:** Used to display data distribution  
- **Scatter Plot:** Used to show relationships between variables  

Seaborn is built on top of Matplotlib and provides more attractive and informative visualizations with less code.

---

## Datasets Used

### 1. Study Dataset
- Columns: Days, Study_Hours, Marks, Attendance, Sleep_Hours, Assignments_Completed  
- Used for line plots, bar charts, and scatter plots  

### 2. Marks Dataset
- Used for histogram and distribution analysis  

### 3. Sales Dataset
- Columns: Day, Region, Sales, Profit, Customers, Category  
- Used for Seaborn visualizations  

---

## Problem Statements

### 1. Line Chart

Plot study hours over days to analyze trends.

**Concepts Used:** plt.plot()

---

### 2. Advanced Line Chart

Compare study hours and marks in a single graph.

**Concepts Used:** multiple line plots, legend

---

### 3. Bar Chart

Visualize marks for each day.

**Concepts Used:** plt.bar()

---

### 4. Advanced Bar Chart

Display marks with value labels on top of each bar.

**Concepts Used:** get_height(), get_x(), get_width(), plt.text()

---

### 5. Grouped Bar Chart

Compare study hours and marks side by side.

**Concepts Used:** numpy indexing, bar positioning

---

### 6. Histogram

Analyze the distribution of marks and highlight mean value.

**Concepts Used:** plt.hist(), axvline()

---

### 7. Scatter Plot

Show relationship between study hours and marks.

**Concepts Used:** plt.scatter()

---

### 8. Conditional Scatter Plot

Differentiate data points based on result (Pass/Fail) using colors.

---

### 9. Seaborn Visualizations

- Line Plot  
- Bar Plot  
- Histogram  
- Scatter Plot  

**Concepts Used:** sns.lineplot(), sns.barplot(), sns.histplot(), sns.scatterplot()

