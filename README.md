🛒 E-Commerce Recommendation Engine

The E-Commerce Recommendation Engine is a Streamlit-based web application that performs Market Basket Analysis on e-commerce transactional data using the Apriori algorithm and generates intelligent product recommendations.
The system is designed with a clean and intuitive interface for business stakeholders, enabling real-time analysis, interactive filtering, and automated insight generation.

💡 Features

📁 File Upload: Upload your .xlsx transaction dataset

📊 Data Visualization: View top 10 frequent products with support values

🧠 Apriori Algorithm: Discover frequent itemsets and association rules

🎯 Product Recommendations: Get smart suggestions based on customer buying patterns

⚙️ Interactive Filters: Adjust minimum Support, Confidence, and Lift thresholds

📘 Explainable AI Section: Understand key metrics like Support, Confidence, and Lift

💼 Business Insights: Actionable recommendations for product bundling and cross-selling

📁 Files Included
File Name	Description
app.py	Main Streamlit application code
README.md	Project documentation
⚙️ Requirements

Install the required dependencies using pip:

pip install streamlit pandas mlxtend matplotlib plotly openpyxl

▶️ How to Run the Application

Run the Streamlit app using:

py -m streamlit run app.py

Then open your browser and go to:

http://localhost:8501

📊 Input Dataset Format

The dataset should contain transactional data with the following columns (or similar):

InvoiceNo / Invoice

Description / Product

Quantity

CustomerID / Customer ID

InvoiceDate

The system automatically detects column variations for compatibility with different datasets.
