# Age-Calculator
1. Modules to Install:
   - You don’t need to install any additional modules for this code as it only uses built-in Python modules. Specifically, it uses `datetime` from the standard library.

2. Purpose of the Code:
   - This code is designed to calculate a person's age based on their birthdate and then display it. It breaks down the age into years, months, and days.

3. How It Works:
   - Input: The user is prompted to enter their birthdate in a specific format (day, month, and year).
   - Processing the Input: The code converts this input into a date format that can be processed. It then calculates the difference between the current date and the provided birthdate.
   - Calculating Age:
     - The code first calculates the difference in years, months, and days between the current date and the birthdate.
     - It adjusts these differences if the current date is before the birthdate in the current year or month.
   - Handling Errors:
     - If the user inputs a date in an incorrect format or if the provided birthdate is invalid (like being in the future), the code will handle these errors and prompt the user to enter the date correctly.
   - Displaying the Result: After calculating the age, the code formats the result into a readable string showing years, months, and days.

The code takes a birthdate from the user, calculates the age by comparing it with the current date, and then displays the age in a human-readable format. If there are any issues with the input, it provides an appropriate error message.
