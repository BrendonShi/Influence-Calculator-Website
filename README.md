# Influence Calculator
A sleek, interactive web application to visualize numerical data and calculate the statistical "influence" of any subset. See how selecting different data points impacts the overall average in real-time!

![msedge_1hlTtSnHw7](https://github.com/user-attachments/assets/7b440c5f-ac05-4596-acde-49d28a954e25)

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

---

### Tech Stack
Backend: Python & Flask

Frontend: HTML5, CSS3, Vanilla JavaScript

Communication: Fetch API for asynchronous client-server requests

---

## How to run the code

Prerequisites
You will need to have the following installed on your system:

Python
On MacOS:
```bash
brew install python
```
On Windows
```bash
winget install -e --id Python.Python.3.12
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
