# Election_Analysis
Conducting Election Analysis using Python and VSCode

## Overview/Purpose of Election Audit

The purpose of this Election Audit was to provide the election commission additional election data along with a written analysis highlighting voter turnout for each county, percentage of votes from each county, the county with the highest turnout, and of course the winner of the election. Of note, in order to analyze the data, python and the vscode platform were used.

## Election Audit Results: 
Below is a detailed breadown of the Election Results in bulletized format. Additional data could be provided upon request.  

* Total number of County votes and County Percentages:
  * As depicted in the image below, there were a total of 369,711 total votes cast in the election. Out of the 369,711 votes, Denver was the county that accounted for the highest number of votes [306,055], highest turnout, and highest percentage of the votes [82.8%], followed by Jefferson County and Arapahoe County respectively. See below image for the full detail. 
![Total_Votes_County_Votes2](Resources/Total_Votes_County_Votes2.png)

* Candidate Votes and Percentages:
  * Out of the 369,711 total votes, [73.8%] were cast for Diana DeGette with her final result of [272,892] votes. This was significantly higher than the other candidates. As depicted in the below image, Charles Casper Stockham only accounted for [23%] of the total votes while Raymon Anthony Doane accounted for lowest percentage of votes [3.1%]. See below image for full detail including total number of votes for each candidate.  
![Candidate_percentage_votes2](Resources/Candidate_percentage_votes2.png)

* Winner of the Election:
  * As mentioned above, Diana DeGette was the candidate with the highest number of votes and highest vote percentage which makes her the winner of the election. Below is winning result. Congratulations to Diana DeGette!
![Winner_of_Election2](Resources/Winner_of_Election2.png)

## Election Audit Summary:
The use of Python and VSCode streamlined the election analysis process. After the code was modified, all deliverables that the Election Commission asked for could be presented at a click of a button. The code used for this most recent election could also be applied to future elections with minor changes. 
* One modification that would most certainly have to be made is the path to the file. By introducting a new data source, we have to make sure we provide the appropriate file path in order to analyze the correct data. With a simple change to "file_to_load" and "file_to_save", you can start analyzing different election data. 
* I would also recommend inserting a code that outputs graphs/charts to better understand the data. For example, when comparing county or candidate vote number and percentages, a simple pie chart or bar graph could have been used to visualize the data. By installing and importing "matplotlib" into our code, we can provide these types of visualizations and make our election analysis even more detailed. Below is a link to instructions on how to utilize "matplotlib." I also included a link to the code we used ("Pypoll_Challenge.py") for the election analysis and the "election_results" csv.
  * https://www.geeksforgeeks.org/graph-plotting-in-python-set-1/
  * [PyPoll_Challenge](PyPoll_Challenge.py)
  * [election_results](Resources/election_results.csv)
