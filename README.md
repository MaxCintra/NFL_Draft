# The Winning Formula: Predicting NFL Success through Combine Analytics
Project 4: Max Cintra, Josh Eskra, Boston Proffitt, Rose Kasper

## Overview
Through using machine learning models and other analysis, we are attempting to create a application that allows users to make predictions on NFL prospects based off of their measurables, and through this process, discover possible connections.

## The Dataset
All Data was pulled from <a href = "https://www.pro-football-reference.com/">Pro-Football Reference</a>.

For context on drills see <a href = "https://www.si.com/nfl/2020/02/24/nfl-combine-2020-drills-workouts-explained-on-field-applications"> Sports Illustrated </a>.

## Tutorial
1: Clone Repository

2: Open folder using jupyter notebook

3: Open create_database_creds.json and enter PostgreSQL user credentials, save and close file

4: Run the data_setup_cleaning_to_database.ipynb file

5: Run the Working_Model_Drafted_to_Allpro_SQL.ipynb file

6: Run the Working_Model_Drafted_to_Probowl_SQL.ipynb file

7: Open VSCode and open integrated terminal

8: Run flask app by entering command "python app.py"

9: Follow link in terminal, and enter desired test data

## Key
### Position
'QB': 1

'RB': 2

'T': 3

'WR': 4

'DB': 5

'LB': 6

'DT': 7

'DE': 8

'G': 9

'TE': 10

'C': 11

'P': 12

'OL': 13

'NT': 14

'FB': 15

'OLB': 16

'CB': 17

'S': 18

'ILB': 19

'LS': 20

'DL': 21

### College
Due to amount of schools within this data frame, to find a schools associated number, run the code below.

'Insert desired school here' = df[df['College/Univ'] == 'Insert desried school here']

## Presentation Overview
To find the results we found, view our <a href = "https://docs.google.com/presentation/d/1GtA_nVt5ErDfyAnrdmhtmVOjtg00gSBk4NyIhyiP4ck/edit?usp=sharing"> Google Slides </a>.

