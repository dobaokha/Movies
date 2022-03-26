# Movies
This project is for my ISM 3011 class at USF. I have to pick a dataset and do some analyis with Excel. However, the dataset is not tidy so I cleaned it using R. The dataset can be found here: https://www.kaggle.com/datasets/danielgrijalvas/movies

# Tidy with R
- Dropped duplicate movies' names. I shouldn't have done that but I haven't understood the reason for the duplicate in names specifically. Other columns in those duplicate movies' name are different such as the "released" variable. For the class assignment, I dropped it but for future analysis, I will dig deeper into the dataset to find a better way of tidying the dataset.
- Separated "released" columns to "month_released", "day_released", "year_released", "country_released"
- Changed the data type of the columns released_day and released_year from character to double.
- Added a surrogate key as the Id of the movie because there is no explicit unique ID in the original dataset.
- Exported the dataset to an Excel file for further analysis for the ISM 3011 DKB_3EX.xlsx assignment.
- Renamed all the columns by capitalizing the first letter.
