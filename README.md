# Python Projects
# Task 1: Data Cleaning and Preprocessing

## 🎯 Objective
The goal of this task is to clean and prepare a raw dataset that may contain:
- Missing values
- Duplicate entries
- Inconsistent formats  
so that the dataset is ready for analysis or modeling.  

The **Netflix dataset** was chosen for this task.

---

## 🛠 Steps Performed

### 1. Handle Missing Values
- Filled `director` column with **"Unknown"** where data was missing.
- Filled `cast` column with **"Not Available"** where data was missing.
- Filled `country` column with **"Unknown"** where data was missing.

### 2. Remove Duplicate Rows
- Checked for duplicate entries.
- Removed duplicate rows using Pandas `.drop_duplicates()`.

### 3. Standardize Text Values
- Standardized country names (e.g., converted to **title case** like *United States*, *India*).
- Stripped extra spaces.

### 4. Convert Date Formats
- Converted `date_added` column to **datetime format** for consistency.

### 5. Rename Columns
- Changed all column headers to **lowercase** with **underscores** instead of spaces.  
  Example: `Date Added` → `date_added`

---

## 📊 Final Dataset
- Shape: **200 rows × 12 columns**  
- All missing values handled.  
- No duplicate rows remain.  
- Data is consistent and ready for analysis.  

---

## 📁 Files Included
- `Netflix_Cleaned.csv` → Cleaned dataset (ready for analysis)  
- `README.md` → This summary file  

---

✅ Dataset is now clean, consistent, and ready for further analysis or visualization.

