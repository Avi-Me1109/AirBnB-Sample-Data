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
Sample data is for LOCAL Data (Penang, Malaysia) not National
- Correlation Beds vs Price: 0.3976761197658033
  
  ![Beds v Price](https://github.com/user-attachments/assets/052f9e16-33f7-4a75-9e43-6f9afc13bfe6)

- Correlation Num_Reviews vs Price: -0.027492798080179293

  ![Number of Reviews v Price](https://github.com/user-attachments/assets/7ec51f9a-df36-43a7-a7a9-31770041fe17)

  
- Correlation Rating vs Price: -0.08040870569178392

  ![Rating v Price](https://github.com/user-attachments/assets/08c9e691-9db2-4912-9506-b1f139347b72)


- Correlation Num_Amenities vs Price: 0.22758977065123134

  ![Number of Amenities v Price](https://github.com/user-attachments/assets/9a07ccd3-c5c9-4723-a5b7-0320f419705b)


- Correlation Beds vs Rating: 0.04062405298587741

  ![Beds v Rating](https://github.com/user-attachments/assets/eb1357e1-b4e2-4d52-9460-43c2c5693fb8)


- Correlation Num_Reviews vs Rating: 0.11606510504199788

  ![Number of Reviews v Rating](https://github.com/user-attachments/assets/7edba9f7-06bb-49c9-8bfe-8c67a00b434b)


- Correlation Price vs Rating: -0.08040870569178392

  ![Price v Rating](https://github.com/user-attachments/assets/f9a3ac44-b206-420c-aa77-c344898be79e)


- Correlation Amenities vs Rating: 0.13057339074450472

  ![Number of Amenities v Rating](https://github.com/user-attachments/assets/1e152e00-fade-4d90-b65b-7be428d25a94)



## Output with sample data
The output includes correlation coefficients printed in the console and various scatter plots shown in pop-up windows.


## Conclusion
This script provides a foundational approach to data cleaning and correlation analysis for Airbnb listings. It can be modified and expanded for more complex analyses or to include additional features based on user needs.
