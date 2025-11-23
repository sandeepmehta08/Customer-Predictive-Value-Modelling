# 📊 Customer Predictive Value Modelling

This project focuses on analyzing customer purchasing patterns from the [Online Retail II dataset](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci/data). The goal is to explore sales behavior across products, customers, and countries, and extract meaningful insights through data cleaning, exploration, and visualization.


# 📁 About the Project

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

# 🚀 Features
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

# 📸 Demo (Sample Visuals)

Top 10 Selling Products

<img width="1184" height="450" alt="newplot" src="https://github.com/user-attachments/assets/e37ea3e3-b87f-41b3-94c9-9e0d86a15b82" />

Top 10 Countries by Sales
Identifies regions contributing the highest revenue.

<img width="1184" height="450" alt="newplot" src="https://github.com/user-attachments/assets/01d71832-e8fb-4e0b-a947-3cc391870e81" />

# 🚀 How to Run the Project

Follow these steps to run the Customer Predictive Value Modelling project on your local machine:

1️⃣ Clone the Repository
'''bash
git clone <your-repository-link>
cd <your-project-folder>
'''

Replace <your-repository-link> and <your-project-folder> with your actual GitHub details.

2️⃣ Install Required Libraries
Create a Python environment (optional but recommended):

'''python -m venv venv'''

Activate it:

Windows
'''venv\Scripts\activate'''

Mac/Linux
'''source venv/bin/activate'''


Now install the required Python libraries:
'''pip install numpy pandas plotly'''

(Plotly includes both Express and Graph Objects automatically.)

# 3️⃣ Download the Dataset

Make sure the dataset (Online Retail II) is downloaded and placed in the project folder.
If your file is zipped, extract it first.
You can also upload the dataset folder like this:

'''data/
    online_retail_II.csv'''

# 4️⃣ Open the Notebook

Launch Jupyter Notebook or VS Code:
'''jupyter notebook'''

Then open:
'''Customer_Predictive_Value_Modelling.ipynb'''

5️⃣ Run All Cells

Once the notebook is open:
- Click Run All
- Or use Shift + Enter to run each cell step-by-step
Your visualizations (Plotly bar charts & graphs) will appear inside the notebook.

6️⃣ You're Done!

You can now explore:
- Top-selling products
- Top-performing countries
- Basic customer purchase patterns
- Sales insights through interactive charts

# 📝 File Details
- notebook.ipynb:- Contains the complete data analysis workflow — from loading and cleaning the dataset to generating visual insights.
- online_retail_II.zip:- Compressed version of the dataset used in the project.
- README.md:- Documentation describing the project setup, purpose, and execution steps.
- insights_summary.pdf:- A downloadable PDF that includes all key insights, findings, and conclusions from the analysis in a clean, readable format.

Built by Sandeep Mehta
<p align="center"> <a href="https://github.com/sandeepmehta08"> <img src="https://img.shields.io/badge/GitHub-sandeepmehta08-black?logo=github&style=for-the-badge"/> </a> <a href="https://www.linkedin.com/in/sandeep-mehta-25bb99231/"> <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge"/> </a> </p>
