The `train_val.csv` file contains data from the [CAVES](https://arxiv.org/abs/2204.13746) dataset.
The file contains 9,921 tweets labelled with the concerns towards vaccines.

There are 3 columns in the file:
 - ID of the tweet in a string format, appended with a "t" to make it easier to work with on spreadsheet softwares.
 - The tweet text (Note: The tweet text column has not been revealed while uploading it to this public repository)
 - The different labels (vaccine concerns) expressed in the tweet, separated by spaces.

List of the 12 different vaccine concerns in the dataset:
 - [unnecessary]: The tweet indicates vaccines are unnecessary, or that alternate cures are better.
 - [mandatory]: Against mandatory vaccination — The tweet suggests that vaccines should not be made mandatory.
 - [pharma]: Against Big Pharma — The tweet indicates that the Big Pharmaceutical companies are just trying to earn money, or the tweet is against such companies in general because of their history.
 - [conspiracy]: Deeper Conspiracy — The tweet suggests some deeper conspiracy, and not just that the Big Pharma want to make money (e.g., vaccines are being used to track people, COVID is a hoax)
 - [political]: Political side of vaccines — The tweet expresses concerns that the governments / politicians are pushing their own agenda though the vaccines.
 - [country]: Country of origin — The tweet is against some vaccine because of the country where it was developed / manufactured
 - [rushed]: Untested / Rushed Process — The tweet expresses concerns that the vaccines have not been tested properly or that the published data is not accurate.
 - [ingredients]: Vaccine Ingredients / technology — The tweet expresses concerns about the ingredients present in the vaccines (eg. fetal cells, chemicals) or the technology used (e.g., mRNA vaccines can change your DNA)
 - [side-effect]: Side Effects / Deaths — The tweet expresses concerns about the side effects of the vaccines, including deaths caused.
 - [ineffective]: Vaccine is ineffective — The tweet expresses concerns that the vaccines are not effective enough and are useless.
 - [religious]: Religious Reasons — The tweet is against vaccines because of religious reasons
 - [none]: No specific reason stated in the tweet, or some reason other than the given ones.
