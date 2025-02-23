# Pandas Built-in Functions

## DataFrame Creation Functions
- **`pd.DataFrame()`** – Creates a DataFrame, which is like a table or spreadsheet of data.
- **`pd.Series()`** – Creates a Series, which is a single column of data (like a list).
- **`pd.read_csv()`** – Reads data from a CSV file and turns it into a DataFrame.
- **`pd.read_excel()`** – Reads data from an Excel file and turns it into a DataFrame.
- **`pd.read_json()`** – Reads data from a JSON file and turns it into a DataFrame.

## Data Handling Functions
- **`df.head()`** – Shows the first few rows of your DataFrame (great for a quick preview).
- **`df.tail()`** – Shows the last few rows of your DataFrame.
- **`df.info()`** – Displays some basic info about the DataFrame, like column names and data types.
- **`df.describe()`** – Gives you summary statistics (mean, min, max, etc.) for each column.
- **`df.shape`** – Tells you the size of the DataFrame (how many rows and columns).
- **`df.columns`** – Lists all the column names.
- **`df.dtypes`** – Shows the data type of each column (e.g., integer, string).

## Data Cleaning Functions
- **`df.dropna()`** – Removes any rows with missing (NaN) values.
- **`df.fillna()`** – Replaces missing values with something else (e.g., zero or the column average).
- **`df.replace()`** – Replaces a specific value in the DataFrame with another value.
- **`df.drop_duplicates()`** – Removes any duplicate rows in the DataFrame.

## Data Transformation Functions
- **`df.sort_values()`** – Sorts the DataFrame by one or more columns (e.g., sorting by age or price).
- **`df.groupby()`** – Groups the data by one or more columns (useful for aggregation like calculating averages).
- **`df.pivot_table()`** – Creates a pivot table (a summary table that aggregates data).
- **`df.melt()`** – Converts a wide-format DataFrame to a long-format DataFrame.
- **`df.apply()`** – Applies a function to each element in the DataFrame (useful for custom operations).

## Statistical Functions
- **`df.mean()`** – Calculates the mean (average) of each column.
- **`df.median()`** – Finds the median (middle value) of each column.
- **`df.std()`** – Calculates the standard deviation of each column (how spread out the values are).
- **`df.corr()`** – Computes the correlation (relationship) between columns.
- **`df.count()`** – Counts the number of non-null values in each column.
