# Pandas-Cheat-Sheet
Pandas is a powerful open source data analysis library for Python. It is used for a wide range of data manipulation tasks, including data munging, data cleaning, data wrangling, and data visualisation. This cheat sheet provides a quick reference to some of the most common Pandas functions and commands.
import pandas as pd

### Create DataFrame from a dictionary
df = pd.DataFrame({'col1': [1, 2, 3], 'col2': ['a', 'b', 'c']})

## Create DataFrame from a list of lists
df = pd.DataFrame([[1, 'a'], [2, 'b'], [3, 'c']], columns=['col1', 'col2'])

# Create DataFrame from a CSV file
df = pd.read_csv('filename.csv')
