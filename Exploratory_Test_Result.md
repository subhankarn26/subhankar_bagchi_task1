# MoneyFy Exploratory Test Result
##### By : Subhankar Bagchi
##### Date : 22-Jan-2022

## Charter 01 : Addition of Income and Expense
### Explore Target: Adding Income and Expense
### With Resources: 
Test Data as Follows

| Type   | Date | Category | Amount | Note   |
| :----: | :---:| :----:   | :----: | :---- |
| Income | Jan 23, 2022 |Salary | 2000 | Adding Salary |
| Income | Jan 22, 2022 |Saving | 500  | Adding Savings Amount |
| Expense | Jan 15, 2022 |Eating Out | 120 | Bills in Resturent|
| Expense | Jan 08, 2022 |Food | 100 | Fodd from Grocery Store |
| Expense | Dec 23, 2021 |House | 450 | Home Loan Repayment |
| Expense | Jan 12, 2022 |Car | 35 | Car Maintanance |
| Expense | Jan 17, 2022 |Bill | 250 | Electricity Bill |
| Expense | Jan 31, 2022 |Transport | 2500 | Bus Fare |
| Expense | Jan 01, 2021 |Cloths | 2500 | Buying Cloths |

### To Discover:
- Adding Income with different category is working fine and Amount is getting updated as expected.
- Adding Expense with different category is working fine and Amount is getting updated as expected.
- Month, Day, Week , Year Option is working fine
- Switching between the months is working fine.
- Editing the amuont is working fine.
- Changing the category of existing record works fine.

### Observation/Possible Bugs:
- User is able to add an Income/Expense for a future date. There is no restriction for adding on future date.
- In Category selection screen, user is unable to add a custom Category. "Add" button is not working.



## Charter 02 : Verification of Expense chats %
### Explore Target: Expense chart percentage
### With Resources: 
Sample Test Data
### To Discover:
- Expense Breakup percentage is working fine.
- Adding/ Updating expense would update the percentage accordingly.

### Observation/Possible Bugs:
- Once an Date Interval is created, if there is a mistake in date selection, there is no option to update/delete it. Only available way for user is to create another one with new date range.



## Charter 03 : Selection of Custom Interval
### Explore Target: Select Custom Interval
### With Resources: 
Sample Test Data
### To Discover:
- Selection of Custome Interval is working as expected. Balance (Income/Expense) is getting updated according to the selection.

### Observation/Possible Bugs:
- Once an Interval is created, if there is a mistake in date selection, there is no option to update/delete it. Only available way for user is to create another one with new date range.


## Charter 04 : Transfer Feature
### Explore Target: Select Custom Interval
### With Resources: 
Manual Testing
### To Discover:
- Transfer between Cash & Card is working.
- Same account transfer is disabled as expected.

### Observation/Possible Bugs:
- Even if the user have Cash amount zero, user is able to transfer some amount from Cash to Card. Usually, expectation was, is cash amount is zero, then transfer from cash to card should not work.


## Charter 05 : Global Search
### Explore Target: Search feature
### With Resources: 
Manual Testing
### To Discover:
- Global search functionality is working.

### Observation/Possible Bugs:
- N/A


## Charter 06 : Currency change
### Explore Target: Currency change
### With Resources: 
Manual Testing
### To Discover:
- User is able to change the currency.

### Observation/Possible Bugs:
- Once the currency is changed, previously added amount in a different currency does not auto convert itself. For example, if user add, 100 USD and then user update the currency to Australian Dollar, the amount becomes 100 AUS Dollar.