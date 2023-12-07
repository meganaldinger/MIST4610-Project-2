
# MIST4610 Project 2



## Team Members

1. Megan Aldinger [@meganaldinger](https://github.com/meganaldinger)
## Dataset Description

This dataset captures incidents of crime within the City of Los Angeles, spanning from the year 2020 onwards. It was found from the Data.gov database catalog. It contains 853,000 rows, each representing a crime incident. There are 28 columns that describe various information about each crime. “DR_NO” (string) is the official file code from the LAPD which is unique to each case. There is also a series of columns for additional crime codes to attach any additional, less serious crimes within a single case. “Date Occurred” (date) and “Time Occurred” (time) provide information about the time of the crime. “Area Name” (string) contains the 21 neighborhoods within Los Angeles; additionally, there is more specific geographic data containing the category of premise (string) and a street address represented by “Location.” There is also latitude (int) and longitude (int). The dataset also contains information about the victim of each crime, including their age (int), sex (string), and descent (string). Finally, there is information about weapons used–if applicable–which is represented by a weapon code (string) and description (string). 

[Link to dataset](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)


## Question 1
#### Question 1:
How has the number of pickpocketing crimes changed from 2020 to 2023, and how is this change reflected in areas highly populated by tourism?  


#### Importance:
This question demonstrates the impact of a global pandemic on crime, specifically pickpocketing–which is highly driven by global tourism to Los Angeles. In tracking the pitpocketing by year, the data also represents the end of global lockdown. It might also help the Los Angeles police department to track whether or not their pickpocketing mitigation efforts have had an effect on the actual number of crimes either increasing or decreasing. Finally, adding an additional element of location to the question would allow the Los Angeles police to track which areas are most prone to the crime of pickpocketing, and therefore give them insight on where to station more officers or focus on awareness efforts. 

<img width="1439" alt="Screenshot 2023-12-07 at 12 14 54 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/3c5fedfd-d4d2-475a-910b-0085b8e26881">

<img width="1436" alt="Screenshot 2023-12-07 at 12 16 03 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/a9a2b662-a58f-49d8-b1a3-1c715e699054">

## Manupulations applied to the data set for analysis
I first created a density map of the pickpocketing crimes over the entire city of Los Angeles to identify the most and least dense pickpocketing areas to use in my selection. Then I created the previous bar chart by filtering the crime description to only include pickpocketing. I also filtered the area names by Hollywood, a highly tourist neighborhood, Central LA, a moderate tourist neighborhood, and West LA, a more residential reference group.

#### Analysis:
In analyzing the bar graph, we see that West LA–a more residential area of the city–had a very similar number of pickpocketing crimes as Hollywood during the height of the pandemic in 2020. Over the next three years, there is a skyrocketing in pickpocketing across all areas, likely due to more people leaving their homes and returning to normal life. However, Hollywood and Central LA hold a much higher proportion of pickpocketing crimes, showing their influence as highly populated areas that rely more on tourism. In the year 2022, there were almost 11x as many pickpocketing crimes in Hollywood compared to West LA. The data slightly dips in 2023, suggesting that the number of pickpockets may have leveled off to return to normal and will not keep increasing. 


## Question 2
#### Question 2:
What type of retail establishment in Los Angeles experiences the most shoplifting? For the establishment with the most shoplifting, what demographic (age and sex) is most likely to shoplift? 

<img width="1439" alt="Screenshot 2023-12-07 at 12 57 38 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/c69d1b2a-32a3-4b69-b66f-4bebc7ee66d9">
<img width="1440" alt="Screenshot 2023-12-07 at 1 30 53 AM" src="https://github.com/meganaldinger/MIST4610-Project-2/assets/141375048/11ea421b-09ca-4713-bddf-f739c51dec5b">


#### Importance:
Shoplifting is a large problem for retail stores, which leads them to invest in loss prevention efforts such as security cameras and other methods. This data would be valuable for large retail corporations to understand which stores are most highly targeted by shoplifters. This would be helpful for both corporations and the LAPD to distribute their resources accurately to combat shoplifting. Additionally, by understanding the demographics of shoplifters, retailers can better anticipate which items are more likely to be targeted. This information can influence inventory management decisions, helping businesses protect high-risk products. Law enforcement and retailers may collaborate to address shoplifting concerns. Understanding the demographics of shoplifters can contribute to community engagement efforts, such as educational programs or outreach initiatives aimed at reducing theft.

#### Manupulations applied to the data set for analysis:
This line graph gives an overall look at a year’s worth of shoplifting cases refined by the type of retail business. I filtered the data by premises and excluded any that were not a retail establishment. I also filtered out all crimes except “Shoplifting - Petty Theft” and “Shoplifting - Grand Theft”. To create the demographic chart, I kept the same filters, but also added both sex and age, with filters to remove irrelevant data. For example, before I filtered the ages, there was a large spike for both genders at 0, which does not make logical sense in the question, so they were removed. 

#### Analysis:

This graph demonstrates that by far the most likely establishment to be shoplifted from is a department store. Second is a clothing store, and third is a drug store. However, the large gap between department stores and all other retail stores suggests that there might be a specific flaw in the department stores’ loss prevention efforts. When looking at the demographic chart, males are seen to be far more likely than females to shoplift. Additionally, both for men and women, adults aged 20-35 are the most likely culprits. There is a very large spike for male shoplifters around age 35, suggesting this is the most likely demographic to shoplift from a department store. This is helpful to know because I think stereotypically society views women as more likely to shoplift or commit petty theft crimes. When analyzing raw data, we can look past stereotypes and get a good understanding of a specific crime to create an effective plan to mitigate it. 

## Tableau packaged workbook

