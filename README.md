### 2020 United States Presidential Election

To get some hands on experience using Tableau and practice data cleaning, I decided to analyze a dataset of presidential election results. With the amount of coverage that this election got in a year with few positive distractions, I thought this would be an interesting dataset to examine. A link to the original dataset can be found in the link below. It was submitted to Kaggle by Raphael Fontes using data collected from Reuters.

The original file provided the votes for each candidate at a county-level. This offered the opportunity to view the election at a detail that is very rarely seen. However, after loading the dataset into Tableau, I found that there were roughly 1.2k locations that Tableau was unable to match to U.S. counties. This was due to multiple issues; locations in the dataset representing cities instead of counties, election districts that did not fall on county lines, etc. To fix these issues, I was faced with either matching each location one by one in Tableau or removing them form the dataset. Rather than omitting such a large portion of the dataset and having incomplete data, I decided to view the data at a state-level. 

[Original Dataset](https://www.kaggle.com/unanimad/us-election-2020?select=president_county_candidate.csv)  
[Tableau Dashboard](https://public.tableau.com/profile/tyler.dangel#!/vizhome/ElectionData_16091568606920/ElectionData)
