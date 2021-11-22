# Election Analysis Audit

## Election Analysis Audit Overview

The purpose of this project was to use python to pull and read data from the election_results.csv file, and to display an analysis of the election results by the following metrics.

**1.** Total number of votes cast in the election\
**2.** A list of candidates who received votes in the election\
**3.** The total number of votes for each candidate\
**4.** The total percentage of votes for each candidate\
**5.** The winner of the election based on the popular vote\
**6.** The number of total votes per county\
**7.** The percentage of votes per county\
**8.** The County with the largest voter turnout\
**9.** Write these results into a .txt file for the analysis using python\

Additionally we used Git Bash to add the files we worked with to our github repository vs using the github website to learn how to push files through Git.

An image of the results is displayed below.

![election results](https://user-images.githubusercontent.com/92459399/142781593-f388a214-b04a-421a-b5cb-354b3f4270eb.PNG)

## Resources and Analysis files

The data was pulled from the election results.csv file in the **Resources** folder, while the election results were written in python code and exported via VS Code to the Election_Analysis file in the **analysis** folder. the files used in this analysis are included below

[election_analysis.txt](https://github.com/mshariqnaeem/election_analysis/files/7577292/election_analysis.txt)\
[election_results.csv](https://github.com/mshariqnaeem/election_analysis/files/7577293/election_results.csv)\

## Election Audit Analysis Results!

As per the requirements we needed to calculate the following information for the following election results

### Total Number of Votes Cast

The total number of votes cast in the election were 369,711 which were calculated using the following set of code.

![Total votes code](https://user-images.githubusercontent.com/92459399/142781990-a38981d1-e846-4068-9553-73b355ea789e.PNG)

### Candidates Who Received Votes

The next step was to find who the candidates who received votes were and how many votes they received which is calculated in part by the code below

![Total votes code](https://user-images.githubusercontent.com/92459399/142782050-a2ccf8e9-c7fe-4f3f-812e-bf3f193a8772.PNG)

### Total Percentage of Votes per candidate

The total percentage of votes per candidate was as follows

**Charles Casper Stockham: 23.0% (85,213)**\
**Diana DeGette: 73.8% (272,892)**\
**Raymon Anthony Doane: 3.1% (11,606)**\

The total percentage of votes per candidate was calculated and displayed to the terminal with the following steps

![Vote percentage per candidate](https://user-images.githubusercontent.com/92459399/142782271-7ddb6bf4-bd52-4ec8-a6a0-372c822c3f48.PNG)

### Votes per County

The votes for each county are broken down below:

**Denver: 306,055 votes (82.8%)**\
**Jefferson: 38,855 votes (10.5%)**\
**Arapahoe: 24,801 votes (6.7%)

they were calculated using the following set of code:

![County votes](https://user-images.githubusercontent.com/92459399/142782475-54ea1537-c0c1-4324-9909-10389e24f39e.PNG)

### Winning Candidate?

The winning candidate and result breakdown are below:

**Diana Degette**\
**Votes: 272, 892**\
**Vote Percentage: 73.8%**

![Winning Vote](https://user-images.githubusercontent.com/92459399/142782400-1735ba2c-d764-4d66-9dd1-3c8c3a09543b.PNG)

### Export Results to .txt file

The final step was to save our election results to a .txt file. We accomplished this and have included some of the code used to accomplish the goal below:

![print to txt code](https://user-images.githubusercontent.com/92459399/142786300-34c5888f-32df-417b-97a3-5185419e130b.PNG)

the final result of the code we used above was for all the results for our 5 categories (Total votes, Count votes, Largest county turnout, Candiate votes, and winner of the election) being printed/written to the election_analysis.txt file located in the analysis folder.

Below is a picture of the final results:

![election txt file](https://user-images.githubusercontent.com/92459399/142786475-003b0a1e-0eb9-480f-be28-8213d9acc56c.PNG)

## Summary

This election audit assignment gave us a strong base understanding of how to use python and its functions to pull data from .csv and similar files and be able to interpret, code to output file information within the terminal, and write our findings to an external file.

If further data was added to this data set we now have a strong understanding of Python and how to use it to easily and efficiently analyze datasets to come to conclusions from the provided data using python versus manually sifting through thousands of rows of data.

Python is a powerful tool and with its ease of use in comparison to VBA we are able to quickly and efficiently use this for future data analysis purposes
