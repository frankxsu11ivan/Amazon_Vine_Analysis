OverView Mod 16
the purpose of this analysis is to become familuar with big data and using Spark. 
eventaully psuhing results from Spark to pgAdmin via an AWS RDS instance

This pseudo project analyizes the Amazo This data is music reviewsn reviews written by members of the paid Amazon Vine program for bias toward favorable reviews from Vine members.

D1 Deliverables:
***An Amazon Review dataset is extracted as a DataFrame
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Mod16%20DF%20amazon%20review%20data%20set%20as%20DF.png

***The extracted dataset is transformed into four DataFrames with the correct columns 
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Mod16%20DF%20Customer.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Mod16%20DF%20Product.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Mod16%20DF%20Review.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Mod16%20DF%20Vine.png

***All four DataFrames are loaded into their respective tables in pgAdmin
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Push%20Customer%20table%20to%20pgAdmin%20Tables.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Push%20review%20id%20table%20to%20pgAdmin%20Tables.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/Push%20vine%20table%20to%20pgAdmin%20Tables.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/pgAdminProductsTable.png

D2 Deliverables
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/D2%20vine%20table.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/D2%20vine%20table%2025.png
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/D2%20vine%20table%20helpful%2050.png



Summary: In my summary, there is alwasy bias for reviews. Specificly thre is bias in the Vine program. 
The results of bias analysis to has the product id tied to zero (0) popular votes, verified purchase and with a high review headline.
short answer - the high review headlines are profitting by sales of the prodcut ID with out data that it is good == no good votes.
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/bias%20data.png

Results:
Bulleted Results (list) that addresses the three questions for unpaid and paid program reviews:
*How many Vine reviews 
*non-Vine reviews were there?
*How many Vine reviews were 5 stars? 
*How many non-Vine reviews were 5 stars?
*What percentage of Vine reviews were 5 stars? 
*What percentage of non-Vine reviews were 5 stars?

