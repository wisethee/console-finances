# :file_folder: Console Finances
Creating code for analyzing the financial records of a company.

[Demo URL](https://wisethee.github.io/console-finances/)

![Screenshot](https://github.com/wisethee/console-finances/blob/main/assets/cover.jpg?raw=true)


## My Solution
1. Store all months in a different array called "months"
2. Store ale profits and losses in an array called "profitOrLosses"
3. Check "months" array for duplicates
4. Calculate the total profit or loss
5. Create an array called "monthlyChanges" and store the difference between current value and previous value
6. Sum all "monthlyChanges" and return "averageChangeTotal"
7. Calculate mean of "averageChangeTotal"
8. Return min and max of monthlyChanges as greatest increase and decrease in profits


## Instructions
1. Create a new GitHub repo called `Console-Finances`. Then, clone it to your computer.
2. Copy the starter files in your local git repository.

You have been given a dataset composed of arrays with two fields, Date and Profit/Losses.
Your task is to write JavaScript code that analyzes the records to calculate each of the following:
* The total number of months included in the dataset.
* The net total amount of Profit/Losses over the entire period.
* The average of the **changes** in Profit/Losses over the entire period.
  * You will need to track what the total change in profits are from month to month and then find the average.
  * (`Total/Number of months`)
* The greatest increase in profits (date and amount) over the entire period.
* The greatest decrease in losses (date and amount) over the entire period.
When you open your code in the browser your resulting analysis should look similar to the following:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 25
  Total: $2561231
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

The final code should print the analysis to the console.

## License
This project is open source and available under the [MIT License](LICENSE.md).