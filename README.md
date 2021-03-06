# Election_Analysis

## Project Overview
Tom a Colorado Board of Elections employee has been asked to perform an election audit. Tom's manager wants to know if we can help Tom use python instead of Exel to automate it. Our job is to generate a vote count report to certify this U.S. congressional race. The following are the tasks that we were asked to perform. 

1.  Calculate the total number of votes cast.
2.  Get a couplete list of candidates who received votes.
3.  Calculate the total number of votes each candidate received.
4.  Calculate the percentage of votes each candidate won. 
5.  Determine the winner of the election based on popular vote. 

## Resources
- Data Source: election_results.csv
- Software:  Python 3.6.1, Visual Studio, 1.38.1

## Summary 
The analysis of the election show that:  
- There were 369,711 votes cast in the election.

- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane

- The candidate results were: 

    - Charles Casper Stockham had 23% of the votes and 85,213 number of votes.
    - Diana DeGette had 73.8% of the votes and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.

- The winner of the election was: 
    - Dana DeGette who received 73.8% of the vote and 272,892 number of votes.

## Challenge Overview
The challenge required some additonal data to complete the audit. This data was:
   - The voter turnout for each county
   - The percentage of votes from each county out of the total count
   - The county with the largest turnout

The dataset election_results.csv contained data consisting of Ballot Id, County name and Candidate name. 
We calculated County and Candidate information such as total votes for each and also percentage of votes for each. We used a for look to iterate through each row of data and created and defined two dictionaries for County and Candidate. To iterate through each row in the data set we created a for loop here is an example of our code in doing this

![Code example](https://user-images.githubusercontent.com/94208810/143664595-91a87539-8d75-42fd-9c12-489bf1920e50.png)


Achieved this by running a python file in the command line, and performed necessary calculations to achieve desired results.          Created and added keys and values to a dictionary, used decision sttements to help check condition. Applied memembership and logical operators to decision statements. Used repetition statements to iterate through the list and dictionary. We created an output file to print our results.

## Challenge Summary
The voter turnout for each County. 
    - Jefferson had 38,855 voters which made up 10.5% of the vote.
    - Denver had 306,055 voters which made up for 82.8% of the vote.
    - Arapahoe had 24,801 voters which made up for 6.7% of the vote.

The percentage of votes from each county.
    Jefferson had 10.5% 
    Denver had 82.8%
    Arapahoe had 6.7%

- The county with the highest turnout is Denver at 82.8% and total of 306,055 votes.

- The Python script used for this election analysis can be used for all election audits with the same analysis requirements and similar datasets of even bigger sizes with some simple modifications. 
- 
- ![Screenshot (37)](https://user-images.githubusercontent.com/94208810/143662723-c9106ac9-476f-4f12-8fed-81ca0d6a6510.png)
