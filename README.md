📊 Dynamic Pricing Analysis using Pandas and Matplotlib

This project demonstrates how to analyze and simulate dynamic pricing strategies using Python, Pandas, and Matplotlib. It is designed to be beginner-friendly, with code that is extensively commented for easy learning and understanding.

📌 What This Project Does
1. Reads pricing and sales data from a dataset.
2. Converts week-based date info into a real datetime format.
3. Calculates weekly average prices of products vs. competitor pricing.
4. Computes price elasticity of demand to understand how price affects sales.
5. Visualizes elasticity trends using Matplotlib.
6. Estimates sales for both our store and a simulated competitor.
7. Segments products into Low, Medium, and High based on their average price.
8. Calculates elasticity for each segment to see which group is more price-sensitive.
9. Simulates a dynamic pricing model that slightly increases or decreases prices for certain segments.
10. Compares results between static and dynamic pricing strategies.

🧠 Key Concepts Covered
1. Pandas DataFrame Operations 
Grouping, merging, filtering, and aggregating data.

2. Price Elasticity of Demand
A formula to measure how much sales quantity changes when price changes: Elasticity (Ed) = (% change in quantity demanded) / (% change in price)

3. Dynamic Pricing Simulation
Applying rules like price increases/decreases to test business outcomes.

4. Data Visualization
Using plots to understand trends over time and in comparison to competition.

📦 Requirements

To run this notebook, you’ll need:

1. Python 3.x
2. Jupyter Notebook (or any compatible Python IDE)
3. Pandas
4. Matplotlib

Install requirements using:

bash:
pip install pandas matplotlib

▶️ How to Run
1. Clone the repo or download the .ipynb notebook.
2. Open it using Jupyter Notebook or Google Colab.
3. Run the code cells one by one.
4. The code will guide you with comments and outputs at each step.

🔍 Acknowledgement

This project was made for learning purposes and was inspired by
https://amanxai.com/2024/07/22/price-optimization-using-python/