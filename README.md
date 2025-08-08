Home-Overconsumption-Detector
Home Overconsumption Detector This project detects energy overconsumption in household appliances by analyzing their power usage data. It provides visualizations, calculates estimated electricity costs, and offers energy-saving tips using Streamlit.

Features
- Analyze Energy Usage from CSV data.
- Detect Overconsumption based on appliance type.
- Calculate Estimated Cost using your electricity rate.
- Visual Charts to compare usage by device type.
- Energy-saving Tips for each appliance.

Requirements
Make sure you have Python 3.8+ installed and the following dependencies:
pip install pandas matplotlib streamlit

Project Structure:

Home-Overconsumption-Detector/
│
├── energy_tracker.py   # Main Python script
├── energy_data.csv     # Example input CSV
├── README.md           # Documentation

How to Run the Project
Place your CSV file (e.g., energy_data.csv) in the project folder.

Run the project using Streamlit:

1) bash
2) Copy
3) Edit
4) streamlit run energy_tracker.py
5) Upload your CSV file in the web interface.

View charts, cost estimation, and energy-saving tips.

How It Works:

- Data Load → Reads the CSV into a DataFrame.
- Filter → Only devices with status = on are analyzed.
- Calculate → Adds power rating & cost calculation.
- Visualize → Displays a bar chart for consumption by device type.
- Tips → Suggests energy-saving actions.
