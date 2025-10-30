# Project-Samarth
## Intelligent Q&A System for Agricultural Insights


Developed by: Diguvamiddi Pranathi
College: Mohan Babu University, Tirupati
Course: MCA (Master of Computer Applications)

# Project Overview

This project is my submission for Project Samarth, where the goal is to design an intelligent Q&A system that can answer real-world questions about India’s agricultural economy and its relationship with climate patterns using authentic datasets from data.gov.in
.

I built a working prototype that connects crop production data and rainfall data to generate data-backed insights. The idea is to help policymakers, researchers, and students easily understand how climate factors like rainfall impact agricultural production.

# Objective

My main aim was to create a small but complete system that can:

Read and combine government datasets.

Understand and answer analytical questions.

Show results clearly with charts and source citations.

Be expandable into a chat-based Q&A tool later.

# Data Used

I used two open datasets available on data.gov.in

Crop Production Data – From the Ministry of Agriculture & Farmers Welfare

Columns: State, District, Crop, Year, Production (in tonnes)

Rainfall Data – From the India Meteorological Department (IMD)

Columns: Subdivision (State), Year, Annual Rainfall (in mm)

Both were cleaned, renamed, and merged using Python to create a single, combined dataset for analysis.

# Tools and Technologies
Task	Tools Used
Programming	Python
Data Handling	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Modeling	Scikit-learn (Linear Regression)
Data Storage	CSV files
Future Deployment	Flask / Gradio for chat interface
# Project Workflow
1️⃣ Data Collection

Downloaded and loaded the rainfall and crop production datasets using Pandas.

2️⃣ Data Cleaning

Renamed columns (like converting “SUBDIVISION” → “State_Name”), dropped missing values, and standardized the data format.

3️⃣ Data Integration

Merged both datasets on State and Year, so that every record of crop production is linked with rainfall in that state for the same year.

4️⃣ Analysis & Visualization

Created graphs and correlation plots to see how rainfall affects crop yield.
For example: when rainfall increases, does production also increase?

5️⃣ Predictive Modeling

Trained a simple Linear Regression model to predict crop production based on rainfall.
This is a basic start for data-driven forecasting.

6️⃣ Q&A System Prototype

Wrote simple query functions that answer user-like questions such as:

“Compare average rainfall in Andhra Pradesh and Karnataka.”

“Which district has the highest rice production?”

“Show the production trend for Maize over the last 10 years.”

7️⃣ Result Presentation

Displayed all results with visual graphs and mentioned the data source for every insight.
Saved the final merged dataset as final_dataset.csv for traceability.

# Example Insights

✅ Average rainfall comparison between two states.
✅ Top 5 most produced crops in a region.
✅ Correlation graph between rainfall and crop production.
✅ Year-wise trend analysis for a crop type.

# Why This Project Matters

Agriculture in India is deeply affected by weather patterns.
By connecting climate and production data, this system helps show:

How rainfall trends affect crop yields.

Which regions produce more under certain conditions.

What data-driven decisions can improve policy planning.

# Core Values

Accuracy: Data is taken directly from official government portals.

Transparency: Each insight shows which dataset and year it came from.

Privacy: All analysis happens locally — no external servers or APIs.

Scalability: The system can easily include more datasets in the future.

# Future Plans

 Build a Flask-based web app where users can type natural language questions.
 Add live data fetching from data.gov.in through APIs.
 Integrate an AI chatbot to interpret more complex questions.
 Create interactive dashboards using Power BI or Streamlit.

# About Me

Hi, I’m Diguvamiddi Pranathi, an MCA student from Mohan Babu University, Tirupati.
I’m passionate about Data Science, Machine Learning, and real-world analytics.
This project helped me combine my technical learning with meaningful, practical insights.

📧 Email: diguvamiddipranathi@gmail.com
