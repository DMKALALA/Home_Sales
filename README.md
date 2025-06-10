# 🏡 Home Sales – Module 22 Challenge

This project uses **SparkSQL** and **PySpark** to analyze a home sales dataset, calculate key metrics, and apply performance optimization techniques such as caching and partitioning.

---

## 🔧 Setup Instructions

1. **Create a New Repository**  
   - Name the repo `Home_Sales`. Do **not** use an existing repository.

2. **Clone the Repository**  
   - Clone the new repository to your local machine.

3. **Push Changes to GitHub**  
   - After completing your work, push all changes to your GitHub repo.

---

## 📘 Assignment Steps

- Rename `Home_Sales_starter_code.ipynb` to `Home_Sales.ipynb`
- Import required PySpark SQL functions
- Load `home_sales_revised.csv` from the AWS S3 bucket into a DataFrame
- Create a temporary view called `home_sales`

---

## 📊 SparkSQL Analysis Tasks

1. **Average Price for 4-Bedroom Homes by Year**
   - Use SparkSQL to calculate the average price of four-bedroom homes sold each year.
   - Round the results to 2 decimal places.

2. **Average Price of 3 Bed / 3 Bath Homes by Year Built**
   - Filter homes with 3 bedrooms and 3 bathrooms.
   - Group by year built and calculate average price (rounded to 2 decimal places).

3. **Average Price for Homes with Specific Features**
   - Filter for homes with:
     - 3 bedrooms
     - 3 bathrooms
     - 2 floors
     - At least 2,000 sqft
   - Group by year built and compute average price.

4. **Average Price by View Rating (≥ $350,000)**
   - Compute the average price of homes per view rating where the price is ≥ $350,000.
   - Record and compare query run time.

---

## ⚙️ Performance Operations

- **Cache** the `home_sales` temporary table
- **Verify** if the table is cached
- **Rerun** the query from step 4 and compare cached vs. uncached runtime
- **Partition** the data by `date_built` and save as Parquet files
- **Create** a new temp table from the Parquet data
- **Re-run** the average price by view query using partitioned data and compare runtime
- **Uncache** the `home_sales` temp table
- **Verify** it has been uncached using PySpark

---

## 📤 Final Steps

- Download the completed `Home_Sales.ipynb`
- Upload it to your GitHub `Home_Sales` repository

---

## 📚 Resources

- Use class time, office hours, and available tutors for help
- Collaborate with your partner as needed to complete the challenge
