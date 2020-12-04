# BestNeighborhood
## group name
    Apples
## Members
Dastan Abdulla
email: dta12@pitt.edu </br>
Anna Speciale
email: ams692@pitt.edu </br>
Lucas Milavec
email: lrm88@pitt.edu </br>
## Description/ Preanalysis and Links to the datasets used
### public safety dataset description
The data set chosen below includes information related to the number of police reports and the percentage of those reports that were considered serious crimes such as rape and murder. There are two columns which are not needed for this project and they are the crime per 100 columns. The reason why they are not needed is because that is abstracted away from the concrete data already by the composers of the dataset and we want to create our own analysis. public safety is significant for the quality of neighborhood because it determines peace of mind for the people and their comfort level.
### education income dataset description
In my personal notebook I am attempting to figure out how Education can help define the "best" neighborhood in Pittsburgh. This data set has a column of neighborhood names and other columns consist of pupulation and percentages of people with certain levels of education attainment. These attainments include: less than high school, high school graduate, assoc./prof. degree, bachelor's degree, and postgraduate degree. educational statistics are significant because it determines the overall class of the neighborhood, which is in direct correlation to the quality of buildings and peoples satisfaction.
### zoning dataset description
The zoning dataset includes information about the types of industries and buildings in the neighborhood. This information is important because it can tell us the degree of air pollution and other environemntal aspects. It can also give us hints regarding the pricing for houses. A more luxurious neighborhood would cost more even with lesser quality houses due to the degree of safety in those neighborhood and reputation.
### links to data
Public Safety: https://data.wprdc.org/dataset/pgh/resource/204f63f4-296f-4f1d-bbdd-946b183fa5a0 </br>
Education Income: https://data.wprdc.org/dataset/pgh/resource/f7b19c6c-aa66-419b-b0e1-9998d7ddfcbc </br>
Land use zoning: https://data.wprdc.org/dataset/pgh/resource/c2cd7415-b401-4857-8ca5-58ce2ec17c5d </br>
## Metrics
### public safety: <br/>
I created an Neighborhood class that had a scoring method. The method took into account murder rate, rape, drug violations, auto theft, burglary, robberies, and aggrevated assault. I then divided the total account of those crimes by the population of the neighborhood to determine a fixed scale for comparison to be able to deduce the best neighborhood in this category.
### land zoning: <br/>
generate a score by averaging percent area of residential, industrial, commercial, and institutional area. This is based on the assumption that the optimal neighborhood would have a balanced array of zoning.
### education: <br>
focused on postgraduate degree. Determined the percentage of people who attained a post graduate degree and compared each neighborhood using this scale to determine the overall success of the neighborhood.
## Conclusions:
### Dastan Abdulla's Conclusion (public-safety)
After a thorough analysis of the given data, we can conclude that the safest neighborhood is Fairywood. However, the rest of the neighborhoods are incredibly close, except for West End, South Shore, and Chateau. The methodology used in the analysis considers various factors such as murder, rape, robbery, drug use, assaults, and auto theft. I divided the total of the crimes by the neighborhood population to calculate a relative percentage of overall crime. 
### Anna Speciale's Conclusion (education-income)
For the sake of simplicity in the end I decide to focus on the percentage of the populations that attained postgraduate degrees. By this logic the highest percentage of people with a postgraduate degree, the highest form of education in this data set, would be considered the "best" neighborhood. The data set shows that South Shore has the highest percentage at 47.6% or .476. I am not from Pittsburgh so I don't think I have a personal favorite neighborhood. I can't really speak on whether or not these data sets align properly with how good the neighborhoods are since I haven't spent time in most of them.
### Lucas Milavec's Conclusion (zoning)
We can see that Knoxville, Friendship, and East Hills  are the top 3 highest scoring neighborhoods from my analysis. This seems to be consistent with what you would expect from such an analysis because they are relatively well off neighborhoods fairly far from the downtown area. This allows theses neighborhoods to have the balance their use of space and provides residents with a better living condition. However, I am not personally very familiar with all the neighborhoods of Pittsburgh so it is difficult for me to truly evaluate the quality of my analysis.
### Final Conclusion
Overall, the best neighborhood, the relative intersection between the three data sets, is Regent Square. Regent Square has an education attainment rate of 44%, which is the second-highest in Anna's dataset. It also has a 1.18% crime rate according to the metric used in Dastan Abdulla's data set. While Regent Square doesn't have the lowest crime rate, many neighborhoods have a small margin of less than 2% crime rate in the public safety dataset, which renders the margin irrelevant in the overall scope.

## Abstract: 
In this project, we analyze neighborhoods in the pittsburgh region and determine the best neighborhood. We use three data sets in order to achieve this task. The Public Safety dataset provides information such as crime rate, police reports, and murders for various areas. The education dataset provides information about the education level and income for the people in the neighborhoods. The land zoning data set provided information regarding zoning and types of property in those regions. We determined that Regent Square was the best neighborhood according to our individual scales. All three of us used similar comparative metrics that scored each neighborhood by crime(rape, murder, assault, robbery, auto theft, drugs, and burglary), zoning (residential, industrial, commercial, and institutional area), and education level (post graduate).
