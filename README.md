# Data_Analysis_Pandas
In this case we are analysis data which based on world population

The provided code performs various operations on a DataFrame (`df`) containing world population data. Below is a summary of each section of the code:

1. **Reading File:**
   - Reads a CSV file containing world population data into a DataFrame (`df`).

2. **Setting Display Format:**
   - Sets the display format for float values in the DataFrame to have two decimal places.

3. **DataFrame Information:**
   - Uses `info()` to display information about the DataFrame, including data types and non-null counts.

4. **Descriptive Statistics:**
   - Uses `describe()` to calculate descriptive statistics for numeric columns, such as mean, count, standard deviation, minimum, 25th percentile, median (50th percentile), 75th percentile, and maximum.

5. **Handling Null Values:**
   - Checks for null values in each column and calculates the sum of null values.

6. **Number of Unique Values:**
   - Counts the number of unique values in each column using `nunique()`.

7. **Top 10 Populous Countries in 2022:**
   - Sorts the DataFrame by the "2022 Population" column in descending order and displays the top 10 countries.

8. **Correlation Matrix and Heatmap:**
   - Computes the pairwise correlation of numeric columns and visualizes it using a heatmap with Seaborn.

9. **Grouping by Continent:**
   - Groups the data by the "Continent" column and calculates the mean of population values for each continent, sorting by the 2022 population in descending order.

10. **Filtering by Continent (Oceania):**
   - Filters rows where the "Continent" column contains the substring 'Oceania'.

11. **Plotting Continent-wise Population Trends:**
   - Groups the data by continent and plots the mean population values for different years.

12. **Transpose Matrix Plot:**
   - Transposes the DataFrame (`df3`) and plots the resulting matrix.

13. **Displaying Columns:**
    - Lists and displays the columns present in the DataFrame.

14. **Boxplot:**
    - Generates a boxplot for the DataFrame (`df`) with a specified figsize of (20, 10).

The code provides insights into the world population data, including statistical summaries, correlation analysis, and visualizations of population trends across continents.
