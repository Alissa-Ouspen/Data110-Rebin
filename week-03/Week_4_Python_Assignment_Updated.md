# Week 3 Assignment: Scatter Plots, Line Plots, and Bar Graphs

In this assignment, you will practice three common data visualizations in Python using **Matplotlib**:

1. **Scatter Plot** — showing the relationship between two numerical variables
2. **Line Plot** — showing how values change across an ordered sequence
3. **Bar Graphs** — comparing categories and changes across categories

The **bar graph section is the main part of this assignment**.

---

# Part 1: Scatter Plot

A scatter plot is useful when we want to examine the relationship between two numerical variables. In class, we created scatter plots using both `plt.plot()` with markers and `plt.scatter()`.

## Task 1: Study Time vs. Exam Score

Use the following data:

```python
study_hours = [1, 2, 2.5, 3, 4, 5, 5.5, 6, 7, 8]
exam_scores = [55, 60, 63, 66, 72, 78, 80, 84, 88, 94]
```

### Instructions
- Create a **scatter plot** with `study_hours` on the x-axis and `exam_scores` on the y-axis.
- Choose a marker style and color.
- Add a title and label both axes.
- Briefly answer: **What relationship do you observe between study time and exam score?**

---

# Part 2: Line Plot

Line plots are useful for showing changes or trends when the order of the x-values matters. In class, we practiced plotting multiple lines, changing line styles, adding labels, and creating legends.

## Task 2: Temperature Over One Week

Use the following data:

```python
days = ["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]
city_a = [68, 70, 72, 71, 74, 76, 75]
city_b = [62, 64, 67, 66, 69, 71, 70]
```

### Instructions
- Plot **both cities on the same line graph**.
- Use a different line style and/or marker for each city.
- Add a title, x-axis label, y-axis label, and legend.
- Briefly answer: **Which city was generally warmer during the week?**

---

# Part 3: Bar Graphs — Crime Data Visualization (2022–2023)

In this section, you will analyze real-world crime data from 2022 to 2023, sourced from the **FBI's Crime Data** as reported by the Brennan Center. According to the Brennan Center’s analysis, most crimes, including murder, saw decreases in 2023.

Source: [FBI Data Confirms Drop in Most Crimes in 2023, Especially Murders](https://www.brennancenter.org/our-work/analysis-opinion/fbi-data-confirms-drop-most-crimes-2023-especially-murders)

## Dataset

| **Offense** | **Offenses per 100,000 People (2023)** | **Change in Offenses per 100,000 People (2022–2023)** |
|---|---:|---:|
| Aggravated Assault | 264.1 | -3.3 |
| Burglary | 250.7 | -8.1 |
| Larceny | 1,347.2 | -4.9 |
| Motor Vehicle Theft | 318.7 | +12.0 |
| Murder | 5.7 | -12.0 |
| Rape (revised definition) | 38.0 | -9.8 |
| Robbery | 66.5 | -0.8 |

---

## Task 3A: Basic Bar Chart for Crime Rates in 2023

Create a **bar chart** showing the offense rates per 100,000 people for each type of crime in 2023.

### Instructions
- Create a bar chart for crime rates in 2023.
- Customize the bar colors and add gridlines.
- Label the axes and add a title.
- Make sure the category labels are readable.

---

## Task 3B: Change in Crime Rates from 2022 to 2023

Create a **horizontal bar chart** that shows the percentage change in offense rates from 2022 to 2023 for each crime type.

### Instructions
- Create a horizontal bar chart showing the **change in offense rates**.
- Assign a unique color to each crime type.
- Label the axes and add a title.
- Make it easy to distinguish increases from decreases.

### Short Response
Answer the following question in a few sentences:

**Why might this graph be more useful than the graph in Task 3A?**

Think about the difference between looking at the **size of the crime rate in one year** and looking at **how much the rate changed from one year to the next**.

---

## Task 3C: Improve the Clarity of Your Bar Graph

Create **one improved version** of your graph from Task 3B.

You may improve it by changing things such as:
- colors,
- labels,
- gridlines,
- figure size,
- text size,
- or the ordering of the categories.

Your goal is to make the graph easier to understand quickly.

---

## Task 3D: Multi-Series Grouped Bar Chart

In this task, you will practice making a **multi-series grouped bar chart** using a simple fictional dataset.

Imagine three companies (**Company A, Company B, Company C**) that each sell three products (**Product 1, Product 2, Product 3**).

### Example Dataset

```python
companies = ["Company A", "Company B", "Company C"]
product1 = [20, 34, 30]
product2 = [25, 32, 34]
product3 = [30, 35, 27]
```

### Instructions
- Plot a grouped bar chart with **3 bars per company**.
- Use one bar for each product.
- Add labels, a title, and a legend.
- Make sure the three products are easy to compare within each company.

---

# Submission

Submit your completed notebook containing:

- **1 scatter plot**
- **1 line plot with two lines**
- **the four bar graph tasks in Part 3**
- your short written responses

Make sure every graph includes appropriate labels and a title.
