# Colorado Election Analysis
Python script to analyze election results in a local congressional election in the state of Colorado. The largest voter turnout was in Denver County.  
  
## Project Overview
We were given the task of determining the following election results of a Colorado Congressional election:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

The final challenge code used to complete the analysis can be found [Here](https://github.com/JonathanBrown003/Election_Analysis/blob/main/PyPoll_Challenge.py)

## Resources
The original data source used for this analysis was election_results.csv found in the Resources Folder of this repository: [Resources Folder](https://github.com/JonathanBrown003/Election_Analysis/tree/main/Resources) 
 
 We used Python script along with Visual Studio Code to write this analysis.
 
## Summary
The analysis of the election showed the following:

1. The total votes cast in this election were 369,711, of which the majority were cast in Denver County (306,055).

2. The 3 candidates running in this election were Charles Stockham, Diana DeGette, and Raymon Doane.

3. As you can see below, Diana DeGette overwhelmingly won with 272,892 votes or 73.8% of the total cast. Stockham was in a distant second with 85,213 votes (23%) while      Doane received just 11,606 (3.1%) votes.    

![](https://raw.githubusercontent.com/JonathanBrown003/Election_Analysis/main/Election_Results_Capture.PNG)

## Challenge Summary
This Python script could be modified to tally more data like ensuring there aren't any duplicate votes being counted by using syntax that iterates through column 1 of the CSV file to ensure each "Ballot ID" is a unique value/integer. More columns of data would be helpful for analyzing more data about this election. This challenge was very difficult with my very minimal skill level in Python, it took a lot of debugging, module work, and google searches for the script to run correctly. 
