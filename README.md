###### election_analysis
Election Audit Analysis for the Colorado Board of Election.

![thinkstock-colorado-vote-election_1200xx3751-2110-0-16](https://user-images.githubusercontent.com/93900628/145734960-c88bae39-8df6-4979-8908-a9d0133bba4f.jpeg)

# Overview of the Election Audit

### Purpose:

Tom is a Colorado board of elections employee who needs assistance with an Election audit of the tabulated results for the US Congressional precinct in Colorado. Tom's manager wants the election audit process automated using python. 
The results of the votes are determined by the following three primary methods:

1.) Mail-in ballots: that are hand-counted at the central office
2.) Punch Cards: that is collected and fed into a machine that tabulates vote totals and sends the results to the central office
3.) Direct Recording Electronic Machines: have memory cards that are sent to the central office and are read by a computer.

The votes cast by these three voting methods determine the election, this election audit will be used to certify this US congressional race.The automated process will determine on the following for the audit:
1.) The total number of votes cast.
2.) A complete list of candidates who received votes and the counties that voted.
3.) The total number of votes each candidate received.
4.) The percentage of votes each candidate won.
5.) The county with the highest voter turnout.
6.) The winner of the election is based on the popular vote.

Resources

Election Audit Results:

The analysis shows the follwing results

There were 369,711 votes cast in the election.

The results for each county were:
    Jefferson county cast 38,855 votes, 10.5% of the total vote.
    Denever county cast 306,055 votes, 82.8% of the total vote.
    Arapahoe county cast 24,801 votes, 6.7% of the total vote.

The county with the largest number of votes was Denver.

The results for each candidate:

Charles Casper Stockham received 23% of the vote and 85,213 number of votes.
Diana DeGette received 73.8% of the vote and 272,892 number of votes.
Raymon Anthony Doane received 3.1% of the vote with 11,606 number of votes.

The winner of the election was Diana DeGette who received 73.8% of the votes and 272,892 number of votes.


Election Audit Summary

This automated process could also be used for primary,general and local elections, some modifications would be have to made for the following:
 - Change county list to state list for a primary, general or local election
 - The amount of votes for each candidate by county could be determined with modification to the code by adding in another if loop.













