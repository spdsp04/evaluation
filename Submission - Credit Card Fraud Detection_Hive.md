# Submission - Credit Card Fraud Detection

1. UCL calculation and other relevant details for the look-up table
1.1 Writes a script to calculate the moving average and standard deviation of the last 10 transactions for each card_id for the data present in Hadoop and NoSQL database.

proper scripts are provided . . . . . . . . . . .  . . . . . 


2. Execution of the scripts

2.1 Executes script written.The scripts must, after loading data&creating look-up table, take data from NoSQL database & AWS RDS & perform relevant analyses as per rules&must feed data in look-up table

 proper screenshots are provided . . . . . . . . . . . . 


3. Streaming data processing framework creation

3.1 Creates a streaming framework which ingests real-time POS transaction data from Kafka. The data is then validated based on the three rules’ parameters (stored in the NoSQL database).

correct code is provided . . . . . . . . . . . . . . .

4. Adding real-time transactions data in the card_transactions table

4.1 Updates the transactions data along with the status (Fraud/Genuine) in the card_transactions table.

correct code is provided . . . . . . .. . .  .. .  . . . 

5. Updating ‘postcode’ and ‘transaction_dt’ of the current transaction in the look-up table

5.1 Stores the ‘postcode’ and ‘transaction_dt’ of the current transaction in the look-up table in the NoSQL database.

correct code is provided . . . . . . . . . . . . . .

6. Correct classification as Genuine/Fraud

6.1 All incoming transactions should be correctly classified.

card transactions table in HBase has >59000 records with some having status as Genuine and some as Fraudulent.

7. Correctness of code

7.1 Code written, should be syntactically correct.

code written has correct syntax . . . . . . . . . .

8. Correctness of logic

8.1 Explanation of the solution to the problem in detail should be provided properly in a document.

proper Logic.pdf is provided . . . . . . . . . . .

9. Documentation

9.1 Proper documentation should be provided in the form of comments in the code.

the code written has proper documentation. . . . . ..  

