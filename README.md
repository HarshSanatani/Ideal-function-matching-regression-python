📈 Function Matching using Supervised Learning

This project focuses on identifying the most appropriate functions that fit a given training dataset using basic supervised learning principles. It simulates the process of pattern recognition and curve fitting using predefined candidate functions and a labelled dataset. The goal is to assess which candidate functions most closely approximate the underlying function that generated the data.

🧠 Problem Statement

Given a set of input–output pairs (training data), determine which among several predefined mathematical functions best represents the relationship between inputs and outputs. This has applications in model selection, pattern recognition, and regression analysis.


✅ Objectives

Load and visualise training datasets

Match data against a set of ideal candidate functions

Calculate deviation/error between actual and predicted outputs

Identify the best-fitting function using threshold criteria

Plot and compare function performance

🛠 Tools & Technologies

Python 3.x

NumPy – numerical operations

Pandas – data handling

Matplotlib – visualisation

Jupyter Notebook – interactive analysis

📊 Methodology

Data Ingestion: Load training dataset and multiple candidate functions.

Function Matching: Compute the sum of squared errors (SSE) between each function and the dataset.

Threshold-Based Selection: Identify candidate functions where error remains within defined limits.

Visualisation: Plot training data alongside selected functions for comparison.

📁 Project Structure

bash

Copy

Edit

├── data/                      # Contains training and candidate function datasets

├── notebooks/                 # Jupyter notebooks for analysis

├── src/                       # Python scripts (optional modular functions)

├── output/                    # Graphs and result summaries

└── README.md


📌 Key Learning Outcomes

Understanding basic supervised learning without using high-level ML libraries

Manual model selection through error metrics

Improved grasp on function approximation, data analysis, and performance evaluation


🚀 Future Improvements

Automate threshold tuning via cross-validation

Implement additional regression techniques (e.g., polynomial regression)

Integrate Scikit-learn for benchmarking


👤 Author

Harshraj Chavda

Aspiring Data Analyst | MSc. Data Science

GitHub: @HarshSanatani
