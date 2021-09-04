# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent total Congressional election. 

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.60.0

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview 

### Overview of Election Audit
The Colorado Board of Elections employee initially requested an election audit of a recent total Congressional election with information about the total votes cast and the candidates, i.e., the total number each candidate received, the percentage of the vote that each candidate received, and the winner of the election. The election commission then requested additional information to include in the election audit, such as information about the counties and their votes. The full list of tasks performed were as follows: 

1. Calculate the total number of votes cast. 
2. Calculate the total number of votes cast within each county.
3. Calculate the percentange of votes from each county. 
4. Determine which county had the largest voter turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular vote.

## Challenge Summary 

### Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The results for voter turnout for each county was:
  - Jefferson obtained 10.5% of the vote and 38,855 number of votes.
  - Denver obtained 82.8% of the vote and 306,055 number of votes.
  - Arapahoe obtained 6.7% of the vote and 24,801 number of votes.
- The county with the largest voter turnout was:
  - Denver, which obtained 82.8% of the vote and 306,055 number of votes. 
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.

### Election Audit Summary
The current analysis revealed how Python coding could be utilized to determine the results of a recent total Congressional election. As described above, the analysis conducted was limited to a particular congressional district, Colorado's 1st congressional district, consisting of a precinct of three counties in Colorado, i.e., Jefferson, Denver, and Arapahoe. However, the same exact code has powerful versatility and can be utilized to conduct any election audit analysis that the commission requests:
- The commission can apply the same script to election data files obtained for the other 6 congressional districts and yield the same type of data results for each congressional district. A full report can be written to include the above results across all 7 congressional districts.  
- Furthermore, the existing script can be modified to run analyses to obtain other election results that might be of interest to the election commission. For example, this script can be performed on data files that also contain information about voters' political party affiliation if we want to know about voter turnout according to political party affiliation. We can create a list of party affiliation: "party_options = []" to obtain all the different party affiliations and a dictionary for party votes: "party_votes = {}", and perform the same script that was used for county turnout to determine the voter turnout for each different party affiliation, including the total number and percentage of votes.  

Thus, the current analysis using Python coding not only provided the results that the commission requested but the script that was developed can be adapted to other election audits as outlined above as well as for local election results as well as senatorial races. 
