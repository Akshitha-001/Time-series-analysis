Time Series Analysis on Titanic Dataset
📌 Overview

This project demonstrates time series analysis techniques applied to the Titanic dataset. Using Python, we analyze survival trends by grouping passengers and applying rolling averages to observe patterns in the data.

📂 Project Structure

timeseries.ipynb → Jupyter Notebook containing the complete analysis

tested.csv → Dataset used for analysis (Titanic dataset)

🛠️ Tools & Libraries

Python 3

NumPy – numerical operations

Pandas – data manipulation

Matplotlib – visualization

📊 Analysis Workflow

Load the Titanic dataset (tested.csv).

Group passengers in batches (50 per group) to calculate survival rate.

Apply a 10-passenger rolling mean to smooth survival trends.

Visualize results to understand how survival rates vary across passenger groups.

🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/timeseries-analysis.git


Navigate to the project folder:

cd timeseries-analysis


Install dependencies:

pip install numpy pandas matplotlib


Open the notebook:

jupyter notebook timeseries.ipynb

📌 Results

Computed survival rates per group of passengers.

Applied rolling mean to smooth fluctuations.

Plotted visual trends of survival rates.
