# Scripts

This folder contains Python scripts used to clean and preprocess IPL datasets using **Pandas**.

## Script 1

Uses:

* `ball_by_ball_data.csv`
* `teams_data.csv`

Tasks performed:

* Replaced team ID numbers with team names using `teams_data.csv`
* Removed unnecessary columns
* Saved the cleaned dataset

## Script 2

Uses:

* `ipl_matches_data.csv`
* `teams_data.csv`

Tasks performed:

* Replaced team ID numbers with team names
* Removed unnecessary columns
* Created a **result column** describing match outcomes (win by runs or wickets)
* Flagged the **final match of each season**
* Saved the cleaned dataset
