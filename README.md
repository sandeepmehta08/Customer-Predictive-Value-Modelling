#  Customer Predictive Value Modelling

This project focuses on analyzing customer purchasing patterns from the [Online Retail II dataset](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data). The goal is to explore sales behavior across products, customers, and countries, and extract meaningful insights through data cleaning, exploration, and visualization.


#  About the Project

Objective

The aim of this project is to understand customer purchasing patterns and product performance by exploring sales data from an online retail store. This includes identifying top-selling products, most profitable regions, and overall sales trends.

Dataset

This project uses the [Online Retail II](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data) dataset from Kaggle, which contains:

- Transactional data
- Customer IDs
- Product descriptions
- Quantities
- Prices
- Datetime information
- Country of origin

The dataset spans December 2009 to 2011.

#  Features
✔ Data Cleaning

- Converted invoice dates to datetime format
- Removed rows with missing Customer IDs
- Created a new column representing total transaction value
- Sorted data for consistent analysis

✔ Exploratory Data Analysis

- Identified top-selling products
- Analyzed the highest revenue-generating countries
- Examined overall purchasing patterns
- Created visualizations using Matplotlib & Seaborn

✔ Visual Insights

- Bar charts for product sales
- Bar charts for country-wise performance
- Simple trend observations

#  Demo (Sample Visuals)

Top 10 Selling Products

<img width="1184" height="450" alt="newplot" src="https://github.com/user-attachments/assets/e37ea3e3-b87f-41b3-94c9-9e0d86a15b82" />

Top 10 Countries by Sales
Identifies regions contributing the highest revenue.

<img width="1184" height="450" alt="newplot" src="https://github.com/user-attachments/assets/01d71832-e8fb-4e0b-a947-3cc391870e81" />


#  Dependencies Used

- `NumPy` — for numerical operations
- `Pandas` — for data cleaning and analysis
- `Datetime` — for handling date and time values
- `Plotly Express` — for quick interactive visualizations
- `Plotly Graph Objects` — for fully customized charts

#  How to Run the Project

Follow these steps to run the Customer Predictive Value Modelling project on your local machine

1️⃣ Clone the Repository

To get started, clone this repository:
```bash
git clone <your-repository-link>
```
Navigate to the project directory:
```bash
cd <your-project-folder>
```
Replace the placeholders with your actual GitHub details.

2️⃣ Set Up a Virtual Environment

Create a virtual environment:
```bash
python -m venv venv
```

Activate it:

Windows:
```bash
venv\Scripts\activate
```

macOS/Linux:
```bash
source venv/bin/activate
```

Install required libraries:
```bash
pip install numpy pandas plotly
```

3️⃣ Download the Dataset

Place the dataset inside a folder named data/:
```bash
data/
    online_retail_II.csv
```
If your dataset is zipped, extract it before running the notebook.

4️⃣ Open the Notebook

Launch Jupyter Notebook or VS Code:
```bash
jupyter notebook
```

Then open:
```bash
Customer_Predictive_Value_Modelling.ipynb
```

5️⃣ Run All Cells

Inside the notebook:
- Click Run All, or
- Press Shift + Enter to run cells step-by-step

Your Plotly visualizations will appear inside the notebook.

6️⃣ You're Done!

You can now explore:
- Top-selling products
- Top-performing countries
- Basic customer purchase patterns
- Clean visual insights

#  File Details
- `notebook.ipynb`:- Contains the complete data analysis workflow — from loading and cleaning the dataset to generating visual insights.
- `online_retail_II.zip`:- Compressed version of the dataset used in the project.
- `README.md`:- Documentation describing the project setup, purpose, and execution steps.
- `insights_summary.pdf`:- A downloadable PDF that includes all key insights, findings, and conclusions from the analysis in a clean, readable format.

<p align="center"> <strong> Built by Sandeep Mehta </strong> </p> <p align="center"> <a href="https://github.com/sandeepmehta08"> <img src="https://img.shields.io/badge/GitHub-sandeepmehta08-black?logo=github&style=for-the-badge"/> </a> <a href="https://www.linkedin.com/in/sandeep-mehta-25bb99231/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge"/> </a> </p>
