# NBA Team Optimization using Linear Programming
This project utilizes Linear Programming techniques to construct an optimal NBA team for the '22-'23 season, taking into consideration factors such as player performance, salary cap restrictions, and position requirements.

## Introduction
In this project, we leverage Linear Programming to build an NBA team that maximizes the overall Player Efficiency Rating (PER) while adhering to salary cap limitations and positional constraints. By formulating the problem as an optimization model, we aim to identify the most effective team composition for the upcoming '22-'23 season.

## Usage
  1) Prepare the input data:
   - Update the player data file (players.csv) with the desired players' information, including their performance metrics and salary details.  
   - Modify the position requirements file (positions.json) to reflect the desired distribution of positions within the team.
    
  2) Run the optimization algorithm:
   - Execute the main script: python optimize_team.py
   - The program will utilize Linear Programming techniques to construct the optimal team based on the specified criteria.
    
## Results
After running the optimization algorithm, the program will generate a report summarizing the selected team members, their positions, salaries, and corresponding Player Efficiency Ratings (PER). Additionally, it will provide insights into the overall team performance and its adherence to salary cap restrictions.
