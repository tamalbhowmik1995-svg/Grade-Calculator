🧰 Tools and Technologies Used

1. Python

The core programming language used to build the Grade Calculator.

Provides simplicity, readability, and a wide range of libraries for data analysis and visualization.



---

2. Pandas

Used for data handling and analysis.

Helps in loading, cleaning, and processing students' grade data efficiently.

Provides powerful tools like DataFrames for:

Calculating averages and totals.

Filtering and sorting student scores.

Managing large datasets easily.



Example Use:

import pandas as pd

data = pd.read_csv('grades.csv')
average_score = data['Marks'].mean()


---

3. Matplotlib

Used for data visualization.

Helps in creating charts and graphs to represent students’ performance visually.

Common plots used:

Bar charts for grade distribution.

Pie charts for pass/fail ratios.

Line charts for performance trends.



Example Use:

import matplotlib.pyplot as plt

plt.bar(data['Student'], data['Marks'])
plt.title('Student Grade Comparison')
plt.xlabel('Student')
plt.ylabel('Marks')
plt.show()


---

4. Jupyter Notebook / VS Code (Optional)

Used as the development environment for writing and testing the Python code.

Provides interactive cells for running and visualizing Pandas and Matplotlib outputs easily.



---

5. CSV Files

Used as data storage for student grades.

Easy to import/export using Pandas.