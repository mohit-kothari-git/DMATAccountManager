Hi 

Project Details :- 
***************************************************

Implement a share trading account in Java that is basically a D-MAT (Dematerialized) account
containing (equity) shares and transaction details regarding the same shares.
Following are the requirements for the D-MAT account:-
1. When the program starts it should give the user two options:
a. Create a Demat account - Create a D-MAT account with needed details
(Mentioned Below).
b. Login - It should ask for the account number in order to login (The account
number should be an integer value).
2. The account should have the following user details:
a. User name
b. Account number
c. Money in the account (that can be used to buy shares or put into the account
when shares are sold)
d. Share name or ID (to identify the company name)
e. Number of shares (of each company) held
f.
Value of each share
3. The transactions done in the account should contain the following details:
a. Data & time the share was bought or sold
b. Number of shares that were transacted
c. Price at which it was bought or sold
4. Following are the additional details for each transactiona. The money in the account should be adjusted based on the transactions.
b. There will be a transaction charge of 0.5% (for both buying and selling) on the
transacted value. Also the minimum transaction charge is Rs. 100.
c. A STT (Securities Transfer Tax) of 0.1% of the overall transaction (not including
the transaction charges) will be deducted.
d. The transaction charges and taxation percentage should be easily
configurable.
5. The main menu when you start the program should be as follows:
0 – Quit
1 – Display Demat account details
2 – Deposit Money
3 – Withdraw Money
4 – Buy transaction
5 – Sell transaction
6 – View transaction report

*****************************************************************************************************************

Project Run Configuration 

Step 1 :- **********************DataBAse Setup***********************
                Use DB-Setup.sql file to create Schema and Tables in Mysql 

Step 2 :-  ************************Code Setup and Project View************************
               Open the folder in Eclipse/Intellij as maven project to view the code
               2.a :- Goto-> DB class and change the filepath to the filepath if the dbConfig.txt in the following fileURI(dmat_account-> src-> dbconfig.txt
               2.b :- Project is ready to be executed
Step 3:- ***********************JAR File and Code Run**********************************
	  By default the pom file will use JRE 17 or 1.8 to run the project incase of error change the Run Configuration as follows:-
               Kindly Use JRE 17 if your IDE is fixed to run 

Enjoy the project Incase of any errors in setup kindly contact 

mohkotha@amazon.com on chime/mail.

Developed with love Mohit Kothari