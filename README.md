# Table of Contents
1. [Defining the Problem](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization#defining-the-problem)

2. [Data Cleaning](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization#data-cleaning)
   
4. [Analyzing](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization#analyzing)
   
6. [Visualization and Final Recommendations](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization#visualization-and-final-recommendations)
   
8. [References](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization?tab=readme-ov-file#references)

# Defining the Problem
My shelter project grew out of my personal experience with adopting my two dogs (Moose and Junimo) from local shelters, but it also became a perfect avenue for applying my skills as a data analyst. Having seen the challenges shelters face such as overcrowding and resource constraints, I wanted to take a deeper dive into these issues through data. I started analyzing shelter data to identify patterns in animal intake, seasonal trends, and opportunities to optimize operations. 

My personal connection to the cause gave me an empathetic perspective when interpreting the data, which, combined with my technical skills, helped me build visualizations and develop actionable solutions. This project is not just about helping shelters; it’s also a reflection of my ability to use data to address real-world problems that matter deeply to me.

# Data Cleaning

The setup for this project started by creating copies of the original sheets. The purpose behind that is so that I could explore and make changes without fearing of altering the originals. The original dataset would remain untouched on sheets labeled ACC Intakes and the manipulated set would be labeled Working Intake.

One of the first steps for cleaning was taking a look at the files as is. Commands in Power Query allowed me to see that the dataset came with a few duplicate values. These were first removed from the Working Intake sheet. Next, the question became which of the existing rows would need reformatting. One of the things I had noticed was that since shelter dogs are often mutts, the combination of three or so different breeds be listed in the breed column was not uncommon. I had decided to use the Text to Column data tool to split the original breed column into primary, secondary, and tertiary breeds. Finally, I saw that the age column was in a non-standard format. So, I created a function that converted all inputs into a new column that described the age in terms of months.

Uncleaned Data:
![Uncleaned Intakes](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization/blob/main/Uncleaned%20Data.png)

Cleaned Data:
![Cleaned Intakes](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization/blob/main/Cleaned%20Data.png)

# Analyzing
The data set contains animal types from typical household dogs and cats to a mix of wildlife. I decided to focus on trends in population over time for dogs but did find some notable trends in the wildlift data available. One unexpected takeaway was a larger bat population than I would have originally guessed. This led me to research the native bat population in Austin and find that the increased numbers of bats coincided with the bats breeding seasons.

Another notable trend is that the number of animals picked up goes up on average in the warmer months. Additional research on this finding allowed me to discover that this is contradictory to typical shelter trends, where the members of the community are more likely to report strays in winter months. 

Finally, I had decided to examine the breakdown of sexes for the intake animals. The key here is that a large portion of dogs are often "fixed". The status of their sex can indicate if the animal has either been be a useful measure if an intake animal is abandoned or lost.

# Visualization and Final Recommendations

The visualizing steps focused on creating charts based off of trends found during the Analysis step. One is of a pie chart showing the break down of intake sex status. The other is a timeline graph showing the intake count of the 5 most popular breeds. Both graphs are able to be manipulated by a filter to select the applicalbe year. 

Final recommedations based on the trends would be to have staff increase training on how to handle "outlier" animals such as bats during their breeding season. Additionally, I would recommend the city of Austin do a research study to find the cause of shelter populations increases in the summer. Is this trend indicative of loose pets? Finally, the intake sex data indicates that most of these animals come from former homes. I would suggest the city promote reading material about pet ownership to try to reduce the number of families that adopt a pet and ultimately decide to release to the shelter. 

![Dashboard ](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization/blob/main/Screenshot%202025-05-15%20143639.png)

# References
AaronSchlegel. (2018, February 16). Austin Animal Center Shelter Outcomes. Kaggle. https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-outcomes-and 

Caudill, M. (2019, November 20). Cold weather brings influx of animals to shelters. Mansfield News Journal. https://www.mansfieldnewsjournal.com/story/news/2019/11/20/cold-weather-brings-influx-animals-shelters-humane/4230836002/ 

Unknown. (2025, February 8). Why do most dogs end up in shelters?. The Environmental Literacy Council. https://enviroliteracy.org/why-do-most-dogs-end-up-in-shelters/ 
