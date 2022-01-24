# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1- Calculate the total number of votes cast.  
2- Get a complete list of candidates and counties that received votes.  
3- Calculate the total number of votes each candidate and county received.  
4- Calculate the percentage of votes each candidate and county won.  
5- Determine the winner of the election based on popular vote and the county with the largest number of votes.  

## Resources
data source: election_results.csv.  
software: Python 3.7.6
## Election Audit Results
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct. Which county had the largest number of votes? Provide a breakdown of the number of votes and the percentage of the total votes each candidate received. Which candidate won the election, what was their vote count, and what was their percentage of the total votes? The analysis of the election show that:

- There were 369,711 votes cast in the election
- County Results:
  - Jefferson received 10.5 % of the vote and 38,855 number of votes.
  - Denver received 82.8 % of the vote and 306,055 number of votes.
  - Arapahoe received 6.7 % of the vote and 24,801 number of votes.
- Denver had the largest number of votes.
- The candidate results were:
  - Charles Casper Stockham received 23.0 % of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8 % of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1 % of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette who received 73.8 % of the vote and 272,892 number of votes.
These can be confirmed by the Text File Output of the code:



## Election Audit Summary
This code can be used for any election with a few modifications which are the following:

- The first modification would be changing the name and possibly the location of the csv file. In the original code we have ``file_to_load = os.path.join("Resources", "election_results.csv")``. This section has to be updated based on the name of the file and the folder.
- The second modification is to check the csv file. Columns need to be checked to see if they match the code. For example, ``candidate_name = row [2]``, this is only true for this csv file where the name of candidates is in column 3. This needs to be changed accordingly for a different dataset.
