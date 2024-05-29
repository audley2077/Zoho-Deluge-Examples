# Deluge Examples
Hi! My name is Tannere Bond and this repository servers an example of my Deluge skills to current and future employers.

## Example 1 - Scheduled Action - Currency Exchange
This example is a demo of a a scheduled action that runs once a day (or night) at a set time. It will calculate the exchange rate from EUR to USD for all records in Zoho CRM matching a sepecific pipeline. Using COQL I am able to get the exact number of records I needed, and also sort if needed. I can then make a list of lists, in order to feed that into Bulk Update API command to update a hundred records at a time. This process is very quick, even when dealing with thousands of records.

## Example 2 - Custom Function (Workflow Trigger) - Currency Exchange
This is the same as the first one, but will be triggered via workflow to calculate the exchange rate if the currency field is changed.
