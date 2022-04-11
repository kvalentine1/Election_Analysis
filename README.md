# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has asked for an election audit of a recent local congressional election. The goal of this audit is to determine the votes and percentage of votes each candidate and county received and well as who is the winning candidate and which county had the largest voter turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.10.4, Visual Studio Code 1.65.2

## Election Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.

- The counties included in this election were:
	- Arapahoe
	- Denver
	- Jefferson
- The county results were:
	- Arapahoe County votes counted for 6.7% of the total votes with 24,801 votes cast in the county.
	- Denver County votes counted for 82.8% of the total votes with 306,055 votes cast in the county.
	- Jefferson County votes counted for 10.5% of the total votes with 38,855 votes cast in the county.
- The county with the largest voter turn out was:
	- Denver county which counted for 82.8% of the total votes with 306,055 votes cast in the county.

- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
- The candidate results were:
	- Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
	- Diana DeGette received 73.8% of the vote and 272,892 votes.
	- Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
	- Diana DeGette who received 73.8% of the vote and 272,892 votes.

## Election Audit Summary
This script can be very versatile for any Board of Elections’ needs. The way in which the script is written is not limited to elections with just three values. This script could easily be used with a CSV data set that includes any number of candidates and districts. It is also easily adaptable to districts other than counties. The script can be edited to change county/counties to states, cities, and districts of cities. The script can be used for a small town’s mayoral election with two candidates, or for the primaries for a nation’s presidential election with 16 candidates. Additionally, the candidates value could be changed to proposition or ordinance to track votes for legislature measures requiring a citizen vote.
