# Utopia Assignment - 20th July 2021
  #### Author - Pragya Rai (Data Analyst)
  #### Contact - drpragyasan@gmail.com

## Problem Statement
There are two datasets:

consumption_data.csv; --> this file contains radio plays consumption for a particular region and timeframe

feed_station_mapping.csv; --> this file contains the mapping between feeds and stations

Context:

Radio play consumptions come in at 'feed' level, These can have a many-to-one relationship with a given radio station. The relationship between feeds and radios is to be found in the feed_station_mapping file.

Your tasks:

- Consolidate the data so that we do not double count plays coming from feeds that belong to the same station If you do not find the parent station for a given feed, just default to the feed info and use that as your 'station' instead.
- Further clean the data as you deem approriate in order to perform an analysis on this dataset
- Present the steps you have gone through for the data processing (eg. python notebook or any other data management tool you use)
- Present any additional findings from the analysis you performed on the cleaned dataset in some visualisation tool (Tableau preferably but not mandatory)

## Solution
- Solution is presented in Jupyter Notebook named **'Utopia_assignment.ipynb'**. With detailed comments.
- Data set is zipped and uploaded in this repo.
- Visualization is done in **Tableau**
- Output csv data from notbook is used in **Tableau** for visualization.
- Sample screenshot of Tableau Dashboard is attached named **'Utopia Music Consumption Insights_Tableau Dashboard.JPG'**.

## How to run
- Download the Note book load it in your Jupyter Lab.
- Download the data and unzip it in Jupyter's working directory. And run the notebook cells.
- Last step in the notebook will create a csv file in the working directory. Use this for data visualization.
- Link to Tableau Public dashboard is: https://public.tableau.com/views/UtopiaRadioFeedDashboard_Local/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
