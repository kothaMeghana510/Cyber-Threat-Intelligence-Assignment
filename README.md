# Cyber Threat Intelligence Assignment

## Overview
This project analyzes cybersecurity techniques and assigns risk scores based on predefined criteria.

### Task 1:
Fetched and Analysed the data using Python

### Task 2:
Extracted the objects where type == 'attack-pattern' and stored them into a list called techniques to calculate the risk scores

### Task 3:
Each Technique is scored based on:
- Base score which starts at 5
Additional scores for keywords like
- Credential
- execution
- privilege
- persistence
- lateral

### Task 4:
Score is furthur updated on analysing the description of each technique based on keywords like
- administrator
- remote
- bypass
- stealth

## Task 5:
Stored all the techniques in a a list called scoredTechniques and sorted the techniques based on the score from highest to lowest
displayed the top 10 techniques which are high risk

## Final Output:
The techniques whose score is greater than 8.9 are the critical threats that analysts should investigate

## Technologies
- Python
- Google Colab

## How to run
- Open the notebook file in Google Colab.
- Run all cells.
- The top 10 highest risk techniques will be displayed.

