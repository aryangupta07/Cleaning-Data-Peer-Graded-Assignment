General info
You can read in the tidy data set tidy_data.txt into R via read.table("tidy.txt"). The so created object is a table with dimensions 181 x 81. The first column is the subject, i.e. the person who is using the device. The second column shows the activity. The residual columns show the accelerometer and gyroscope data. A list of these features can be found in the feature list.

How the data are transformed by the script:
The data are read in and simplified for processing
We define the wanted features, concentrating on standard deviations and means.
Only the data relevant for the standard deviations and means are read in to safe memory.
Perform steps 1-3 for the test and the training set.
Transform activity names into factors.
Reshape the data so that subjects and activities become a variables of two independent columns.
Finally safe the data.

How to use the script:
Download the data, unzip the folder and rename it to data for convenience under linux and unix.
Run the run_analysis.R script
The script creates a tidy data set saved as tidy_data.txt in your working directory.
