# Python-data-analytics-quiz-4-5
Loading and Initial Inspection:

Loaded the "Significant Earthquakes 1965-2016" CSV file into a DataFrame.
Inspected the structure and columns of the DataFrame.
Data Cleaning:

Converted the Date column to datetime format and split it into Year, Month, and Day columns.
Dropped columns with more than 50% missing values.
Dropped rows with missing values in critical columns (Latitude, Longitude, Magnitude).
Categorizing Numeric Data:

Used the cut() function to categorize the Magnitude column into "Minor", "Moderate", and "Major" categories.
Data Reshaping:

Applied the melt() function to transform the DataFrame from a wide format to a long format.
Applied the pivot_table() function to create a summary table of Magnitude values, with Year as the index and Depth as columns, aggregated by the mean.
