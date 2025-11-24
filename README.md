# currency converter

**Simple INR Currency Converter**
This is a basic Python script that converts a user-provided amount in Indian Rupees (INR) to six major foreign currencies using a set of fixed exchange rates.

This script is ideal for learning fundamental Python functions, dictionaries, loops, and user input handling.

**Features**
User Input: Prompts the user to enter the amount in INR to convert.

Multiple Conversions: Simultaneously calculates the equivalent amount in 6 different currencies.

Supported Currencies:

USD (US Dollar)

EUR (Euro)

GBP (British Pound)

JPY (Japanese Yen)

CAD (Canadian Dollar)

AUD (Australian Dollar)

Error Handling: Checks for valid numerical input.

**How to Run the Script**
Save the Code: Save the code block below into a file named converter.py.

Open Terminal: Navigate to the directory where you saved the file.

Execute: Run the script using the Python interpreter:

Bash

python converter.py
Enter Amount: The script will prompt you to enter the amount in INR, and then it will display the converted values.



**Note on Exchange Rates**
The exchange rates defined in the EXCHANGE_RATES dictionary are fixed and hardcoded.

For a real-time, production-ready application, you should use an external Currency Exchange Rate API to fetch up-to-date rates instead of relying on fixed values.

**Contribution**
Feel free to fork this repository and enhance it! You can improve it by:

Adding more currencies to the EXCHANGE_RATES dictionary.

Implementing an API call to fetch live exchange rates.

Allowing the user to select the base currency (not just INR).
