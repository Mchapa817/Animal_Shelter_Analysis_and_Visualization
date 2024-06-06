# Shelter Workbook
# Goal
My goal with this project is create a Dashboard that summarizes data from the Austin Animal Center

# Methodology
For this project, the mains stages were to Clean, Analyze, Visualize. 

Cleaning: 

The setup for this project started by creating additional sheets. The original dataset would remain untouched on sheets lavbel ACC Intakes and ACC Outtakes. The manipulated data exists on sheets Working Intakess and Working Outtakes. The pivot tables used in the final deliverable exist on the Pivot sheet and the final Deliverable is on the sheet labeled Dashboard. 

The dataset came with a few duplicate values. These were first removed from the Working Intake and Working Outtake sheets using the filter in filter system. 

![Cleaned Intakes](https://github.com/Mchapa817/shelter_workbook/assets/124482275/fa94b87d-2610-4a89-9fb7-5d2ef6dd2c9b)

Analyizing: 

Next, the question became which of the existing rows would need reformatting. Since this data set lacked any business related context, I decided to just look for trends in population. The set as a whole contains animals from dogs to cats to a mix of wildlife. For the analysis I decided to focus on filtering based off of breed and intake sexes. Since, shelter dogs are often mutts, the combination of 3 or so different breeds be listed in the breed column was not uncommon. For our graphing purpose later, the filtering required new columns to be created. This was done by using the Text to Column data tool to splite the original breed column into primary, secondary and tertiary breeds. 

Image

Visualizing:

The visualizing steps focused on creating 2 charts. One of which is a pie chart showing the break down of intake sec status. The other is a timeline graph showing the intake count of the 5 most popular breeds. Both graphs are able to be manipulated by a splicer created off of the pivot tables. 
text. 

# Deliverables:
Final Dashboard: 

# Issues / Credits:
Dataset was gathered from Kaggle. All sheets were created using Excel.
