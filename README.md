# 📚 Key Stone Project

### Louisville Library Collection Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellowgreen)
![Git LFS](https://img.shields.io/badge/Git-LFS-lightgrey)  

A clean and friendly Python analysis of the Louisville Library dataset.  
Includes data cleaning, category mapping, and four honest, well‑designed visualizations.  
Main notebook: lv_library.ipynb  
Dataset stored with Git LFS.



 
## 🌟 Overview

This project analyzes the **Louisville Library** collection using Python.  
The notebook `lv_library.ipynb`  includes *data cleaning, category mapping, and visualizations* that explore how the library's collection has changed over time.

## 🗃️ Project files 
* `lv_library.ipynb` - main notebook with code, charts, and explanations
* `Louisville_Library.csv` - dataset used for analysis (tracked with Git LFS)
* `README.md` - project overview
## 💼 Requirements 
To tun this project, install:  

* Core Tools  

  <img src="https://img.shields.io/badge/Python-3.10%2B-4B8BBE?style=flat&logo=python&logoColor=white" />  

  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37726?style=flat&logo=jupyter&logoColor=white" />  

  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-4C9A2A?style=flat&logo=pandas&logoColor=white" />  

  <img src="https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?style=flat&logo=numpy&logoColor=white" />  
  
* Visualization 

  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-5A9?style=flat&logoColor=white" />  

* Tools  
  <img src="https://img.shields.io/badge/VS%20Code-Editor-007ACC?style=flat&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-LFS-6E6E6E?style=flat&logo=git&logoColor=white" />

 ## 🏗️ Project Structure  
📁 Project folder  
|    
├── 📕lv_library.ipynb - Main analysis notebook  
├── 🧾Louisville_Library.csv  - Dataset (Git LFS)  
├── 📘[README.md](README.md) - Project documentation  
└── 🖼️images/ - Optional folder for chart screenshots



## 🧹 Data Preparation

* Removed unnecessary columns
* Dropped duplicated rows
* Converted data types
* Checked and documented missing values
* Filtered unrealistic publication years (kept 1800-2026)

## 📋 Item Type Categories
The original dataset had **35 item types**.  
They were grouped into meaningful categories:  
- Book
- Audiobook
- Music
- Video
- Digital Reading
- Mixed Media
- Other  
This made the analysis clearer and easier to interpret.

## 📊 Visualizations  <!-- Visualization -->
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat&logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-5A9?style=flat&logoColor=white" />

1️⃣ Collection by Publication Decade  
    A line chart showing how the library's collection grew across decades.  
    
2️⃣ Collection by Location  
    A horizontal bar chart comparing item counts across library branches.
    
3️⃣ Publication Year vs Item Price  
    A scatter plot with a regression line showing how prices change over time.  
    
4️⃣ Average Item Price by Decade  
    A line chart summarizing long-term pricing trends.  


All charts follow ethical design principles: honest scale, full context, and no exaggeration. 



## 🧪 How to Run
1. Clone the repository
2. Place `Louisville_Library.csv` in the same folder as `lv_library.ipynb`
1. Open the notebook in Jupyter or VS Code
1. Run the cells top to bottom


## ⚠️ Challenges 
The CSV file was too large for standard Git, so the project uses **Git LFS** to store the dataset.
## 🚀 Future improvements
- Add more visualizations
- Explore seasonal or monthly borrwing trends
- Build an interactive dashboard  


## 🤝 Acknowledgments  
***Thanks to the Louisville Library for providing the dataset and to the open‑source Python community for the tools used in this analysis.***
  
<!-- License -->
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat" />