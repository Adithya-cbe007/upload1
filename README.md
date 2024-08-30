# upload1
Python
import yfinance as yf

# Download Tesla stock data
tesla_data = yf.download('TSLA', start='2023-01-01', end='2024-08-29')

# Reset the index to make it a regular DataFrame
tesla_data.reset_index(inplace=True)

# Save the data to a CSV file
tesla_data.to_csv('tesla_stock_data.csv', index=False)

# Display the first five rows
print(tesla_data.head())
Use code with caution.
Screenshot of the results and code:
 Opens in a new window www.mssqltips.com
Python code and output for Tesla stock data 

