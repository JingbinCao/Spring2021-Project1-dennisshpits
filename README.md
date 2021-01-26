# Applied Data Science @ Columbia
## Spring 2021
## Project 1: A "data story" on how Americans vote

<img src="figs/title1.jpeg" width="500">

### Table of Contents
* [Project Description](#description)
* [Folder Structure](#structure)
* [Data Source](#data)
* [R Libraries Used](#library)

<a name="description"></a>
## Project Description
Term: Spring 2021

+ Project title: How Immigrants Influence Elections. The Past and Present
+ This project is conducted by Dennis Shpits

+ Project summary: Immigration does not only change the dynamics of the labor market, but might also change election outcomes. Recently there have been rumors that the Democratic party plans on securing more votes in elections by increasing immigration. This analysis will try to provide statistical evidence of whether this assumtion holds water.
<a name="structure"></a>
## Folder Structure
```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```
<a name="data"></a>
## American National Election Studies
For our analysis we used the following [link](https://electionstudies.org/data-center/). The data used has been zipped and placed in the data folder. The R notebook will handle the unzipping of the file.
<a name="library"></a>
## R Libraries
The following R libraries should be installed in order to run this notebook:
* ggplot2
* haven
* dplyr