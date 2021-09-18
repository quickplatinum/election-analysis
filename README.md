# Module 3-Python
# Election-Analysis
## Project/Challenge Overview
A Colorado Board of Elections employee requested my help in completing an election audit of a recent local congressional election. The following tasks were  included in the completed election audit and viewable in the election result and election analysis files:

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.

- The idea is to create a script usiong Python to help analyze a CSV file, the script will run automatically and create a result file that can be shared with the county employee and a github repository. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code 1.60.1
- A slighlty olrder vertison of Python was used depsite 3.9 being the most current iteration, the latest current Visual Studio Code was used.

## Inital Election Summary
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
  - Diana DeGette, who received 73.8% of the votes and 272,892 number of votes.

Beyond the final outcomes and results, there were other key insights that were requested to be included. The client requested to know 3 further results and analysis points. The findings of the following tasks were added to the final election audit:

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes each county contributed to the election.
3. Determine which county had the largest turnout.

## Completed CHallenge Summary
- Attached is a screenshot of the election_results.txt file whcih inbcludes a snapshot of all results and additonal requests.
![election results](https://user-images.githubusercontent.com/88692025/133906721-cc876e2f-f135-46ab-b5ee-fa7c276521ec.PNG)

- Total Votes: 369,711

- County Results:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Largest County Turnout: Denver

- Candidate Results:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
  - 
- Election Winner:
  - Diana DeGette
  - Vote Count: 272,892
  - Percentage: 73.8%

## Election Committee Statement
![for loop](https://user-images.githubusercontent.com/88692025/133907095-ac25d720-2b6e-4a15-8d0a-38f28e100f88.PNG)
- The above for loop is the key that makes this code so verstaille as it collects the data needed from any candidate combination and is future proofed if more counties are added in the future.
- The script that is currenlty written is a great way to analyze any election data in the future, the script is programmed to handle any amount of votes and CSV data lines. As such if more counties and votes are added as well as candidates, the analysis and result system will be easy and clear. Therefore, it would be a great businness move fo the commision to use this code going forward as it is clear, verstaille and easily changed.
