# Home_Sales
This analysis uses SparkSQL to determine key metrics about home sales data    
**Questions to be answered by Analysis:**  
- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places. 

**Other comparisons to perform are:**  
Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000.  
- Determine the runtime and compare it to uncached runtime.
Partition by the "date_built" field on the formatted parquet home sales data.
Create a temporary table for the parquet data.
Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000.  
-  Determine the runtime and compare it to uncached runtime.
# Files/Folders
- Home_sales.ipynb = file uploaded from google colab to github repository (C:\PythonStuff\Repo\Home_Sales\Starter_Code)
- Readme = Gives an overview of the project  
(C:\PythonStuff\Repo\Home_Sales)