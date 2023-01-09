# Console-Finances

##### This code is analyzing a set of financial data. It is calculating and outputting various statistics about the data, such as the total number of months included in the dataset, the net total amount of profit or loss over the entire period, the average change in profit or loss over the entire period, the greatest increase in profit over the entire period, and the greatest decrease in loss over the entire period.

#### the pseudo coode ansd the steps are:- Initialize totalMonths to 0
###### Initialize netTotal to 0
###### Initialize totalChange to 0
###### Initialize averageChange to 0
##### Initialize greatestIncrease to ['', 0]
##### Initialize greatestDecrease to ['', 0]

#### For each item in finances:
  Set month to the month of the item
  Set amount to the amount of the item
  Increment totalMonths by 1
  Add amount to netTotal
  If this is not the first month:
    Set change to the difference between the amount of the current month and the amount of the previous month
    Add change to totalChange
    If change is greater than the amount of greatestIncrease:
      Set the month of greatestIncrease to the current month
      Set the amount of greatestIncrease to change
    If change is less than the amount of greatestDecrease:
      Set the month of greatestDecrease to the current month
      Set the amount of greatestDecrease to change

Set averageChange to totalChange divided by (totalMonths - 1)

console.log "Total months: " and totalMonths
console.log "Net total: " and netTotal
console.log "Average change: " and averageChange
console.log "Greatest increase: " and the month of greatestIncrease, " (", and the amount of greatestIncrease, ")"
console.log "Greatest decrease: " and the month of greatestDecrease, " (", and the amount of greatestDecrease, ")"


#### screeshot of the code solution 

