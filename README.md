HR Analytics Dashboard

ABOUT PROJECT :

The HR Analytics Dashboard is a Power BI-based project that provides insightful visualizations and analysis of human resources data. It offers HR professionals a comprehensive overview of key metrics and trends, enabling data-driven decision-making to optimize HR processes and improve employee engagement.

With this dashboard, HR professionals gain crucial insights into key areas such as Employee Count, Attrition Trends, Demographics, Job satisfaction levels, and more.

HR teams can use its capabilities to make smart decisions and effectively manage workforce.


Technologies Used :

📈 Power BI

🔢 Excel

Steps Overview :
Data subset collected from online.
Understanding the Data.
Data Cleaning & Finding Missing values.
Data Visualization.

DASHBOARD CONTENT :

KPI's such as

Employee Count : This provides a snapshot of the total number of employees in organization.

Attrition Count : This indicates the number of employees who have left the company.

Attrition Rate : This calculates the percentage of employees who have left, relative to the total employees count.

Average Years : This shows the avg years of the Employees.

Average Age : This shows the average Age of the Employees.

Charts

Attrition by EducationalField:

This donuts chart represents the attrition rate by educationalfields. It helps determine if there are any specific education fields with higher attrition rates.


Number of Employees By Age Group:

By creating age groups using clustered column chart, this bar graph illustrates the distribution of employees across different age ranges. It helps identify age-related trends in workforce.


Job Satisfaction Rate:

The matrix chart showcases job satisfaction ratings for different job roles or positions. It enables us to identify areas of high or low job satisfaction within organization.


Attrition by Salary Slab:

The bar chart represents the attrition rate by Salary Slab. It helps determine if there are any specific SalarySlab with higher attrition rates.


Attrition by JobRole:

This bar graph presents the attrition rates Job Role. It helps determine if there are any JobRole with higher attrition rates.


Attrition Rate Years At Company:

The Line chart show the attrition rates segmented by Years At Company. It provides a visual breakdown of attrition patterns based on attrition and years at company.


Dashboard Overview :
The HR Analytics Dashboard is a powerful Power BI-based tool designed to provide HR professionals with comprehensive insights into key HR metrics and trends. It combines visually appealing and interactive visualizations to enable data-driven decision-making, optimize HR processes, and enhance employee engagement.

By leveraging the dashboard's key performance indicators (KPIs), HR professionals can track and analyze critical workforce data in real-time. This empowers them to identify patterns, trends, and potential areas of improvement within the organization.

The dashboard includes various HR analytics charts and graphs. The Department-wise Attrition Pie Chart provides an overview of attrition distribution across departments. The No. of Employees by Age Group Column Chart displays age demographics within the organization, and the Job Satisfaction Rate Heat Map Chart highlights satisfaction levels across roles and departments. Additionally, the Education Field-wise Attrition Bar Graph shows attrition rates by educational background, and the Attrition Rate by Gender for Different Age Groups Donut Chart offers insights into attrition patterns across gender and age groups.

The HR Analytics Dashboard offers a user-friendly interface, empowering HR professionals to explore the data interactively, filter information, and gain deeper insights. With this valuable tool, HR teams can make informed decisions, proactively address workforce challenges, and ultimately foster a positive work environment.

Features

Employee Demographics: Visualize employee distribution by age, gender, department, and more.

Attrition Analysis: Analyze employee attrition rates and identify key factors contributing to attrition.

Performance Metrics: Track employee performance metrics and identify high and low performers.

Predictive Modeling: Implement machine learning models to predict employee attrition and other HR metrics.


Data
The data used in this project includes various HR-related datasets. These datasets should be placed in the data/raw/ directory. The data processing script will handle cleaning and preprocessing.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request. Please follow the project's code of conduct.




HR Analytics Dashboard
Project Overview
The HR Analytics Dashboard is designed to provide comprehensive insights into human resources data, enabling organizations to make informed, data-driven decisions. The dashboard leverages Python and various data analysis and visualization libraries to offer a user-friendly interface for exploring key HR metrics.

Table of Contents
Project Structure
Installation
Usage
Features
Data
Contributing
License
Acknowledgements
Project Structure
The project is organized as follows:

css
Copy code
HR-Analytics-Dashboard/
│
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
│   ├── data_processing.py
│   ├── visualization.py
│   └── dashboard.py
├── README.md
├── requirements.txt
└── LICENSE
data/: Directory containing raw and processed datasets.
notebooks/: Jupyter notebooks for exploratory data analysis and model development.
src/: Source code for data processing, visualization, and dashboard implementation.
README.md: Project documentation.
requirements.txt: List of dependencies required for the project.
LICENSE: License information for the project.
Installation
To run the HR Analytics Dashboard locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/hr-analytics-dashboard.git
cd hr-analytics-dashboard
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Prepare the data:

Place the raw HR datasets in the data/raw/ directory.
Run the data processing script to preprocess the data:
bash
Copy code
python src/data_processing.py
Run the dashboard:

Launch the dashboard using the following command:
bash
Copy code
python src/dashboard.py
Open your web browser and go to http://localhost:8050 to view the dashboard.
Features
Employee Demographics: Visualize employee distribution by age, gender, department, and more.
Attrition Analysis: Analyze employee attrition rates and identify key factors contributing to attrition.
Performance Metrics: Track employee performance metrics and identify high and low performers.
Predictive Modeling: Implement machine learning models to predict employee attrition and other HR metrics.
Data
The data used in this project includes various HR-related datasets. These datasets should be placed in the data/raw/ directory. The data processing script will handle cleaning and preprocessing.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request. Please follow the project's code of conduct.
