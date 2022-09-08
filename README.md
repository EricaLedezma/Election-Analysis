# Election-Analysis
## Project Overview

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
![image](https://user-images.githubusercontent.com/111028230/189001271-60ed383a-e08a-454f-85b7-779fdaae38dc.png)

The analysis of the election show that:
- There were 369,711 votes cast in the election.
- Votes broken down by county:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Largest County Turnout:
  - Denver
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidates results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received "3.1%" of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes
  
## Election-Audit Summary
The attached Python and Visual Studio Code used to analyze this election data is mutable and can be used for the analysis of future elections. Below are the requirements needed in the data collection and updated to make to the code to correspond with the current election data.
  Data collection:
  - election results would need to be collected via csv file
  - three data points
    - Ballot ID
    - County
    - Candidate
    
      ![image](https://user-images.githubusercontent.com/111028230/189005140-c9b89463-e778-4449-a3d4-4135a9e35ca1.png)
  
  - edit the code for the file that will pull the election results:
    - You will need to edit the file location (i.e. "Resources")
    - you will need to edit the title of the csv (i.e. "election_results.csv")
    
    ![image](https://user-images.githubusercontent.com/111028230/189005397-5924ce25-d2be-4830-b447-67633499edb9.png)

  - edit where you will save the results once the analysis has run
    - you will need to edit the file location (i.e. "analysis")
    - you will need to edit the text file (i.e. "election_analysis.txt")
    
    ![image](https://user-images.githubusercontent.com/111028230/189005992-471c9a25-6fd6-4432-80ac-48a35c9e0ce8.png)
