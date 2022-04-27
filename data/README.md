# Data Description
The two datasets I will be pulling from are `1990_2020_mercury_retrograde_dataset.csv` and `clean_report.csv`.

## Mood Data
I downloaded a CSV of the data from the Dailyo app. The app itself is relatively straightforward: you click one of the "moods" you create (mine included names like "meh", "not good but feel like it should be", etc) (which are inherently factors, even if the app doesn't make it seem like it at first glance!), select activities/traits that apply to your day, and write notes if you would like. 
For the sake of this report, I omitted the notes I had and created a `mood_scale` (that is a numerical representation of the factors (for ex, multiple moods had the equivalent of a 4/5 so I took this step for my own usability purposes). before uploading the csv file to GitHub.

The features of the dataset include:

* date | date format (yyyy/mm/dd)
* mood | character 
* activities | character
* mood scale | number

The Mercury in Retrograde data comes from [this Github Repo](https://github.com/Paris778/Retrograde-Mercury-Dates-Dataset-1990-2020).

Per the Repo:
"The present dataset consists of two features those being:

* DATE | date format (yyyy/mm/dd)
* isRetrograde | boolean (0 or 1)
isRetrograde has a value of 1 (one) when mercury was in retrograde during the respective date and 0 (zero) when it was following a normal course."

The original GitHub Repo also provided a photo of a graphical representation of one of the years (2018) of the data:
![](https://raw.githubusercontent.com/Paris778/Retrograde-Mercury-Dates-Dataset-1990-2020/main/screenshots/2018_mercury.png)