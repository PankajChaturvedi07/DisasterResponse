*****************process_data***********
Read both csv files
Merged the two files
Data cleaning and preparation (Splitting categories column into 36 columns and removing text before 0 and 1)
Saving data into sql database
**************train_classifier************
Import required libraries
load sql data
tockenize the data
create ML pipeline
model evaluation
Improving model using GridsearchCV
evaluate model performance
Save model using pickle
***************Run.py******************
Update database, model path in template
add relevant visulatizations
