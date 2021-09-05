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
The Colorado Board of Elections employee initially requested an election audit of a recent total Congressional election with information about the total votes cast and the candidates, i.e., the total number each candidate received, the percentage of the vote that each candidate received, and the winner of the election. The election commission then requested additional information to include in the election audit, such as information about the counties and their votes. The full list of tasks performed along with screens shots of  their associated Python coding are presented below: 

1. Calculate the total number of votes cast. 

![image](https://user-images.githubusercontent.com/85533099/132108442-dbc95fb7-b171-45a7-b4af-0a9c5897c317.png)

![image](https://user-images.githubusercontent.com/85533099/132108452-da198de1-33c3-4114-9801-1de0b0870cf9.png)

![image](https://user-images.githubusercontent.com/85533099/132108458-8987e879-6d81-4c90-a528-7f59e4dab945.png)

2. Calculate votes by county:
  - Calculate the total number of votes cast within each county.
  - Calculate the percentange of votes from each county. 
  - Determine which county had the largest voter turnout.

![image](https://user-images.githubusercontent.com/85533099/132113872-ade1ef29-1d2a-4cec-b3a2-fad9f2861980.png)

![image](https://user-images.githubusercontent.com/85533099/132113878-2f7cb03c-71d9-45cf-96c2-4163d8816f5a.png)

![image](https://user-images.githubusercontent.com/85533099/132113887-06e20289-c0c4-4ae7-86b7-358bbd282500.png)

3. Calculate votes by candidate:
  - Get a complete list of candidates who received votes.
  - Calculate the total number of votes each candidate received.
  - Calculate the percentage of votes each candidate won.

![image](https://user-images.githubusercontent.com/85533099/132114158-abb10c95-01aa-4c53-9dbe-52c32dc95447.png)

![image](https://user-images.githubusercontent.com/85533099/132114164-c40c4e07-ddf1-4eaa-ad98-4e3602ef68ce.png)

![image](https://user-images.githubusercontent.com/85533099/132114166-2d61d55d-958e-4433-b599-e3c973800f8c.png)

![image](https://user-images.githubusercontent.com/85533099/132114171-9022447c-75b7-4e38-83f8-6c6f989b69cf.png)

![image](https://user-images.githubusercontent.com/85533099/132114175-7cc76ffa-ee16-41c3-ad22-7bbd7f7d336a.png)

4. Determine the winner of the election based on popular vote.

![image](https://user-images.githubusercontent.com/85533099/132114199-133433d1-3866-4b60-a79c-e63558c8093f.png)

## Challenge Summary 

### Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The results for voter turnout for each county was:
  - Jefferson county obtained 10.5% of the vote and 38,855 number of votes.
  - Denver county obtained 82.8% of the vote and 306,055 number of votes.
  - Arapahoe county obtained 6.7% of the vote and 24,801 number of votes.
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
The current analysis revealed how Python coding could be utilized to determine the results of a recent total Congressional election. As described above, the analysis conducted was limited to one particular congressional district consisting of a precinct of three counties in Colorado, i.e., Jefferson, Denver, and Arapahoe. However, the script has been created so that any variable of interest can be added for examination. The script is not "tied" to particular values and instead operates by generating lists that can be extrapolated from existing data. Therefore, this same exact code has powerful versatility and can be utilized to conduct any election audit analysis that the commission requests:
- The commission can apply the same script to election data files obtained for other congressional district elections in Colorado and yield the same type of data results  for each congressional district. 
- The existing script can be modified to run analyses to obtain other election results that might be of interest to the election commission. For example, this script can be performed on data files that also contain information about voters' political party affiliation if the election commission wants to examine voter turnout according to political party affiliation. We can create a list of party affiliation: "party_options = []" to obtain all the different party affiliations and a dictionary for party votes: "party_votes = {}", and perform the same script that was used for county turnout and candidate votes but applied to new party affiliation variables to determine the voter turnout for each different party affiliation, including the total number and percentage of votes. 
- This script can also be used to examine voter turnout based upon demographic charateristics, e.g., age, gender, race/ethnicity. Additionally, the script can delineate voter turnout based on suburban, urban, or rural areas. 
- In order to modify and successfully run the above script, however, the data files must be "clean." In other words, all of the qualitative data must be standardized to ensure that all words used are spelled correctly and appear exactly the same so that the computer can correctly identify each unique occurrence of a new option for lists. 

Thus, the current analysis using Python coding not only provided the results that the commission requested but the script that was developed can be adapted to other election audits as outlined above. The code can also be adapted for local election results as well as senatorial races. 
