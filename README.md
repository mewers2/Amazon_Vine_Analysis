# Amazon_Vine_Analysis

## Project Overview
The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program and to evaluate if a positivity bias exists with the reviews written by members of the Vine program. To accomplish this analysis, Amazon Web Services is utilized to set up a database, PySpark is used to read and parse the data.  PostgreSQL is utilized to organize the data into a relational database.  PySpark is used to execute the ETL process on the data and then load the data into the PostgreSQL relational database.


## Results

The Vine Review Analysis yielded the following results:

#### Vine Program Members (Paid Reviews) Results

![vine 5star summary]()

- There are 170 total reviews written by Vine program members
- There are 37,840 total reviews written by non-members of the Vine program
- There are 65 5-star reviews written by Vine program members

#### Vine Program Non-Members (Unpaid Reviews) Results

![nonvine 5star summary]()

- There are 20,612 5-star reviews written by non-members of the Vine program
- The percentage of 5-star reviews written by Vine program members is 38%
- The percentage of 5-star reviews written by non-members of the Vine program is 54%


## Summary
Based on the results of the analysis, no evidence of a positivity bias exists with the reviews written by members of the Vine program.  Since the percentage of 5-star reviews within the vine members is 38% while the percentage of 5-star reviews written by individuals who are not members of the vine program is 54%.  Non-members are more likely to write a 5-star review than vine program members.

Another analysis I would recommend evaluating is the frequency of 1-star reviews written by vine program members compared to non-members.  Since this project has evaluated the 5-star (positive) reviews, an analysis of the negative (1-star) reviews would be interesting to evaluate and then juxtapose against the results of the 5-star review analysis.