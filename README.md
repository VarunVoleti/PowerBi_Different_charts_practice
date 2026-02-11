# I practiced all kinds of charts available in Power Bi and there are the one that I always come back to

## 1️⃣ Bar Chart (Clustered / Horizontal Bar)

###🔹 What it is:

**Compares values across categories using horizontal or vertical bars.**

### ✅ Advantages

Very easy to understand
Great for comparing categories
Works well with long category names (horizontal bar)

### ❌ Disadvantages

Gets cluttered with too many categories
Not good for showing trends over time (unless small dataset)

### 📊 Best Use Cases

Sales by region
Revenue by product
Count of customers by state

### 📁 Best Data

Categorical data (Region, Product, Department)
One numeric measure (Sales, Count, Profit)

<img width="1023" height="673" alt="powerbi_practice_pic1-barchart" src="https://github.com/user-attachments/assets/4429bee0-746f-4cde-85ab-d2cc12873e1a" />

## 2️⃣ Line Chart

### 🔹 What it is:

Shows trends over time using connected data points.

### ✅ Advantages

Best chart for time-series analysis
Clearly shows trends and seasonality
Good for comparing multiple lines

### ❌ Disadvantages

Not ideal for categorical comparison
Too many lines make it messy

### 📊 Best Use Cases

Monthly sales trend
Daily website traffic
Year-over-year growth

### 📁 Best Data

Time-based data (Date, Month, Year)
Continuous numeric values

<img width="1036" height="668" alt="powerbi_practice_pic2-linechart" src="https://github.com/user-attachments/assets/87918648-0713-4b7f-b722-375a3a436e05" />

## 3️⃣ Area Chart & Line Area Chart

### 🔹 What it is:

Like a line chart, but the area below the line is filled.

### ✅ Advantages

Shows trend + volume
Good for cumulative totals
Visually impactful


### ❌ Disadvantages

Hard to compare multiple categories
Can hide smaller values

### 📊 Best Use Cases

Total revenue growth
Customer growth over time
Cumulative performance

### 📁 Best Data

Time-based data
Continuous numeric values

<img width="1042" height="674" alt="powerbi_practice_pic3-area linechart" src="https://github.com/user-attachments/assets/1292b25d-1297-49e4-9d04-1d54b62232a0" />

## 4️⃣ 100% Stacked Area Chart

### 🔹 What it is:

Shows percentage contribution of categories over time (always totals to 100%).

### ✅ Advantages

Shows proportion changes clearly
Good for market share analysis

### ❌ Disadvantages

Cannot see actual values
Hard to compare small segments

### 📊 Best Use Cases

Market share over time
Revenue contribution by category
Percentage distribution trend

### 📁 Best Data

Time dimension
Multiple categories contributing to total

<img width="1038" height="668" alt="powerbi_practice_pic4-100%stacked_areachart" src="https://github.com/user-attachments/assets/891709d3-ee6a-483a-b582-564133ad6711" />

## 5️⃣ Stacked Area Chart

### 🔹 What it is:

Shows total value and how each category contributes over time.

### ✅ Advantages

Shows both total and breakdown
Good for part-to-whole trend

### ❌ Disadvantages

Hard to compare middle layers
Can get cluttered

### 📊 Best Use Cases

Revenue by product category over time
Sales by region trend

### 📁 Best Data

Time series
Multiple numeric categories

<img width="1034" height="677" alt="powerbi_practice_pic5-Stacked_areachart" src="https://github.com/user-attachments/assets/870fcab5-f9a2-4a77-aa99-a3bc6f20c504" />

## 6️⃣ Combo Chart (Line + Column)

### 🔹 What it is:

Combines bar chart and line chart in one visual.

### ✅ Advantages

Compare two different measures
Can use dual axis
Great for performance vs target

### ❌ Disadvantages

Can confuse audience if not labeled properly
Dual axis can mislead

### 📊 Best Use Cases

Sales (bars) vs Profit Margin % (line)
Revenue vs Target
Volume vs Price

### 📁 Best Data

One categorical/time field
Two different numeric measures

<img width="1032" height="671" alt="powerbi_practice_pic6-combocharts" src="https://github.com/user-attachments/assets/fc8df6d9-fc19-42af-9b69-230179a03edf" />

## 7️⃣ Pie Chart & Donut Chart

### 🔹 What it is:

Shows proportion of categories in a whole.

### ✅ Advantages

Simple and visually clean (if few categories)
Good for part-to-whole snapshot

### ❌ Disadvantages

Hard to compare similar slices
Not good with many categories
No trend analysis

### 📊 Best Use Cases

Market share snapshot
Budget allocation
Customer segment distribution

### 📁 Best Data

2–5 categories max
Percentage-based data

**👉 Use only when categories are few and differences are clear.**

<img width="1011" height="673" alt="powerbi_practice_pic16-pie donutcharts" src="https://github.com/user-attachments/assets/d2ce81e9-a1ad-4035-8f72-26129163f1a0" />

## 8️⃣ Scatter Plot

### 🔹 What it is:

Shows relationship between two numeric variables.
Example: Income vs Spending

## Types:

**Basic scatter**
**Bubble chart (size varies)**
**Scatter with play axis (animation over time)**

### ✅ Advantages

Shows correlation
Identifies clusters
Detects outliers

### ❌ Disadvantages

Hard for non-technical users
Needs numeric data on both axes

### 📊 Best Use Cases

Sales vs Profit
Income vs Spending
Customer Age vs Purchase Value

### 📁 Best Data

X-axis: Numeric

Y-axis: Numeric

Optional:

Size → Third numeric measure

Color → Category


<img width="830" height="600" alt="powerbi_practice_pic17-scatter_plotcharts" src="https://github.com/user-attachments/assets/ec6b4bcb-2bfd-410c-8259-4409b6230d00" />

## 🎨 How to make different sizes & colors in Power BI:

**X Axis:** Add numeric field

**Y Axis:** Add numeric field

**Size:** Add a numeric measure (e.g., Sales)

**Legend:** Add category (e.g., Region)

**Details:** Add unique ID (e.g., Customer ID)

That creates a bubble chart.

<img width="1037" height="586" alt="powerbi_practice_pic18-scatter_plot2" src="https://github.com/user-attachments/assets/f6987729-69be-4716-abe4-59214f3a254a" />

## 9️⃣ Ribbon Chart

### 🔹 What it is:

Shows ranking changes over time.
It displays how categories move up or down in rank.

### ✅ Advantages

Excellent for rank comparison
Shows competition movement

### ❌ Disadvantages

Not good for exact values
Can get visually complex

### 📊 Best Use Cases

Product ranking over years
Top-performing regions over time
Market share ranking

### 📁 Best Data

Time field
Category
Numeric measure (for ranking)

<img width="828" height="670" alt="powerbi_practice_pic19-ribbon_chart" src="https://github.com/user-attachments/assets/fc7bc747-dabd-42cb-ad20-8b24d81d062c" />

## 🔟 Waterfall Chart

### 🔹 What it is:

Shows how an initial value increases or decreases step-by-step.

### ✅ Advantages

Excellent for financial analysis
Shows contribution of each component
Easy to explain profit breakdown

### ❌ Disadvantages

Not suitable for large datasets
Needs ordered steps

### 📊 Best Use Cases

Revenue → Expenses → Net Profit
Budget vs Actual variance
Monthly profit breakdown

### 📁 Best Data

Categories in logical sequence
Positive and negative values

<img width="842" height="674" alt="powerbi_practice_pic20-waterfall_chart" src="https://github.com/user-attachments/assets/e71afb3a-adb6-44c4-bb58-e5c762c0ca67" />



