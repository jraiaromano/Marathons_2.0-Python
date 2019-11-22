# Marathons_2.0-Python
## Overview
This is the repo for a project that involved webscraping the data we used for a previous project directly form the source, then performing further analysis to come up with new and "interesting" findings. We then had to give a short presentation on our new insights.
## Project Takeaways
The webscraping was an absolute horrifying nightmare but it was also incredibly empowering. This project was one during which I could feel my own exponential growth.

The thing that fascinated me the most with this project, though, was how different a tool python is from Excel. Things that took me hours in Excel were the work of one short line of code in Python... but I also have the tendency to set up my dataframes like spreadsheets, a tendency exacerbated by a dataset that I was already familiar with in Excel. This made it impossible to plot properly in Python, so I had to force myself to create a dataframe that was Python-specific.

## The Pitch
Create a forloop formula to iterate over the web pages containing the marathon data from the [Excel Marathons project](https://github.com/jraiaromano/Excel_Marathons) and pull the data into an empty dataframe.  After loading the marathon and half-marathon data to dataframes in Python, perform EDA as usual. Think of a question that you find interesting and answer it with the data. Prepare a brief (5 minutes) presentation to share what you find. 

## The Data
Exactly and precisely the same data as that which I worked with for my Excel Marathons project, just in Python. Actually its a fairly clean dataset, although sadly there is one tiny error that is really consequential: the "winner" of one of the marathons is actually a runner from the half-marathon from the same year, so time is world-record breaking... except it's a lie. It is a recording error. Interesting, but this aside it's mostly clean.
## Approach to the Problem
So for this one, I sort of took up where I left off. This was the slide I created for our team presentation:
![Slide from Excel Marathons slideshow depicting the number of marathoners who participated in multiple races](https://user-images.githubusercontent.com/52726447/69395009-382e9180-0ca3-11ea-8944-f88a7ea4a974.png)
I decided to look at performance metrics to see why these runners might continue to run races. I looked first at their performance relative to other runners, then at their performance over time (in other words, their performance relative to themselves).
What I discovered was, I think, indeed interesting. There was no obvious correlation between runners doing well either relative to others or themselves to indicate why they might return to the run. I concluded that perhaps the race was in fact not very competitive at all, and that they might be running for the otherwise very touristy perks.
