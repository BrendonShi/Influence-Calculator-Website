# Influence Calculator
A sleek, interactive web application to visualize numerical data and calculate the statistical "influence" of any subset. See how selecting different data points impacts the overall average in real-time!

---

## Features

Dynamic Chart Generation: Instantly visualizes your number set as a beautiful, animated bar chart.

Interactive Data Selection: Simply click or drag across the chart to select and deselect data points.

Real-Time Calculations: Get immediate feedback with statistics for your selected data:

Total: Sum of selected values.

Median: The middle value of the selected set.

Mode: The most frequently occurring value.

Average: The mean of the selected values.

Influence Score: A unique metric calculated as the percentage change between the average of your selected subset and the average of the entire dataset.

Modern & Responsive UI: A clean and visually appealing interface built with pure CSS, featuring smooth hover effects and transitions.

---

### What is "Influence"?
The "Influence" score is designed to quantify the impact of a subset of data on the overall average. It answers the question: "How much does the average change when I only consider these specific data points?"

It's a powerful way to spot outliers or understand the weight of certain data clusters within your set. The formula used is:

$$ \text{Influence} = \frac{|\text{Subset Average} - \text{Total Average}|}{|\text{Total Average}|} \times 100% $$

This provides a clear percentage, showing how much your selection pulls the overall average up or down.

💻 Tech Stack
Backend: Python & Flask

Frontend: HTML5, CSS3, Vanilla JavaScript

Communication: Fetch API for asynchronous client-server requests (AJAX)

---

## Hot to run
Follow these instructions to get the project up and running on your local machine for development and testing purposes.

Prerequisites
You will need to have the following installed on your system:

Python 3
```
pip (Python package installer)
```
Installation & Setup
Clone the repository:
(Bash)
```
git clone https://github.com/your-username/influence-calculator.git
cd influence-calculator
```
### Create and activate a virtual environment (recommended):
For macOS/Linux
```
python3 -m venv venv
source venv/bin/activate
```
For Windows
```
python -m venv venv
.\venv\Scripts\activate
```
Install the required dependencies:
```
pip install Flask
```
Run the Flask application:
```
python app.py
```
View the application:
Open your web browser and navigate to http://127.0.0.1:5000.

### Project Structure
Here is a brief overview of the project's file structure:

```
.
├── app.py              # The Flask backend server logic
├── static/
│   ├── script.js       # Frontend logic for chart rendering, user interaction, and calculations
│   └── style.css       # All styles for the application, including animations and layout
└── templates/
    └── counter.html    # The main HTML file that structures the page
```
