# 🧠 Jobs Dataset Analysis | Python + Pandas + Seaborn

This project provides a detailed exploratory analysis of a real-world job listings dataset. It uncovers hiring trends, top companies, required skills, and experience distributions using Python’s powerful data analysis libraries.

---

## 📂 Dataset Overview

- **File**: `jobs.csv`
- **Fields Include**:
  - Job Role
  - Company
  - Location
  - Salary
  - Experience
  - Reviews & Rating
  - Responsibilities
  - Posted On

---

## 📈 What’s Inside

### 🔹 Step 1: Data Cleaning & Preparation
- Renamed misspelled columns
- Extracted experience range (min/max)
- Cleaned review counts
- Parsed textual features

### 🔹 Step 2: Exploratory Data Analysis
- Most common job roles & companies hiring
- Locations with highest postings
- Company ratings & reviews
- Required experience distributions

### 🔹 Step 3: Visual Insights
- Bar graphs, histograms, heatmaps
- Timeline analysis for job posts
- Keyword extraction from responsibilities

### 🔹 Step 4: Feature Engineering
- Created `exp_min` and `exp_max`
- Classified job levels: *Fresher, Junior, Mid-Level, Senior*

---

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for keyword analysis)

---

## 📤 Output

- ✅ Cleaned Dataset → `cleaned_jobs.csv`
- ✅ Visualizations & Analysis → Jupyter Notebook

---

## 💼 Use Cases

✅ Resume/Portfolio Project  
✅ Demonstrates real-world data wrangling  
✅ Good for Data Analyst/Data Scientist roles  

---

## 📁 How to Run

```bash
git clone https://github.com/yukti-says/Data-Analytics-Projects.git
cd jobs-data-analysis
pip install -r requirements.txt
jupyter notebook
