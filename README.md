# Hammer Points
2018-23

This project draws inspiration from the concept/work of Tom Tango and "The Book." I wanted to figure out the effectiveness of starting pitchers over the last handful of seasons. I selected the 2018-2023 seasons. I wanted to include 5 full seasons since 2020 was shortened and some pitchers didn't participate. The approach involves tracking pitching performance points during the first three innings of games. I know it's not an exact measure, it offers a general sense of a pitcher's performance against the starting lineup once through. 


Here is a simplified points chart used to evaluate pitcher effectiveness, Not included are wild pitches and passed balls. Tango included this but I couldn't find a way to wxtract this information from the event column in ths csv files I downloaded:

2B, 3B, BB, HBP, wild pitches, and passed balls: 1 point each
HR: 2 points
1B: 0.5 points
SO: -1 point

Prerequisites:
Before using this tool, ensure you have the following prerequisites:
Python 3.x
Jupyter Notebook (optional)


To access the data files and save your results, you must mount your Google Drive. 

Ensure you have CSV data files for the seasons 2018-2023. You can place these files in your Google Drive or specify their paths in the code.

Execute the script responsible for combining and analyzing the data. Replace the placeholders with appropriate file paths

The tool includes an interactive loop for searching pitchers. Enter their names in the "Last, First" format to retrieve their cumulative Hammer Points.
