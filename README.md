# Project Scenario: 
You have been hired as a data engineer by research organization. Your boss has asked you to create a code that can be used to compile the list of the top 10 largest banks in the world ranked by market capitalization in billion USD. Further, the data needs to be transformed and stored in GBP, EUR and INR as well, in accordance with the exchange rate information that has been made available to you as a CSV file. The processed information table is to be saved locally in a CSV format and as a database table.

The required data are available [here](https://web.archive.org/web/20230902185326/https://en.wikipedia.org/wiki/List_of_countries_by_GDP_%28nominal%29)

# Objectives
- Log the progress of the code with appropriate timestamps.
- Extract the tabular information from the given URL under the heading 'By market capitalization' and save it to a dataframe.
- Transform the dataframe by adding columns for Market Capitalization in GBP, EUR and INR, rounded to 2 decimal places, based on the exchange rate information shared as a CSV file.
- Load the transformed information to the required CSV file and as a database file.
- Run the required query on the database:
  + Display the contents of the entire table.
  + Display the average market capitalization of all the banks in Billion GBP.
  + Diplay only the names of the top 5 banks

