# NYC_SAT_RESULTS
This repository contains Python code for analyzing SAT scores data from a CSV file. The dataset includes information about various schools, the number of SAT test takers, and the average scores in critical reading, math, and writing. 
The code identifies schools that have not reported their SAT exam results, considering only numeric values.
Top and Bottom Performing Schools:

Identifies the top and bottom 5 schools based on average scores in math, writing, and reading.
Average Scores Visualization:

Visualizes the average scores of math, writing, and reading for each school with a bar graph.
Allows filtering scores above a specified threshold (e.g., 600).
Top 10 Schools by Overall Average:

Calculates the overall average score for each school and displays the top 10 schools with the highest averages.
Instructions
Dataset:

Ensure that the SAT scores dataset (sat_results.csv) is available.
The dataset should have columns like "DBN," "SCHOOL NAME," "Num of SAT Test Takers," "SAT Critical Reading Avg. Score," "SAT Math Avg. Score," and "SAT Writing Avg. Score."
Environment Setup:

Execute the provided Python code in a Jupyter notebook or any Python environment with the required dependencies installed.
Adjustments:

Modify file paths, column names, or any other parameters as needed for your specific dataset.
Graph Customization:

Customize graph parameters, such as figure size, bar thickness, and label rotation, to suit your preferences.
Contribution:

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit pull requests.
Dependencies
Python 3.x
Pandas
SQLite3
Matplotlib
