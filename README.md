# 📱 Amazon Cell Phones Data Analysis

## 📌 Overview
This project analyzes Amazon cell phone data to uncover insights into customer preferences, pricing trends, and product ratings. The analysis is performed using **Python (Pandas, Matplotlib, Seaborn, NumPy)**, and the results are visualized in a Jupyter Notebook.

## 📊 Dataset Information
- **File Name**: `Amazon_Cell_Phones.csv`
- **Source**: Amazon cell phone listings and customer reviews
- **Description**: The dataset contains detailed information about various cell phones available on Amazon, including brand, price, ratings, and customer feedback.

### 🔹 Dataset Columns:
- `Brand`: The brand of the phone
- `Model`: The specific model name
- `Price`: The price of the phone in USD
- `Rating`: Average customer rating (out of 5)
- `Reviews_Count`: Number of customer reviews
- `Storage`: Internal storage capacity
- `RAM`: RAM size in GB
- `Battery_Life`: Estimated battery life in hours
- `Screen_Size`: Display size in inches
- `Camera`: Camera specifications
- `Release_Year`: Year of release
- `Processor`: Chipset/processor used in the phone

## 📂 Project Structure
📂 Amazon-Cell-Phones-Analysis │-- 📄 README.md (This file) │-- 📂 Data │ │-- Amazon_Cell_Phones.csv (Raw dataset) │-- 📂 Notebooks │ │-- AmazonCellPhones_DataAnalysis.ipynb (Data analysis and visualizations) │-- 📂 Scripts │ │-- analysis_script.py (Python script for data processing and visualization) │-- 📂 Results │ │-- figures/ (Folder containing generated plots)


## 🚀 Key Insights & Analyses
- **Price vs. Rating**: Investigates if higher-priced phones receive better customer ratings.
- **Brand Popularity**: Identifies the most reviewed and highly rated brands.
- **Storage & RAM Trends**: Examines the impact of RAM and storage on pricing.
- **Customer Preferences**: Analyzes reviews to determine key features that influence purchases.

## 🛠️ Technologies Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Jupyter Notebook**
- **Data Cleaning & Visualization**
- **Statistical Analysis**

## 🔄 How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Vighnesh3232/Amazon-Cell-Phones-Analysis.git
   cd Amazon-Cell-Phones-Analysis

## Install dependencies
`pip install pandas numpy matplotlib seaborn jupyter`

## Run the Jupyter Notebook
`jupyter notebook Notebooks/AmazonCellPhones_DataAnalysis.ipynb`

## Run the Python script for analysis
`python Scripts/analysis_script.py`

📈 Outputs
Visualizations & Graphs: Stored in the Results/figures/ folder.
Processed Insights: Presented in Jupyter Notebook.
