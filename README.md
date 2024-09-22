# Local Airbnb Data Cleaning Python Script

## Description
This Python script is designed to clean and analyze local Airbnb data from Penang, Malaysia. The script performs data cleaning on various fields and computes correlation coefficients between different attributes, such as the number of beds, price, rating, and number of reviews. It also generates scatter plots to visually represent these correlations.

## Author
- **Name:** Avi Raj Balam
- **ID:** ADTP License Data (Python)

## Requirements
To run this script, ensure you have the following libraries installed:
- pandas
- seaborn
- matplotlib
- numpy
- re

## Usage
1. Input Data: Place the sample data in a CSV file name DATA.csv within the Project directory/
2. Run the Script: Execute the script in your Python environment. The script will:
- Read the CSV file and extract necessary columns.
- Clean the data by removing rows with missing or incorrect values.
- Analyze the data by calculating correlation coefficients.
- Generate scatter plots for visual analysis.

## Data Cleaning Process
The script performs the following cleaning steps:
- Removes rows with missing or invalid values in the key columns (Sleeping_Arrangements, Location, Rating, Price, and Number_of_Reviews).
- Filters properties located in Penang by checking the Location field.
- Extracts the total number of beds from the Sleeping_Arrangements column.
- Converts the Price from a string to an integer format.
- Counts the number of amenities for each property.

## Correlation Analysis
The script calculates the following correlations and generates corresponding scatter plots:

- Beds vs Price
- Number of Reviews vs Price
- Rating vs Price
- Number of Amenities vs Price
- Beds vs Rating
- Number of Reviews vs Rating
- Price vs Rating
- Number of Amenities vs Rating

Each correlation and its scatter plot are displayed sequentially.
- Correlation Beds vs Price: 0.3976761197658033
  ![Beds v Price](https://github.com/user-attachments/assets/052f9e16-33f7-4a75-9e43-6f9afc13bfe6)


## Output with sample data
The output includes correlation coefficients printed in the console and various scatter plots shown in pop-up windows.


## Conclusion
This script provides a foundational approach to data cleaning and correlation analysis for Airbnb listings. It can be modified and expanded for more complex analyses or to include additional features based on user needs.
