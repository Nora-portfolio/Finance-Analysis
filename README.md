# Finance-Analysis
# Finance Tracker

Welcome to the **Finance Tracker**! This project is a full-stack application designed to streamline financial data management and visualization. It showcases a modern web interface combined with powerful backend processing and data visualization tools.

## Features

### 1. Web Interface
- **HTML & CSS**: A responsive and intuitive design for seamless user experience.
- **JavaScript**: Provides client-side interactivity and form validation.

### 2. Backend
- **Flask (Python)**: Handles API requests and facilitates data storage.
- **Excel Integration**: User inputs are directly saved to an Excel file for persistent storage.

### 3. Data Processing
- **Python Libraries (e.g., Pandas)**: Cleans and transforms raw data for analysis, ensuring accuracy and efficiency.

### 4. Data Visualization
- **Power BI**: Generates interactive reports for in-depth financial analysis, including categorized summaries and trends.

### 5. Deployment
- Exports the Power BI reports and integrates them seamlessly into the web interface.

---

## Workflow

### Step 1: Input Data
Users input:
- Amount
- Date
- Category (Income, Food, Accommodation, etc.)

### Step 2: Save Raw Data
Data is saved as a raw Excel file using Python's openpyxl library.

### Step 3: Clean & Transform
Python scripts:
- Remove null and duplicate entries.
- Add calculated columns for additional insights.

### Step 4: Summarize Data
Summaries include:
- Total amounts per category.
- Aggregated tables for easy analysis.

### Step 5: Visualize with Power BI
The cleaned dataset is used to create visually engaging and interactive Power BI reports.

### Step 6: Publish Online
The final reports are embedded into the website, allowing users to view and interact with their financial data.

---

## File Structure

- **app.py**: Backend API built with Flask for handling requests and saving data.
- **index.html**: Main web page interface.
- **script.js**: Client-side functionality to handle user interactions.
- **style.css**: Styling for a modern and user-friendly appearance.
- **finance report.pbix**: Power BI report file for visualization.

---

## How to Run

### Prerequisites
- Python 3.x
- Flask
- openpyxl
- Pandas
- Power BI Desktop

### Steps
1. Clone this repository.
2. Install the required Python libraries: `pip install flask openpyxl pandas`.
3. Run the Flask app: `python app.py`.
4. Open `index.html` in your browser.
5. Explore the embedded Power BI reports.

---

## Acknowledgements
Special thanks to the open-source community and Microsoft Power BI for their incredible tools that made this project possible.

---

## Contact
For questions or feedback, feel free to reach out to [Nora Nguyen](mailto:example@example.com).
