# Election Analysis
## Overview
A Colorado Board of Elections employee, Tom, had asked us to help write a python script to execute the tabulation in a US Congressional precinct more efficiently than the previous Excel process. Our program will need to be flexible enough to be used to calculate results for other elections and still show all the required information, including:
1. The total number of votes in the precinct
2. The counties that sent in votes
3. The number of votes and the percentage of the total vote from each county
4. The county with the largest turnout
5. The candidates in the election
6. The number of votes and the percentage of the total vote for each candidate 
7. The winning candidate with their number of votes and percentage of votes

## Election-Audit Results
The analysis of the election showed that:

The total number of votes was 369,711.

The counties that sent in votes were:
- Jefferson 
- Denver
- Arapahoe

The counties results were:
- Jefferson had 10.5% of the votes and 38,855 total votes.
- Denver had 82.8% of the votes and 306,055 total votes.
- Arapahoe had 6.7% of the votes and 24,801 total votes.

The county with the largest turnout was Denver.

The candidates were:
- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

Their results were:
- Charles Casper Stockham received 23% of the vote and 85,213 total votes.
- Diana DeGette received 73.8% of the vote and 272,892 total votes.
- Raymon Anthony Doane received 3.1% of the vote and 11,606 total votes.

The winner of the election was:

Diana DeGette, with 73.8% of the vote and 272,892 total votes

![printedToCommandline](https://user-images.githubusercontent.com/83182353/118757196-3ca11f80-b832-11eb-97c5-f0fc9e8e13da.png)


## Election-Audit Summary
The script provided is programed to return the requested statistics for counites and candidates, and because it is reading all information for this summary data from the input file, it can output data for other counties and candidates with no edits necessary. If the input file is formatted different than the completed election, the code on row and 50 can be changed slightly to read in the correct information concerning candidates and counties. Similarly, row 9 cand be edited to ensure the file that needs to be read can be found by the program. In addition, if there is concern about a potential tie, the code from line 139 to 143 can be built upon to take that potential outcome into consideration in this script. 






