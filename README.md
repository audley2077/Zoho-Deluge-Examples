# Deluge Examples
Hello. My name is Tanner Bond and this repository serves as an example of my Zoho Deluge skills to current and future employers. Deluge is the primary scripting language used in the [Zoho ecosystem](https://www.zoho.com/deluge/). It shares similarities to [JavaScript](https://en.wikipedia.org/wiki/JavaScript). Feel free to copy or use any parts of my code to learn from. Cheers.

## Example 1 - Scheduled Automation - Currency Exchange
This example is a demo of a scheduled action that runs once a at a set time. It will calculate the exchange rate from EUR to USD for all records in Zoho CRM matching a sepecific pipeline. Using [COQL](https://www.zoho.com/crm/developer/docs/api/v8/COQL-Overview.html), I am able to get the exact number of records I need and then sort if required. From there I can then make a list of lists in order to feed that into [update records](https://www.zoho.com/deluge/help/crm/bulk-update-records.html) API to update a hundred records at a time. This process is very quick even when dealing with thousands of records.

## Example 2 - Custom Function - Currency Exchange
This is the same as the first example, but will be triggered via workflow to calculate the exchange rate if the currency field is changed.

## Example 3 - Custom Function - Generate Deal Name
This function will auto-generate a Deal name based on the Account and Contact name. It wil also add the total Deal amount. This can be used with any type of trigger.
