# Crop-Production-Analysis(Python)
This project provides an in-depth data analysis of crop production patterns across Indian states and years using Python and data visualization libraries like Matplotlib and Seaborn. The dataset includes information on crop types, production volumes, cultivated areas, seasons, and regional statistics. It helps identify trends, performance of different states, and yield efficiency across various crops like rice, wheat, coconut, potato, onion, and maize.

📁 Dataset Information
Source: crop_production.csv (uploaded via Google Colab)

Rows: 246,091 entries

Columns: 7 features

State_Name

District_Name

Crop_Year

Season

Crop

Area

Production

🔍 Exploratory Data Analysis (EDA)
Performed initial analysis including:

Checking for null values and data cleaning (dropna)

Identifying unique crops and states

Summary statistics using .describe()

Added a derived feature: Yield = Production / Area

📊 Visualizations
Key plots generated:

Bar plots of total production and yield per state

Production and yield trends across crop years

Yield by season

Crop-specific analysis (Rice, Wheat, Coconut, Potato, Onion, Maize)

🧠 Key Insights
Kerala has the highest crop production.

Puducherry has the highest yield (production per area).

Rice performs best in Rabi season and Chandigarh in terms of yield.

Punjab is the top wheat producer, especially in Rabi.

Mizoram stands out for coconut yield despite Andhra Pradesh being the top producer.

West Bengal leads in potato production.

Gujarat and Maharashtra dominate onion production.

Maize production sees a wide variance, with interesting seasonal trends.

📦 Libraries Used
pandas for data loading and preprocessing

numpy for numerical operations

matplotlib & seaborn for data visualization

📌 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/crop-production-analysis.git
cd crop-production-analysis
Install required libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn
Run the notebook:
Open ml_miniproject.ipynb in Jupyter or Google Colab.

📈 Future Scope
Implement predictive models to forecast crop yields.

Correlate with rainfall, temperature, and climate datasets.

Deploy as a dashboard using Streamlit or Dash for farmers and policymakers.

