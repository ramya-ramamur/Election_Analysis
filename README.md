# Election_Analysis
## Overview of Election
A Colorado Board of Elections wants to complete the election audit of the local congressional precinct election. They want to know the following;
1. The total number of votes cast.
2. The list of candidates who received votes
3. The percentage of votes each candidate won
4. Winner of the election based on popular vote.

## Resources:
 - Data Source: election_results.csv
 - Software: Python 3.8.8, Visual Strudio Code 1.61.2
 
## Election Audit Results

![Screen Shot 2021-11-03 at 4 28 01 PM](https://user-images.githubusercontent.com/75961057/140232752-aecc39d9-ab01-44f1-bedf-0b6b92f6b3bf.png)

## Election-Audit Summary
The Colorado Board of Election can use the python code in PyPoll_Challenge.py used to analyse this dataset for any election as long as the data is captured and stored in the same way as in election_results.csv. as follows:
 - Ballot ID	
 - Location (In this dataset, it is County)
 - Candidate

Modifications should be made at the following lines of code

1.The path to load and read the .csv (dataset) file and the path to store the .txt (analysis results) file 

![Screen Shot 2021-11-03 at 4 53 17 PM](https://user-images.githubusercontent.com/75961057/140234700-33034f63-8721-49f0-a2db-e0b1262af1d9.png)

2. Change "County" if necessary from the print statements below to reflect the type of election it is - for eg: "City Votes:" in line91

![Screen Shot 2021-11-03 at 5 00 19 PM](https://user-images.githubusercontent.com/75961057/140235527-27ec681b-2d34-4271-a7aa-f3262e8d2074.png)

![Screen Shot 2021-11-03 at 5 00 42 PM](https://user-images.githubusercontent.com/75961057/140235533-b30b0b68-a017-4e0b-beb2-b4ad83f9b2bc.png)

3. The code in PyPoll_Challenge.py can also be wrapped inside another analysis, for example, a countrywide election analysis that can analyse by county for each state. Inside the function that analyzes State results, this program can be called and the results used for calculating State voting numbers. 
