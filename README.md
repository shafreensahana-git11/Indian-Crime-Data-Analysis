# Indian-Crime-Data-Analysis
Exploratory data analysis of Indian crime records (2015–2023) across 5 states — trends, victim demographics, conviction rates, and rural vs urban patterns using Python, Pandas, and Seaborn.

🔍 Indian Crime Data Analysis
A data science project analyzing crime patterns across Indian states using Python. This project was completed as part of a Summer Internship at Virtual Tech Services, Chennai.

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on Indian crime data spanning from 2015 to 2023, covering 5 states, multiple districts, and 6 crime categories. The goal is to uncover trends, patterns, and insights from the dataset using statistical analysis and visualizations.

📂 Dataset
File: indian_crime_data.csv
ColumnDescriptionStateIndian state where the crime occurredDistrictDistrict within the stateYearYear of the crime record (2015–2023)Crime_TypeCategory of crimeNumber_of_IncidentsTotal incidents reportedVictims_MaleNumber of male victimsVictims_FemaleNumber of female victimsRural_AreaWhether the crime occurred in a rural area (Yes/No)ConvictionsNumber of convictions
Crime Types Covered: Theft, Assault, Murder, Rape, Cyber Crime, Kidnapping
Dataset Size: 810 records × 9 features

🛠️ Technologies Used

Language: Python 3
Environment: Jupyter Notebook
Libraries:

Pandas – Data manipulation and analysis
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical data visualization




📊 Analysis Performed

Data Preprocessing – Null value check, duplicate removal, data type inspection
Descriptive Statistics – Summary statistics using .describe() and .info()
Crime Distribution – Count plots by crime type and state
Yearly Crime Trends – Line chart showing incident trends from 2015–2023
Gender-Based Victim Analysis – Comparison of male vs female victims
Rural vs Urban Analysis – Crime occurrence by area type
Conviction Rate Analysis – Overall conviction rate calculation
Pair Plot & Joint Plot – Correlation analysis across numeric features


📈 Key Visualizations

Bar chart: Total incidents per state
Line chart: Crime trends over years
Count plot: Crime type distribution
Bar chart: Gender-based victim count
Bar chart: Rural vs Urban crime occurrences
Distribution plot: Incident number distribution
Pair plot with Crime_Type as hue


🚀 How to Run

Clone the repository

bash   git clone https://github.com/your-username/indian-crime-data-analysis.git
   cd indian-crime-data-analysis

Install required libraries

bash   pip install pandas numpy matplotlib seaborn

Launch Jupyter Notebook

bash   jupyter notebook mini_project.ipynb

Make sure indian_crime_data.csv is in the same folder as the notebook.


📁 Project Structure
indian-crime-data-analysis/
│
├── mini_project.ipynb       # Main analysis notebook
├── indian_crime_data.csv    # Dataset
└── README.md                # Project documentation

👩‍💻 Author
M. Shafreen Jakana
B.Sc Computer Science — Alagappa Government Arts College, Karaikudi
Internship at Virtual Tech Services, Ambattur, Chennai (May–June 2025)

📄 License
This project is intended for academic and educational purposes.
