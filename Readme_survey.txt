Survey Tool for Healthcare Product Launch – Final Project
Developer: Inemesit Mitchel
Date:05/01/2025 


#Project Overview#
This project consists of a complete data pipeline built using Flask, MongoDB, Python, and Jupyter Notebook to collect, store, analyze, and visualize participant income and expense data. The insights support a healthcare product launch strategy.

Project Features
- Web app built with Flask for survey data collection
- Data stored in MongoDB
- Expense inputs via checkboxes and textboxes for categories which includes:
  - Utilities
  - Entertainment
  - School Fees
  - Shopping
  - Healthcare
- Python class `User` for data handling
- Data exported to CSV and analyzed using Jupyter Notebook
- Charts saved for use in PowerPoint
- Deployed to AWS


Folder Structure


project-folder/
│
├── flask_app.py        - the Main Flask app
├── templates/	         - Web form template folder
│   └── form.html       - Web form template
├── process_data.py     - User class for processing
├── survey_data.csv     - Generated user data
├── visual_flask.ipynb  - Jupyter notebook with visualizations
├── README.txt           - Project instructions (this file)
└── requirements.txt    - Python dependencies


#Installation Instructions#

1. Set up a virtual environment on python and activate it
2. Install dependencies
- Flask, pymongo, pandas, and matplotlib
3. Run MongoDB- Ensure you have MongoDB running locally on 'mongodb://localhost:27017/'
4. Start the Flask app
You can access the app at (http://localhost:5000)

#Data Processing#
Run the process.py file
1. Each submission is processed and stored in 'MongoDB'
2. A Python class 'User' parses the Mongo data into a CSV (`Survey_data.csv`)
3. This file is loaded in 'visual_flask.ipynb' for visualization


#Visualization#

Open 'visual_flask.ipynb' in 'Jupyter Notebook' to view:
1. Top Ages by Income – bar chart
2. Spending by Gender Across Categories – Grouped bar chart

All charts are saved as '.png' files for PowerPoint use.


