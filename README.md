# Deluge Examples
Hello! My name is Tanner Bond and this repository serves as an example of my Deluge skills to current and future employers.

## Example 1 - Scheduled Action - Currency Exchange
This example is a demo of a scheduled action that runs once a day (or night) at a set time. It will calculate the exchange rate from EUR to USD for all records in Zoho CRM matching a sepecific pipeline. Using COQL, I am able to get the exact number of records I needed and sort if required. From there, I can then make a list of lists in order to feed that into Bulk Update API command to update a hundred records at a time. This process is very quick even when dealing with thousands of records at a time.

## Example 2 - Custom Function - Currency Exchange
This is the same as the first example, but will be triggered via workflow to calculate the exchange rate if the currency field is changed.

## Example 3 - Custom Function - Generate Deal Name
This function will auto-generate a Deal name based on the Account and Contact name. It wil also add the total Deal amount. This can be used with any type of trigger.
