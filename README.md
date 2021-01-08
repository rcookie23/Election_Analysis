# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent local congressional election.

    1. Calculate the total nuber of votes cast in the precinct.
    2. Calculate the total number of votes cast in each county in the precinct.
    3. Calculate the percentage of total votes for each county in the precinct.
    2. Get a complete list of candidates who received votes.
    3. Calculate the total number of votes each candidate received. 
    4. Calculate the percentage of votes each candidate won.
    5. Determine the winner of the election based on popular vote.
    

## Resources
    - Data Source: election_results.csv
    - Software: Python 3.7, Visual Studio Code 1.52.1

## Summary
The analysis of the election revealed the following statistics: 

- There were 369,711 votes cast in the election.

The code used to calculate the total number of votes case is shown below:
![Total Votes](/Resources/total_votes_code.png)

- The breakdown of the number of votes per county is as follows:
    - Jefferson County: 38,855 (10.5%)
    - Denver County: 306,055 (82.8%)
    - Arapahoe County: 24,801 (6.7%)

- The county with the largest turnout was Denver County, with 306,055 votes.

The code used to calculate the number and percentage of voter turnout per county is shown below:
![Votes Per County](/Resources/county_votes_code.png)

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 total votes.
    - Diana DeGett received 73.8% of the vote and 272,892 total votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes.
- The winner of the election was:
    - Diana DeGett, who received 73.8% of the vote and 272,892 total votes.

The code used to calculate the candidates' votes and determine the winning candidate is shown below:
![Candidate Results](/Resources/candidate_results_code.png)

## Election-Audit Summary

Moving forward, the Colorado Board of Elections will be able to use this script for any election in the state. If voter data from other precincts is added to the CSV file, the script can be updated to calculate the number of votes that are cast in each precinct, and for which candidates. The script can also be modified to print the information from all precincts to the text file, and allow users to see voter data from the entire state in one document. 