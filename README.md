
# MIST4610 Project 2



## Team Members

1. Megan Aldinger [@meganaldinger](https://github.com/meganaldinger)
## Dataset Description

This dataset captures incidents of crime within the City of Los Angeles, spanning from the year 2020 onwards. It was found from the Data.gov database catalog. It contains 853,000 rows, each representing a crime incident. There are 28 columns that describe various information about each crime. “DR_NO” (string) is the official file code from the LAPD which is unique to each case. There is also a series of columns for additional crime codes to attach any additional, less serious crimes within a single case. “Date Occurred” (date) and “Time Occurred” (time) provide information about the time of the crime. “Area Name” (string) contains the 21 neighborhoods within Los Angeles; additionally, there is more specific geographic data containing the category of premise (string) and a street address represented by “Location.” There is also latitude (int) and longitude (int). The dataset also contains information about the victim of each crime, including their age (int), sex (string), and descent (string). Finally, there is information about weapons used–if applicable–which is represented by a weapon code (string) and description (string). 

[Link to dataset](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)


## Question 1
#### Question 1:
How has the number of pickpocketing crimes changed from 2020 to 2023, and how is this change reflected in areas highly populated by tourism?  

This question demonstrates the impact of a global pandemic on crime, specifically pickpocketing–which is highly driven by global tourism to Los Angeles. In tracking the pitpocketing by year, the data also represents the end of global lockdown. It might also help the Los Angeles police department to track whether or not their pickpocketing mitigation efforts have had an effect on the actual number of crimes either increasing or decreasing. Finally, adding an additional element of location to the question would allow the Los Angeles police to track which areas are most prone to the crime of pickpocketing, and therefore give them insight on where to station more officers or focus on awareness efforts. 

<img width="1439" alt="Screenshot 2023-12-07 at 12 14 54 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/3c5fedfd-d4d2-475a-910b-0085b8e26881">

#### Analysis:
In analyzing the bar graph, we see that West LA–a more residential area of the city–had a very similar number of pickpocketing crimes as Hollywood during the height of the pandemic in 2020. Over the next three years, there is a skyrocketing in pickpocketing across all areas, likely due to more people leaving their homes and returning to normal life. However, Hollywood and Central LA hold a much higher proportion of pickpocketing crimes, showing their influence as highly populated areas that rely more on tourism. In the year 2022, there were almost 11x as many pickpocketing crimes in Hollywood compared to West LA. The data slightly dips in 2023, suggesting that the number of pickpockets may have leveled off to return to normal and will not keep increasing. 

<img width="1436" alt="Screenshot 2023-12-07 at 12 16 03 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/a9a2b662-a58f-49d8-b1a3-1c715e699054">
I first created a density map of the pickpocketing crimes over the entire city of Los Angeles to identify the most and least dense pickpocketing areas to use in my selection. Then I created the previous bar chart by filtering the crime description to only include pickpocketing. I also filtered the area names by Hollywood, a highly tourist neighborhood, Central LA, a moderate tourist neighborhood, and West LA, a more residential reference group. 

