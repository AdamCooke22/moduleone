# moduleone
Module 1 Challenge

Part 1
In the first part of this challenge we have a simple list of the cost of loans. We know it is a list due to the use of []. 
  We are trying to find the length of the list or in other words, how many loans we are dealing with, and to do that we use the len() function.
  We are also trying to find the total value of all of the loans in the list, to do that we use a sum() function to add together all of the values in the list
  We are also trying to find the average amount of each loan in the list. In order to do that we are going to use what we have previously done which is getting the sum of all of the loans in the list and getting the number of the quantity of loans in the list. Then apply the correct formula to do that.
  To get all of the values that we are wanting we use the print function print() to display what we are solving for when we go to run the code.
  
  
  
Part 2
In this part of the challenge we are working on using dictionaries and conditional statements.
    We are asked to define certain variables like future value and fair value and in order to do that we need to create certain variables for them and to do that we use the get() function to extrac that data out of the dictionary. 
    In order to find the fair value we just use the formula for present value and we use the print() function to display those values when we are running the code
    In order to see if the loans are worth buying we need to implement an if else statement by seeing if the loan meets a certian condition, that condition being if the fair/present value of the loan being greater than or eaqual to the price of the loan. If the cost of the loan was less that or equal to the present value of the loan we would deem it worth buying and print a message indicating such, and if not than a message would print indicating otherwise.
 \
 
Part 3
In this part we are to define a function to calculate the present value of a new loan with the date and parameters listed in a dictonary.
  We can set up the function to calculate the PV and call that function using the parameters from that specific dictionary my specifying the name of the dictionary before we list the variables.
  We define the function using all of the parameters needed for the calculation and the state what we want the function to do, and have it print the results, and return the present value of the new loan
  To actuallly use the function to calculate the present value of the new loan dictionary we call the function into play and have and specify that the variables are coming from the new loan dictionary and print the result and I just went ahead and rounded the result to two decimal places since dollars and cents only go to two decimals.
  
  
Part 4
In this part we have a list of loans and we are trying to create an additional list of certain loans that meet certain conditions. 
  We first create and empty list using [], then in order to go through the list and make changes we need to use a for loop.
  When using this for loop we are working under the condition that the loans that we need to add to the new list need to have a price that is less than or equal to 500. So if that condition is met then we add that loan to the new list using the append() function.
  To see what we were able to add to the new list we use the print function () along with the name of the new list. When doing so we were able to add two new entries to the list and both of them satisfy the criteria.
  
Part 5
In order to output the list that we were working on we need to create a new csv file. This is used to store the data in a spreadsheet format.
  The header defines the column names and the rows contain the values that pair with the columns. We also are using a delimiter to seperate the entries by using a comma between them by using ",". By using the with and open functions it allows us to establish a connection from our python file to the csv file that we created.
  Then we use a loop again so we can go through each row at a time and select and outpust each entry in the list to the spreadsheet.
  "w" indicates that we are writing to a file, and allows us to write the data from python to a new csv file.
  We start off by writing the first row, which is going to be the headers, then every subsequent row we use the for loop to input the data from the inexpensive loan list. 
  
  
  
  
After completion this file is added to a github repository and shared via the link associated with the repository.
  


