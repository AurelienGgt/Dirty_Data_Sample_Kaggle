<h1 align="center">CRM Data Cleaning</h1>

---

## 🎯 Project Objective

Clean and transform the CRM-like dataset using Python(excel will be easier here but the point was to show in python. In excel we can unpivot and it will show you the results too).

---

## 📂 Dataset

**Source**: [Dirty Data Sample (Kaggle)](https://www.kaggle.com/datasets/shivavashishtha/dirty-data-sample)  

**Overview**:  
This dataset simulates a CRM-style customer database containing fake user records. It intentionally includes real-world data quality issues — such as duplicates, nulls making it ideal for practicing cleaning .

### 📊 Key Facts

| Attribute               | Value                        |
|------------------------|------------------------------|
| 📄 Rows (records)       | 826                        |
| 📈 Columns (features)   | 16                            |
| 📁 File Format          | Xlsx (`dirtydata.xlsx`)         |
| 🧪 Missing Data         | Yes (random NaNs throughout)  |
| ♻️ Duplicates           | Yes (entire and partial rows) |
| 💬 Languages            | English                |
| ⚠️ Errors Simulated     | Data entry & validation errors|


**💡 Note**: The presence of diverse errors makes it an excellent playground for showcasing:

---

## 🧰 Tech Stack & Tools

- **Python**: cleaning : pandas

---

## 🔄 Workflow Overview

1. **Profiling data**: type mismatches, duplicates  
2. **Cleaning rules**:
   - Unpivot the data in python 
   - Remove duplicates

---

## 🚀 Project Goals

- Showcase practical cleaning of “dirty” data common in CRM systems  
- Provide documentation powered by ChatGPT

---

## 📁 Folder Structure

| Folder/File                    | Description                                                |
|-------------------------------|------------------------------------------------------------|
| 📂 `data/`                    | Contains raw data, including CRM-style messy datasets      |
| └── 📄 `Dirty Data Sample.xlsx`| The unclean, NaN-filled dataset used for cleaning practice |
| 📂 `notebooks/`               | Exploratory scripts and profiling notebooks                |
| ├── 📘 `cleaning_profile.ipynb` | Visual EDA and profiling via pandas-profiling              |
| 📄 `README.md`                | Project documentation and structure                 

---

## 🤖 Credits

- ChatGPT (OpenAI) for workflow explanations, and framing. 
- Dataset source: Kaggle – Dirty Data Sample

---
