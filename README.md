# 🌱 Online Plant Business Analysis

## 📊 Project Overview

This project provides a comprehensive analysis of an **e-commerce plant business catalog**, containing detailed product information, pricing strategies, and plant characteristics. The dataset represents 400 plant products sold online, used to generate insightful dashboards for business intelligence and decision-making.

---

## 📁 Project Structure

```
Online Business Project (Plant)/
│
├── 📂 Online_Plant_Business_Analysis/
│   └── README.md                          # Project documentation (this file)
│
├── 📂 Dataset/
│   └── Online Business Dataset.csv        # Raw dataset (400 products × 13 columns)
│
├── 📂 Excel_Workbook/
│   └── ONLINE_BUSINESS.xlsx               # Main Excel workbook with all analysis
│
├── 📂 Visualizations/
   ├── 📂 Charts/                         # 10 individual chart screenshots
   │   ├── 01_Price_Distribution_BoxWhisker_Chart.PNG
   │   ├── 02_Price_Distribution_Histogram_Chart.PNG
   │   ├── 03_Top10_Brands_BarChart.PNG
   │   ├── 04_Plant_Type_Distribution_PieChart.PNG
   │   ├── 05_Plant_Size_Distribution_ColumnChart.PNG
   │   ├── 06_Plant_LifeCycle_Distribution_DonutChart.PNG
   │   ├── 07_Location_Distribution_ColumnChart.PNG
   │   ├── 08_Hybrid_Plants_Distribution_PieChart.PNG
   │   ├── 09_FengShui_Plants_Distribution_BarChart.PNG
   │   └── 10_Return_Policy_Distribution_ColumnChart.PNG
   │
   ├── 📂 Dashboard/
   │   └── Online Business Plant Analysis.PNG    # Full dashboard screenshot
   │
   └── CHARTS_DOCUMENTATION.md            # Detailed chart descriptions


---

## 📋 Dataset Description

### **Dataset Summary**
- **Total Rows:** 400 products
- **Total Columns:** 13 (primary columns)
- **Format:** CSV (Comma-Separated Values)
- **Domain:** E-commerce plant marketplace

### **Sample Products**
- Anthurium Plant
- Ficus Bonsai Plant
- Brahma Kamal Plant
- Tomato Plant
- Pomegranate Plant
- Dragon Tree
- Jade Plant
- Bamboo Palm Plant

---

## 🗂️ Data Structure

### **1. Product Details**
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `name` | Text | Full product name of the plant |
| `brand` | Text | Brand or seller name |
| `type` | Categorical | Plant category (e.g., Foliage, Fruit, Flower, Herb, Succulent) |
| `plant size` | Categorical | Size classification (Small, Medium, Large) |
| `plant age` | Numeric | Age of the plant (in years/months) |

**Example:**
- Ficus Bonsai Plant
- Brand: greenhousestore
- Type: Fruit
- Size: Small

---

### **2. Pricing Information**
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `original price` | Numeric (₹) | Listed price before discount |
| `special price` | Numeric (₹) | Discounted selling price |
| `discount` | Percentage | Discount percentage offered |

**Insights Available:**
- Price range analysis
- Discount patterns by brand/type
- Average discount rates
- Price-to-value comparison

**Example:**
- Original Price: ₹499
- Special Price: ₹199
- Discount: 60%

---

### **3. Plant Characteristics**
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `life cycle` | Categorical | Annual or Perennial plant |
| `location` | Categorical | Suitable location (Indoor/Outdoor/Both) |
| `feng shui` | Boolean | Feng Shui benefits (Yes/No) |
| `hybride` | Boolean | Hybrid or natural plant (Yes/No) |

**Use Cases:**
- Categorize plants by lifestyle needs
- Filter indoor vs outdoor plants
- Identify specialty plants (Feng Shui, Hybrid)

---

### **4. Customer Policy Information**
| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| `return policy` | Text | Return/replacement policy |

**Common Policies:**
- "No Returns Allowed"
- "7 day return"
- "Replacement only"

---

## 🎯 Project Objectives

### **Business Questions Answered:**

1. **Product Analysis**
   - What are the most common plant types?
   - How many products per brand?
   - Indoor vs Outdoor plant distribution

2. **Pricing Strategy**
   - Average product price
   - Average discount percentage
   - Price comparison across brands
   - Discount patterns by plant type

3. **Inventory Insights**
   - Popular plant sizes
   - Hybrid vs Natural plant ratio
   - Life cycle distribution (Annual/Perennial)

4. **Customer Preferences**
   - Feng Shui plants popularity
   - Most affordable plant categories
   - High-discount product segments

---

## 📊 Visualizations & Charts

### **Chart Collection (10 Charts)**

All charts are professionally named and numbered for easy reference:

#### **1. Price Analysis Charts**
- **01_Price_Distribution_BoxWhisker_Chart.PNG**
  - Type: Box & Whisker Plot
  - Shows: Price quartiles, median, outliers, and range
  - Insight: Statistical distribution of product prices

- **02_Price_Distribution_Histogram_Chart.PNG**
  - Type: Histogram
  - Shows: Frequency distribution across price ranges
  - Insight: Most common price points

#### **2. Brand & Product Analysis**
- **03_Top10_Brands_BarChart.PNG**
  - Type: Horizontal Bar Chart
  - Shows: Top 10 brands by product count
  - Insight: Market leaders and competitive landscape

- **04_Plant_Type_Distribution_PieChart.PNG**
  - Type: Pie Chart
  - Shows: Distribution across categories (Fruit, Flower, Foliage, etc.)
  - Insight: Product portfolio diversity

#### **3. Physical Characteristics**
- **05_Plant_Size_Distribution_ColumnChart.PNG**
  - Type: Column Chart
  - Shows: Small, Medium, Large size distribution
  - Insight: Inventory composition by size

- **06_Plant_LifeCycle_Distribution_DonutChart.PNG**
  - Type: Donut Chart
  - Shows: Annual vs Perennial ratio
  - Insight: Seasonal vs long-term products

#### **4. Plant Attributes**
- **07_Location_Distribution_ColumnChart.PNG**
  - Type: Column Chart
  - Shows: Indoor, Outdoor, Both categories
  - Insight: Target customer segments (apartment vs house)

- **08_Hybrid_Plants_Distribution_PieChart.PNG**
  - Type: Pie Chart
  - Shows: Hybrid vs Natural plants ratio
  - Insight: Product breeding strategy

- **09_FengShui_Plants_Distribution_BarChart.PNG**
  - Type: Bar Chart
  - Shows: Feng Shui vs Non-Feng Shui plants
  - Insight: Specialty/niche product availability

#### **5. Policy Analysis**
- **10_Return_Policy_Distribution_ColumnChart.PNG**
  - Type: Column Chart
  - Shows: Different return policy types
  - Insight: Customer-friendly policies

### **Dashboard**
- **Complete_Dashboard_View.PNG**
  - Comprehensive executive dashboard
  - All KPIs and charts in one view
  - Interactive analysis (in Excel version)

---

## 📊 Dashboard Features

The Excel dashboard (`ONLINE_BUSINESS.xlsx`) includes:

### **1. Sales & Product Insights**
- Total number of products by plant type
- Brand distribution chart
- Product count per category

### **2. Pricing Analytics**
- Original Price vs Special Price comparison
- Average discount by category
- Price range distribution
- Most discounted products

### **3. Plant Characteristics**
- Indoor vs Outdoor vs Both (location analysis)
- Hybrid vs Non-Hybrid distribution
- Annual vs Perennial plants
- Feng Shui plants count

### **4. Inventory Overview**
- Plant size distribution (Small/Medium/Large)
- Plant age distribution
- Brand-wise product count
- Return policy breakdown

---

## 🛠️ Tools & Technologies Used

- **Microsoft Excel** - Dashboard creation & pivot tables
- **CSV** - Data storage format
- **Data Analysis** - Pivot tables, charts, conditional formatting
- **Data Visualization** - Charts, graphs, KPIs

---

## � Pivot Tables & Exported Data

The project includes **12 CSV files** exported from Excel pivot tables for further analysis:

| File Name | Description |
|-----------|-------------|
| `DATA.csv` | Complete dataset with all 400 products |
| `DASHBOARD.csv` | Dashboard summary data |
| `box and whisker.csv` | Price statistics for box plot |
| `HISTOGRAM.csv` | Price frequency distribution data |
| `top 10 brand.csv` | Top brands by product count |
| `plant type chart by count.csv` | Product count per plant type |
| `plant size chart by count.csv` | Product count per size category |
| `life cycle chart by count.csv` | Annual vs Perennial counts |
| `location chart by name.csv` | Indoor/Outdoor/Both distribution |
| `hybride chart by count.csv` | Hybrid vs Natural plant counts |
| `feng shui chart by count.csv` | Feng Shui vs Non-Feng Shui counts |
| `return policy chart by count.csv` | Return policy distribution |

**Use Cases:**
- Import into Python/R for advanced analytics
- Create custom visualizations
- Perform statistical analysis
- Build machine learning models

---

## �🚀 How to Use This Project

### **Step 1: View the Data**
1. Open `Dataset/Online Business Dataset.csv` in Excel or any spreadsheet tool
2. Review the 400 product records with 13 columns

### **Step 2: Explore the Dashboard**
1. Open `Excel_Workbook/ONLINE_BUSINESS.xlsx`
2. Navigate through different sheets:
   - Dashboard (main view)
   - Pivot tables (data summaries)
   - Charts (visualizations)

### **Step 3: View Individual Charts**
1. Browse `Visualizations/Charts/` folder
2. Charts are numbered 01-10 for logical sequence
3. Each filename describes the chart type and purpose

### **Step 4: Access Pivot Data**
1. Check `Pivot_Tables_CSV/` folder
2. Use CSV files for custom analysis
3. Import into Python, R, or other tools

### **Step 5: Review Documentation**
- Check `Visualizations/CHARTS_DOCUMENTATION.md` for detailed chart descriptions
- View `Complete_Dashboard_View.PNG` for executive overview

---

## 📈 Key Insights

### **Pricing Insights**
- Average discount range: **44% - 84%**
- Most products priced between **₹120 - ₹279** (special price)
- Original price range: **₹299 - ₹799**

### **Product Insights**
- **Hybrid plants** are more common
- **Small-sized plants** dominate the inventory
- Most plants are suitable for **Both** indoor and outdoor
- Majority are **Annual** plants

### **Brand Insights**
- Multiple brands represented (greenhousestore, Cloud Farm, UGAOO, etc.)
- Each brand has unique pricing strategies
- "No Returns Allowed" is the most common policy

---

## 🔍 Data Cleaning Notes

The dataset is **relatively clean** but may contain:
- Extra unnamed columns from Excel exports
- Duplicate price columns
- Special characters in price fields (₹)
- Inconsistent return policy text

**Recommended Cleaning:**
- Remove unnamed/duplicate columns
- Standardize price formats
- Normalize return policy text
- Handle missing values (if any)

---

## 📌 Use Cases

### **For Business Owners:**
- Optimize pricing strategies
- Identify best-selling categories
- Plan inventory based on demand

### **For Data Analysts:**
- Practice Excel dashboard creation
- Learn e-commerce data analysis
- Build visualization skills

### **For Marketing Teams:**
- Identify promotional opportunities
- Target high-discount categories
- Plan seasonal campaigns

---

## 👤 Author

**Divya Thakur**
- GitHub: [@divyathakur15](https://github.com/divyathakur15)

---

## 📝 License

This project is for educational and portfolio purposes.

---

## 📞 Contact

For questions or suggestions, please open an issue on GitHub.

---

## 🌟 Acknowledgments

Dataset represents a real-world e-commerce plant business catalog, ideal for learning business analytics and Excel dashboard development.

---

**Last Updated:** March 2026
