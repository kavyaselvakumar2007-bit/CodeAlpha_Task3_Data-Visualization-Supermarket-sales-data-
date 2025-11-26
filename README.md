🛒 Supermarket Sales Data Visualization

                       This project is part of my work for the CodeAlpha Data Analytics Internship (Task 3).

The objective of this task is to visualize supermarket sales data and draw useful business insights from it.

📌About the Dataset

    The dataset originally consists of four Annex files containing:

    Item codes and names

    Sales and quantity information

    Wholesale prices

    Loss (or wastage) percentage

Annex 2 contained a very large number of rows. For practical processing and visualization, a random sample of 100,000 records was taken from it and combined with the remaining files using Item Code.

The final processed data used for visualization is saved as:
data/final_supermarket_sales.csv

Visualizations in This Project

The notebook includes the following charts:

1. Top Selling Products
   Identifies the products with the highest total sales quantity.

2. Wholesale Price Distribution
   Shows the overall range of prices in the supermarket.

3. Loss Rate Distribution
   Helps understand how much wastage occurs for different items.

4. Price vs Loss Rate (Scatter Plot)
   Examines whether high-priced items have less wastage.

5. Correlation Heatmap
   Displays the relationships between numerical variables such as quantity, price and loss percentage.

Each chart focuses on a specific pattern that may help decision making in areas like pricing, inventory, storage, or promotional strategy.

🛠 Tools & Technologies

🐍 Python

📘 Pandas

📊 Matplotlib

🎨 Seaborn

📓 Jupyter Notebook

🚀 How to Run the Notebook

     1. Download or clone this repository.


     2. Install required libraries (if not already installed):

     pip install pandas matplotlib seaborn


     3. Open the notebook:

     Task3_Supermarket_Visualization.ipynb


     4. Run all cells to generate the graphs.

All generated images are stored in the images/ folder.

📌Project Overview

This task focuses on data cleaning, merging, sampling, and effective visualization to derive meaningful business interpretations from sales and inventory data. The main goal was not building a prediction model, but visually understanding how sales, pricing and wastage interact in a supermarket environment.

👩‍💻 Internship Details

Organization: CodeAlpha
Domain: Data Analytics
Task: Exploratory Data Analysis
Intern: Kavya Dharshini S
