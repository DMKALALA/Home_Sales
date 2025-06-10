🏡 Home Sales – Module 22 Challenge
In this challenge, you’ll apply your SparkSQL knowledge to analyze key metrics in a home sales dataset. You’ll work with Spark to create temporary views, perform data partitioning, utilize caching, and verify uncaching within your PySpark environment.

🔧 Setup Instructions
Create a New Repository
Name it Home_Sales. This should be a separate repository and not added to any existing one.

Clone the Repository
Clone your new repository to your local machine.

Push Your Changes
After completing the challenge, push your updated files to GitHub.

📘 Instructions
Rename the notebook file Home_Sales_starter_code.ipynb to Home_Sales.ipynb.

Import the necessary PySpark SQL libraries.

Load the home_sales_revised.csv file from the provided AWS S3 bucket into a PySpark DataFrame.

Create a temporary view named home_sales.

📊 Analytical Tasks (Use SparkSQL)
Average Price of 4-Bedroom Homes by Year

Compute the yearly average price of homes with four bedrooms.

Round the results to two decimal places.

Average Price of Homes (3 Bed / 3 Bath) by Year Built

Find the average price for each year homes were built with 3 bedrooms and 3 bathrooms.

Round to two decimal places.

Average Price for Specific Criteria by Year Built

Calculate the average price for homes with:

3 bedrooms

3 bathrooms

2 floors

2,000+ square feet

Group by the year built and round the results to two decimal places.

Average Price by View Rating (Homes ≥ $350,000)

Determine the average home price for each view rating where the average price is ≥ $350,000.

Record and round the runtime for this query.

⚙️ Spark Optimizations and Operations
Cache the home_sales Temporary Table

Verify the Table is Cached

Run the "Average Price by View Rating" Query Again Using the Cached Table

Measure and compare the runtime to the uncached version.

Partition Data by date_built

Save the formatted home sales data as Parquet files, partitioned by the date_built column.

Create a Temporary Table from the Parquet Data

Re-run the "Average Price by View Rating" Query

Use the partitioned Parquet data, note the runtime, and compare it with previous runs.

Uncache the home_sales Table

Confirm that the Table Has Been Uncached Using PySpark

📤 Final Submission
Download the completed Home_Sales.ipynb notebook.

Upload it to your Home_Sales GitHub repository.

📚 Support & Resources
You have access to your instructional team, office hours, learning assistants, and tutors. Make full use of these resources for guidance and collaboration.

