# COVID19-DASH

COVID-19 Data Explorer Dashboard

# 📊 Project Overview

The COVID-19 Data Explorer Dashboard is an interactive data visualisation platform designed to provide real-time insights into the impact of the COVID-19 pandemic across the UK.

Developed as part of a personal project with an interest in learning software development. This project demonstrates the use of public health data APIs, data processing techniques, and interactive visualisation tools to support data-driven decision-making.

The dashboard focuses on:
	•	Daily and cumulative COVID-19 deaths over time
	•	Age and sex distribution analysis
	•	Regional comparisons
	•	Downloadable structured datasets

The goal of this project is to transform raw public health data into accessible, interactive, and actionable insights.

⸻

# 🎯 Objectives
	•	Provide real-time access to official UK COVID-19 statistics
	•	Enable users to explore trends through interactive visualisations
	•	Analyse demographic impact (age and sex breakdown)
	•	Support researchers and policymakers with exportable datasets
	•	Present complex public health data in an intuitive and user-friendly format

⸻

# 🗂 Data Source

Data is sourced from the UK Government’s public health data API, previously maintained by Public Health England (PHE).

The dashboard retrieves structured data directly from the official API to ensure:
	•	Accuracy
	•	Reliability
	•	Timeliness

⸻

# ⚙️ Key Features
	•	✅ Real-time data retrieval from UK Government API
	•	📈 Interactive charts for daily and cumulative deaths
	•	👥 Age and sex distribution breakdowns
	•	🗺 Region-based filtering
	•	📅 Date range filtering
	•	⬇ Downloadable raw datasets (JSON and Pickle formats)

⸻

# 🛠 Technical Implementation

(Edit this section based on what you used — here’s a strong generic template.)

### Technologies Used:
	•	Python
	•	Pandas
	•	Requests (API integration)
	•	Plotly / Matplotlib / Seaborn (Data visualisation)
	•	Dash / Flask / Streamlit (Web framework, if applicable)
	•	JSON data processing

### Core Components:
	1.	API Integration
	•	Fetches live COVID-19 data from UK Government API
	•	Handles data parsing and transformation
	2.	Data Processing
	•	Cleans and structures raw JSON responses
	•	Aggregates daily and cumulative metrics
	•	Groups demographic data by age bands and sex
	3.	Visualisation Layer
	•	Time-series charts for trend analysis
	•	Interactive filters for region, age, and date
	•	Responsive dashboard layout

⸻

# 📊 Dashboard Insights

### The dashboard allows users to:
	•	Identify peak infection and mortality periods
	•	Compare regional trends
	•	Analyse demographic vulnerability patterns
	•	Track cumulative mortality progression

By presenting structured public health data visually, the project highlights how analytics can support crisis monitoring and evidence-based policy.

# 🚀 How to Run the Project
# Clone the repository
git clone https://github.com/yourusername/covid-dashboard.git

# Navigate into project directory
cd covid-dashboard

# Install dependencies
pip install -r requirements.txt

# Run application
python app.py


Then open your browser and navigate to:
http://127.0.0.1:5000
(Adjust based on your framework.)

# 📁 Project Structure
├── app.py
├── data/
├── static/
├── templates/
├── requirements.txt
└── README.md

# 💡 Skills Demonstrated
	•	API integration and data retrieval
	•	Data cleaning and transformation
	•	Time-series analysis
	•	Data visualisation and storytelling
	•	Full-stack dashboard development
	•	Public sector data handling
	•	Analytical problem-solving

⸻

# 📌 Academic Context

This project was completed as part of my interest in exploring programming. It demonstrates the practical application of:
	•	Data engineering principles
	•	Statistical analysis
	•	Software development
	•	Interactive systems design

⸻

# 🔮 Future Improvements
	•	Deployment to AWS (EC2 or Elastic Beanstalk)
	•	Docker containerisation
	•	CI/CD pipeline integration
	•	Expanded metrics (cases, hospitalisations, vaccination rates)
	•	User authentication and saved preferences
