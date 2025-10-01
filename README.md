**Chicago Divvy Bikeshare 2024 – Exploratory Data Analysis**

Project Overview



This project analyzes the 2024 Chicago Divvy bikeshare dataset to explore user behavior patterns, seasonal trends, and operational insights.

The analysis was conducted in Python (Google Colab) and the results were summarized into datasets and reports, with visualizations also prepared for Tableau dashboards.



Objectives:



Identify seasonal and monthly usage trends



Compare behavior between casual riders and annual members



Analyze trip duration, weekday vs weekend patterns, and hourly usage



Prepare clean summary datasets for visualization in Tableau



📂 Repository Structure

project-name/

│── requirements.txt              # Python dependencies

│── README.md                     # Project overview (this file)

│── .gitignore                    # Ignore unnecessary files

│

├── notebooks/

│   └── Bikeshare\_EDA.ipynb       # Main analysis notebook

│

├── summary/

│   ├── monthly\_summary.csv       # Trips per month

│   ├── member\_summary.csv        # Member vs casual trips

│   └── heatmap\_summary.csv       # Usage by day/hour

│

├── reports/

│   ├── Chicago\_Divvy\_Bikeshare\_2024\_Report.pdf   # Final analysis report

│   └── Chicago\_Divvy\_Bikeshare\_2024\_Report.docx

│

└── data/ (optional, if included)

    ├── raw/                      # Original monthly datasets (Jan–Dec 2024)

    └── processed/                # Cleaned datasets





**Key Findings**



Seasonality



Trip volume peaks in July–August (summer)



Lowest ridership in January–February (winter)



User Types



Members take more trips overall, mostly short commuting rides.



Casual riders take fewer trips but with longer durations, especially on weekends.



Hourly \& Daily Patterns



Morning and evening commuting peaks for members



Casual riders more active mid-day and weekends





**Tools \& Technologies**



Python: pandas, matplotlib, seaborn



Google Colab for analysis



Tableau for interactive dashboard visualization





**Deliverables**



Notebook: complete EDA process (/notebooks)



Summary Datasets: ready for Tableau (/summary)



Report: business-oriented analysis in PDF/Word (/reports)



Tableau Dashboard (https://public.tableau.com/app/profile/marsel.luase/viz/ChicagoDivvyBikeShare2024Analysis/BikeshareOverview)





**How to Use**



Clone this repository



git clone https://github.com/achelllu/bikeshare-2024-analysis

cd bikeshare-2024-analysis





**Install dependencies**



pip install -r requirements.txt





Open the notebook in Jupyter/Colab and run step by step



Dashboard Preview



https://public.tableau.com/app/profile/marsel.luase/viz/ChicagoDivvyBikeShare2024Analysis/BikeshareOverview



**Author**



Prepared by \[Marsel Luase]

Contact: luaseachell@gmail.com



🔗 LinkedIn / Portfolio: \[https://www.linkedin.com/in/marsel-pongdatu-luase-24249836a/]

