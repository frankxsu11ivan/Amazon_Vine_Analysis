OverView Mod 16
the purpose of this analysis is to become familuar with big data and using Spark. 
eventaully psuhing results form Spark to pgAdmin. 

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

Summary: In my summary, there is alwasy bias for reviews. Specificly thre is bias in the Vine program. 
The results of bias analysis to has the product id tied to zero (0) popular votes, verified purchase and with a high review headline.
short answer - the high review headlines are profitting by sales of the prodcut ID with out data that it is good == no good votes.
https://github.com/frankxsu11ivan/Amazon_Vine_Analysis/blob/main/GitWorkingFolder/bias%20data.png

Results:
How many Vine reviews and non-Vine reviews were there?
How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

