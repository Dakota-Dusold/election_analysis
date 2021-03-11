# Election_Analysis

## Challenge Overview
An employee form the Colorado Board of Elections has requested that we do an election audit for their recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election Audit Results
The results of the anlysis of this election provide the following information:
- There were **369,711** votes cast in the election.
- The counties were:
  - Arapahoe
  - Denver
  - Jefferson
-The County Results were:
  - Arapahoe had 6.7% of the vote, with 24,801 votes cast.
  - Denver had 82.8% of the vote, with 306,088 votes cast.
  - Jefferson had 10.5% of the vote, with 38,855 votes cast.
 - The county with the largest turnout was **Denver**.
- The candidates were:
  - Diana Degette
  - Raymon Anthony Doane
  - Charles Casper Stockham
 -The Candidate results were:
  - Diana Degette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
 - The winner of the election was:
    - **Diana Degette**, who received 73.8% of the vote and 272,892 votes.
## Election Audit Summary
1. This script could be used in city or state level elections with minor modifications. The f-strings and print statements would have to be updated as well as the variable names. 
2. Another use for this script could be to analyze registered voters in the area to project election results. The data would have to be manipulated to assume people would vote for their party, but the script would not change much. The f-strings and print statements would have to be updated as well as the variable names. THe majority of the formulas in this script are built to update the lists, tuples, dictionaries and counts bases on the data. 
  
