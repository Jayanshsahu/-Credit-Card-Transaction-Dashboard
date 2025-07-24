💳-Credit-Card-Transaction-Dashboard
This Power BI project presents a Credit Card Transaction Report that analyzes revenue, transaction volume, and customer behavior across various dimensions. Designed for financial analysts and product managers, this dashboard provides actionable insights into credit card usage patterns, customer segmentation, and quarterly performance.



🧩 Problem Statement
Financial institutions face key challenges:

Lack of real-time visualization of credit card revenue, interest, and transactions.

Difficulty in understanding customer expenditure patterns and how different card categories perform.

No unified dashboard to evaluate product performance, customer education, or income segments.



🎯 Project Objectives
Build a visual dashboard to track key credit card metrics: revenue, interest, transaction amount, and volume.

Analyze expenditure trends by category, education, job type, and card type.

Monitor quarter-wise performance and identify top-performing segments.

Enable dynamic filtering to support real-time exploration and decision-making.




✅ Solution & Features
💡 Key Metrics:
Revenue: 23M

Total Interest Earned: 3.3M

Total Transaction Amount: 19M

Transaction Count: 278K



📊 Visuals & Insights:
Card Category Breakdown:

Revenue, Transactions, and Interest for Blue, Gold, Silver, and Platinum cards.

Quarterly Revenue & Volume Trends:

Bar and line combo chart showing Q1 to Q4 changes in revenue and transaction count.

Revenue by Expenditure Type:

Bills, Fuel, Entertainment, Food, Grocery, Travel.

Revenue by Customer Segment:

Education Level (e.g., Graduate = 9.6M)

Job Type (e.g., Business = 7.1M)

Card Type (e.g., Blue = 20M)

Transaction Mode (e.g., Swipe = 15M)



🎛️ Interactive Filters (Slicers):
Quarter (Q1–Q4)

Gender (M/F)

Card Category (Silver, Blue, Gold, Platinum)

Income Band (Low, Medium, High)

Start Week Filter (for time-based filtering)


🛠️ Tools & Technologies
Tool	Purpose
Power BI	Dashboard creation and analysis
DAX	Custom KPIs and measures
CSV File	Underlying customer data

🧾 Raw Dataset Summary
This dataset contains customer-level information across demographics, financial status, and service usage. It is structured as a flat table with each row representing a unique client.
<img width="951" height="378" alt="image" src="https://github.com/user-attachments/assets/5833e576-b2f6-4d2a-b600-e97d733efbb0" />



📂 File Structure

📁 Credit_Card_Report/
├── Credit_Card_Report proj .pbix    # Main Power BI dashboard
├── customer_data.csv                # Source data (CSV)
├── README.md                        # Project documentation
└── screenshots/                     # Dashboard image(s)


📸 Dashboard Preview

<img width="617" height="344" alt="image" src="https://github.com/user-attachments/assets/0dc208a6-1708-445b-8376-54750672627c" />



🚀 How to Use
Clone or download the repository.

Open the .pbix file using Power BI Desktop.

Interact with visuals and slicers for deep analysis.

Modify visuals or add your own KPIs for customization.


🔮 Future Enhancements
Predictive analysis: churn forecasting based on behavior.

Real-time data connection with SQL/Azure sources.

Embedding the dashboard into a web portal or report server.


📜 License
This project is released under the MIT License.
