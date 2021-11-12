# Written Analysis of the Election Audit
Performing an election audit for Arapahoe, Denver, and Jefferson counties.

# Working with Python

## Overview of Election Audit

### Purpose
The purpose of this analysis is to quickly and efficiently look through voter results for the candidates Charles C. Stockham, Diana DeGette, and Raymon A. Doane and determine not only who won the election, but also information on what county had the largest number of voters, the number of votes each candidate received, and the percentage of votes each candidate receieved. This extra analysis provides the election audit committee with more information about this election and can be used in data-driven decision making.

## Results
* The number of votes that were cast in this congressional election is 369,711
* The breakdown of the number of votes and the percentage of total votes for each county in the precint are as follows:
     * Jefferson: 10.5% (38,855)
     * Denver: 82.8% (306,055)
     * Arapahoe 6.7% (24,801)
* The county with the largest number of votes is Denver 
* The breakdown of the number of votes and the percentage of the total votes each candidate received are as follows:
     * Stockham: 23.0% (85,213)
     * DeGette: 73.8% (272,892)
     * Doane: 3.1% (11,606)
* The candidate that won the election is Diana DeGette with a total vote count of 272,892 and 73.8% of total votes.

## Election Audit Summary
The code used for this election can also be used for any election, with some modifications. This is because of the IF statements that were built into the script that allows candidate and county names to be added to the candidate and county lists.
![election_script](https://github.com/julianneitliong/election_analysis/blob/e2a329c7ee00759544bd47e4fc511223e86dfd1e/election_audit_summary.jpg)

This means as long as the election results are held in a csv file and is formatted similarly to our source (3 rows: Ballot ID, County, Candidate) the code will add the new candidate or new county to the each of their respective lists. In addition, depending on the business question the election audit committee would like answered, other variables can be created for analysis. For example, calculating the average number of votes the candidate receives in each county in order to understand how effective their election campaigns perform. In summary, this election analysis script can be re-used for any election because it is not specific to this csv source file. 
