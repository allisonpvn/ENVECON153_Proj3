# ENVECON153_Proj3

Overview
This project investigates dietary habits and nutritional adequacy for the elderly population (ages 50+) in four African countries: Uganda, Tanzania, Senegal, and Mali. It includes data processing, analysis, and visualization to derive meaningful insights into consumption behavior and adequacy of key nutrients.

Group Members
Allison Nguyen

Fari Santoso

Katy Qin

Johann Dicken

Shrija Malla

Avani Agarwal

Project Structure
📁 Sections
Deliverable [A]: Population of Interest

Identifies and filters data for elderly individuals in the target countries.

Data Setup

Imports required modules and reads in datasets from Google Sheets.

Data Filtering

Applies age and country filters to isolate the target population.

Estimation

Performs calculations on dietary energy needs and intake.

Gamma Visualizations

Displays gamma distribution plots for different food items and population groups.

Deliverable [B]: Nutritional Content and Adequacy

Assesses the adequacy of diet based on key nutrients.

🧰 Requirements
Install necessary dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Ensure you have access to the required Google Sheets for country datasets using appropriate APIs or tokens.

📊 Data Sources
The data is retrieved from Google Sheets:

Uganda: 1yFWlP5N7Aowaj6t2roRSFFUC50aFD-RLBGfzGtqLl0w

Tanzania: 1tlNUxe2hY2DAOsv6u7R7yC_CiBcr05cXXQiRWBlEHEo

Senegal: 1cCszXB2Irc1Dp9zyIQgeu4OVWy9ZqvJbTielK8h9PLk

🖼️ Outputs
The notebook generates:

Bar charts and visualizations for gamma values by gender and age.

Sorted nutrient adequacy plots across countries.

Summaries of nutritional gaps.

📌 Notes
Be sure to use the CFEDemands Python module, which may be project-specific.

Some datasets may be large; make sure to filter before visualization to reduce clutter.

