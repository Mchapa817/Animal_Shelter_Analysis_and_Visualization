# Improvements
Over the past months, I have grown significantly as a data analyst, enhancing both my technical expertise and analytical mindset. With this growth, I’ve decided to revisit and refine my shelter analysis. My goal is to apply the advanced skills I’ve developed, such as more effective data visualization techniques, improved data cleaning practices, and more robust statistical methods, to deepen the insights and impact of the analysis. By reworking this project, I aim to ensure that it reflects my current capabilities and delivers meaningful results that showcase the value of data-driven decision-making.

# Goal
My goal with this project is clean, analyzes create a final Dashboard that summarizes notable intake trends from the Austin Animal Center as well as generate possible recommendations based on the patterns found.

# Cleaning / Transformation: 

The setup for this project started by creating copies of the original sheets. Purpose here is so that I could explore and make changes without fearing of altering the originals. The original dataset would remain untouched on sheets labeled ACC Intakes and ACC Outtakes. The manipulated data exists on sheets Working Intakess and Working Outtakes. 
From here, the pivot tables used in the final deliverable exist on the Pivot sheet and the final deliverable is on the sheet labeled Dashboard. 

One of the first steps for cleaning was taking a look at the files as is. Commands in Power Query allowed me to see that the dataset came with a few duplicate values. These were first removed from the Working Intake and Working Outtake sheets. Next, the question became which of the existing rows would need reformatting. One of the things I had noticed was that since shelter dogs are often mutts, the combination of 3 or so different breeds be listed in the breed column was not uncommon. I had decided to use the Text to Column data tool to splite the original breed column into primary, secondary and tertiary breeds.

![Cleaned Intakes](https://github.com/Mchapa817/shelter_workbook/assets/124482275/fa94b87d-2610-4a89-9fb7-5d2ef6dd2c9b)

# Analyizing: 
The set as a whole contains animals from typical dogs and cats to a mix of wildlife. I decided to focus on trends in population over time to see what patterns could be found. One notable portion was a larger bat population than I would have originally guessed. This led me to research the native bat population in Austin and find that the increased numbers of bats coincided with the bats breeding seasons. 

Another notable trend is that the number of animals picked up goes up on average in the colder mounths. Additional reserach on this finding allowed me to discover that as the winter months bring in colder temperatures, members of the communitity are more likely to report strays. 

Finally, I had decided to examine the breakdown of sexes for the intake animals. The key here is that dogs/cats are often "fixed". The status of their sex can indicate if the animal has either been abandoned or lost. 

![Breed and Color Split Intake](https://github.com/Mchapa817/shelter_workbook/assets/124482275/dd4f4788-3611-4fec-a5d8-abae1f732228)

# Visualization and Final Recommendations

The visualizing steps focused on creating charts based off of Pivot tables. One is a pie chart showing the break down of intake sex status. The other is a timeline graph showing the intake count of the 5 most popular breeds. Both graphs are able to be manipulated by a splicer created off of the pivot tables. 

Final recommedations based on the trends would be to have staff increase training on how to handle "outlier" animals such as bats during their breeding season. Additionally, I would recommend the city of Austin expand on the increased sympothies of their community during the winter months by creating an ad campaign highlighting the increased number of pets lost/abandonded around that time of year. 
![Dash](https://github.com/Mchapa817/shelter_workbook/assets/124482275/8becbbbc-24ca-4d8f-9fa8-5285e302911a)

# References:
AaronSchlegel. (2018, February 16). Austin Animal Center Shelter Outcomes. Kaggle. https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-outcomes-and 

Caudill, M. (2019, November 20). Cold weather brings influx of animals to shelters. Mansfield News Journal. https://www.mansfieldnewsjournal.com/story/news/2019/11/20/cold-weather-brings-influx-animals-shelters-humane/4230836002/ 
