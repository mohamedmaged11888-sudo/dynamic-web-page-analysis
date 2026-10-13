# dynamic-web-page-analysis
A data analysis project exploring , and business performance using Python and data visualization ,html, java script 
Jetour Quality Assurance Dashboard

An interactive, web-based Quality Assurance (QA) Dashboard designed to analyze vehicle defects, monitor quality performance, and generate actionable insights using interactive visualizations and dynamic filtering.

The dashboard combines data analytics with a modern interface to help quality teams identify defect patterns, monitor trends, and investigate areas requiring improvement.

📊 Project Overview

The Jetour Quality Assurance Dashboard transforms Excel-based quality inspection data into an interactive analytics experience.

Users can upload their Excel datasets, filter inspection records, analyze defect distributions, monitor quality metrics, and explore relationships between defects, vehicle chassis, inspectors, and production categories.

The dashboard features a modern dark interface with animated 3D visual effects, interactive charts, and a responsive layout.

✨ Key Features
1. Quality Performance KPIs

The dashboard provides four key performance indicators:

Total Defects: Total number of defect records in the filtered dataset.
Total Vehicles: Number of unique vehicles identified by chassis number.
Defects Per Unit (DPU): Average number of recorded defects per vehicle.
Top Impacted Category: Category with the highest defect count.
2. Interactive Data Visualizations

The dashboard includes six visualizations:

Defects by Description: Identifies the most frequently reported defects.
Monthly Defect Trends: Tracks defect counts across the twelve calendar months.
Defects by Category: Displays the distribution of defects across categories.
Pareto Analysis: Highlights the most significant defect types.
Inspector Performance: Compares defects and vehicles inspected by quality inspectors.
Top 10 Defect Locations: Identifies locations with the highest defect counts.
3. Advanced Filtering

Users can filter the dashboard using multiple criteria:

Date range
Defect description
Defect category
Job number
Vehicle chassis number

The Apply Filters button updates the dashboard according to the selected criteria.

4. Interactive Cross-Filtering

Users can click supported chart elements to filter the dashboard by specific defect descriptions, months, categories, and other available dimensions.

An active-filter indicator displays the current chart selection, and users can clear it to return to the broader dataset.

5. Automated Insights

The dashboard includes an Insights Summary section featuring:

Defect concentration analysis
Category distribution insights
Peak trend analysis

These insights help users identify patterns and focus their attention on potential quality issues.

6. LOT & Category Defects Matrix

A dedicated matrix displays defect counts by LOT and quality category, including:

Assy
Body
CKD
Local
Paint
Total

This view helps quality teams compare defect distributions across production lots and categories.

7. Modern UI & 3D Visualization

The dashboard features:

Dark-themed interface with glassmorphism effects
Animated 3D background powered by Three.js
Interactive ambient and analysis modes
Gradient-based chart styling
Responsive layout for different screen sizes
Visual severity indicators

The insights panel uses a color-coded system:

🔴 Red: Critical — requires immediate action.
🟡 Gold: Important — requires secondary action.
🔵 Cyan: Normal indicator.
🛠️ Technologies Used
Technology	Purpose
HTML5	Dashboard structure
CSS3	Styling, animations, and responsive design
JavaScript	Data processing, filtering, and dashboard logic
Tailwind CSS	Utility-based styling
Chart.js	Interactive charts and data visualization
Chart.js DataLabels	Displaying values and percentages on charts
SheetJS (XLSX)	Reading and processing Excel files
Three.js	Animated 3D background and visual effects
📂 Project Structure
Jetour-QA-Dashboard/
│
├── index.html       # Main interactive dashboard
└── README.md        # Project documentation

Note: Rename Jetour_QA_Dashboard_No_PDF(3).html to index.html before uploading if you want to use GitHub Pages with the default page URL.

🚀 How to Run the Dashboard
Option 1: Run Locally
Download or clone this repository.
Open the project folder.
Open index.html in a modern web browser.
Click Upload File.
Select your Excel quality inspection dataset.
Apply filters to explore the data and update the visualizations.

An internet connection is required to load the external JavaScript and CSS libraries used by the dashboard.

Option 2: Run with GitHub Pages

You can publish the dashboard online using GitHub Pages.

Upload index.html and README.md to your repository.
Open the repository on GitHub.
Navigate to Settings → Pages.
Under the build and deployment settings, select Deploy from a branch.
Select the main branch and the root folder.
Save the settings and wait for deployment.
Open the generated website URL to access the dashboard.

You can then add the live dashboard link to your CV and LinkedIn profile.

📑 Expected Dataset

The dashboard reads Excel files in .xlsx and .xls formats.

It combines records from the workbook's worksheets and recognizes several possible column names.

Data Field	Supported Column Names
Repair Date	Repair Date, Date, DATE, RepairDate
LOT	LOT
Chassis Number	Chassis Number, Chassis, CHASSIS
Defect Description	Defect Description, Defect Code, Defect
Defect Location	Location Description, Defect Location
Quality Inspector	Quality Inspector
Defect Category	Defect Category
Job Number	Job, JOB, Job Number, Job No

Important: Use column headers that match the supported names to ensure the dashboard interprets the data correctly. Fields such as LOT, chassis number, and defect category are particularly important for the corresponding KPIs and analyses.

📈 Business Value

This project demonstrates how interactive dashboards can support data-driven quality management.

Potential business benefits include:

Faster identification of recurring defects.
Improved visibility into quality performance.
Better understanding of defect concentration across categories and locations.
Easier comparison of production LOTs.
More efficient investigation of individual vehicle records.
Improved monitoring of quality trends.
More informed prioritization of corrective actions.
👨‍💻 Skills Demonstrated

This project showcases practical skills in:

Data Analytics
Data Visualization
Interactive Dashboard Development
JavaScript Data Processing
Excel Data Integration
KPI Development
Quality Assurance Analytics
Exploratory Data Analysis
Business Intelligence
Responsive Web Development
Data-Driven Decision Support
🔒 Data Privacy

This dashboard processes uploaded Excel data within the browser using client-side JavaScript.

Before publishing the dashboard or sharing the repository, ensure that any real company data, customer information, vehicle identifiers, or confidential inspection records have been removed from public files.

Do not upload confidential Jetour or company inspection datasets to a public GitHub repository.

📌 Future Improvements

Potential enhancements include:

Exporting filtered reports to PDF or Excel.
Adding year-month comparisons for more precise trend analysis.
Introducing configurable quality thresholds.
Adding further drill-down capabilities.
Improving data validation and error handling.
Integrating additional quality metrics.
📝 Disclaimer

This project is intended for quality analytics and dashboard development purposes. Business decisions should be based on validated data, agreed quality definitions, and the organization's official reporting procedures.
