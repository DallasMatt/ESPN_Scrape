Project Title
ESPN Play-By-Play API

Description
This project scrapes the ESPN website to get all NFL games played in 2022. Then, it accesses the ESPN API for each game. 

This project's two outputs are: 
(1) A directory full of JSON objects that store performance data for every player for every week. 
(2) A CSV file that has team-level statistics

Dependencies
This project uses the following libraries in a Python 3.8 environment.
bs4
urllib
requests
re
json
pandas
os
warnings

Executing program
Final Project.ipynb has all code needed to run the program.

Features
(1) Screenscraping of ESPN's NFL Schedule website
(2) Accessing ESPN's Player Data API for data such as Player Name and Image
(3) Acessing ESPN's Game Data API for play-by-play data
(4) Creates three directories (Passing, Receiving, Rushing) that store Weekly Player files as JSON objects
(5) Creates a CSV dataset of full-season performance by team

Additional Files
data_dictionary.csv : Explains all metrics
successful_play_data.csv: Output of Final Project.ipynb
Week 10.json: Output of Final Project.ipynb; sample of the files in the JSON file directories


Authors
Matt McKenna is the sole author.
