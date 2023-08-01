The `test.csv` file contains the test data for evaluation.
The file contains 486 tweets labelled with the concerns towards vaccines.

There are 2 columns in the file:
 - ID of the tweet in a string format, appended with a "t" (to make it easier to work with on spreadsheet softwares).
 - The tweet text


To submit your runs, please prepare a similar CSV file with the ID column, and a column for the predictions. Each of your predictions will be a space-separated list of classes. Thus the file will look like:

"id", "preds"

xxxxxx1t, none

xxxxxx2t, rushed ineffective

xxxxxx2t, side-effect ineffective mandatory
...

NOTE: Make sure the IDs are exactly the same as in the test.csv file.
