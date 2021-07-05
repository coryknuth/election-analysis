# Election Analysis

  At the request of the local election commission, we have created a python script which will tabulate election results from the raw vote data, and calculate and declare the winner of the election. With this script we are now able to also examine some of the data broken down by county, to see where votes came from, as well as the total and percentage of votes for each candidate. Below is an explanation of our process, as well as the results of the election we analyzed.
  
## Election Results

  The results of the election were as follows:
  - There were a total of **369,711** votes cast
  - Those votes broken down by county were:
      - Jefferson: 10.5% (38855 votes)
      - Denver: 82.8% (306055 votes)
      - Arapahoe: 6.7% (24801 votes)
  - Denver County provided by far the most votes of any county.
  - The voting totals broken down by candidate were:
    - Charles Casper Stockham: 23.0% (85,213 votes)
    - Diana DeGette: 73.8% (272,892 votes)
    - Raymon Anthony Doane: 3.1% (11,606 votes)
  - The winner of this years election was:
              **Diana DeGette** with **73.8%** (*272,892*) of the total votes.

![Text Output](https://github.com/coryknuth/election-analysis/blob/ee8893ae869de12e1945a73117077846bd5f1a74/Text%20Output.png)
              
## Future Elections

  All of the tabulation was completely automated by our python script, which could be easily modified for application in other, future elections. Our reccomendations for upgrades that could be made to the script for use in future elections would be to modify the code to analyze more data categories. This script will look at candidates, vote totals, and calculate vote percentages, as well as analyze county by county, but with some additions to the code we could look at more data categories if they were provided. Perhaps broken down by specific polling location, or even time of day the vote was cast. Secondly, we could output the results to something other than a text file. We would recommend an output that could be integrated with both a website to display results as well as your database program for record keeping of election results
