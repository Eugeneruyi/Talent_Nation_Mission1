# Algorithm thinking : THE ATM

## Step 1:
Request User to insert ATM Card, when user insert ATM Card

## Step 2:
detect if card has been inserted, if Yes 

## Step 3:
check if card information can be read, else if card cannot be read print error message and inject card out of the machine

## Step 4:
Request for User card pin

## Step 5: 
If pin is inserted Validate if pin is correct , if yes, else if pin is incorrect print error message and ask user to re-enter pin for the second time and limit number of incorrect pin to 4 try after which block card on the fourth try

## Step 6:
Ask User to select withdrawal ,if Yes

## Step 7:
Ask User to Enter Amount, if yes

# Step 8:
Check User available balance, if available balance is greater than withdrawal amount else if  withdrawal amount is greater than available balance  print insufficient fund 

## step 9:
if yes , check amount of cash available if cash available is greater than withdrawal amount else if available cash in machine is less than  withdrawal amount print unable to dispense cash

## step 10:
if yes, dispense cash while if  transaction cannot be completed, print transaction error message and if user is debited activate cash reversal process

## step 11:
Return card to User.