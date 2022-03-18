# UFO Analysis
Analysis of UFO sightings displayed on webpage searchable by 5 characteristics: Date, Location City, Location State, Location Country, Shape, and duration!

## Purpose
####
The purpose of this assignment is to create a dynamic webpage using Javascript to insert it into html, and then displaying our data on the web. We have learned how to build a table that neatly displays the UFO data we are working with. Filters have also been added which allow users to refine their search based on their use case. The table is then visually displayed by the html on the webpage. We also use bootstap, html and css to format the page, and enable dynamic content, which allows users to enter in new filters to update their search. The end product is a visually appealing and interactive UFO sighting search!

## Analysis
#### When using the webpage to filter for data, we are given the following options:
1. Date
2. City
3. State
4. Country
5. Shape
#### Learning how to use this table filtering application is simple! Follow the steps below to refine your UFO sighting search by Date, City, State, Country and Shape! You can use all 5 filters at once, but you can only use each filter for one selection at a time. For example, you can only search for one state, one city, one date, etc.  

1. Scan through the table that is already loaded to get an idea for the format the filters accept.
> <img width="1283" alt="Screen Shot 2022-03-18 at 11 28 42 AM" src="https://user-images.githubusercontent.com/95602006/159043443-38639620-dcab-449d-8125-ec00dc5886b6.png">
2. Select a filter you want to use first. We'll go with the "State" filter.
> <img width="851" alt="Screen Shot 2022-03-18 at 11 30 12 AM" src="https://user-images.githubusercontent.com/95602006/159043785-cdfac93f-ab9c-4b07-b554-06366cec0f1a.png">
3. Since we previewed the format, we know this filter shows the state as a 2 letter abrieviation that is lowercase. Let's type in "ca" and then click somewhere else on the screen for it to load.
> <img width="876" alt="Screen Shot 2022-03-18 at 11 31 46 AM" src="https://user-images.githubusercontent.com/95602006/159044043-627e9ed4-33f5-4605-95c7-918088e24440.png">
4. We now see all of the results for UFO sightings in "ca", California in this dataset.
> <img width="1179" alt="Screen Shot 2022-03-18 at 11 32 44 AM" src="https://user-images.githubusercontent.com/95602006/159044099-9eee5f20-9e2b-47c8-bf6d-1ac369bd96a8.png">
5. Let's use another filter to narrow our search down further. Keep the "ca" in the state, and type "san diego" into the "city" field.
> <img width="989" alt="Screen Shot 2022-03-18 at 11 33 53 AM" src="https://user-images.githubusercontent.com/95602006/159044329-1c09753f-15ea-46b0-bd1d-9db8ebb02675.png">
6. The filters return 3 results.
> <img width="1122" alt="Screen Shot 2022-03-18 at 11 34 33 AM" src="https://user-images.githubusercontent.com/95602006/159044398-36807124-0246-4c24-8d66-0daca586762a.png">
7. Give it a go and type in the date "1/6/2010" into the date filter field to show how 3 filters can be used at once.
> <img width="700" alt="Screen Shot 2022-03-18 at 11 38 10 AM" src="https://user-images.githubusercontent.com/95602006/159045047-908a5f4f-5c05-48eb-83c7-90341e9f5b88.png">
8. We now see that only one sighting matches the following filters: Date: 1/6/2010, City: san diego, State: ca
> <img width="1042" alt="Screen Shot 2022-03-18 at 11 39 27 AM" src="https://user-images.githubusercontent.com/95602006/159045438-d3b69499-8f73-4247-b9ab-64e9348f0c74.png">

> **Resources for the analysis are attached at the bottom 

#### 5 takeaways from analyzing the resources created from the data
1. The number of temperatures recorded is relatively equal for both months with December having 12 % less recordings to analyze than June. I would be concerned if it were greater than 20% difference because that would mean an unequal distribution of data between the months.
2. The mean for June is 75 degrees and the mean for December is 71. Those are a little more than 5% of eachother and without feeling what those temperatures there actually feel like, I cannot say that the difference is statistically significant, although 71 is getting pretty close to being "too cold", especially with any breeze present, to enjoy ice cream and surfing.
3. The top 75% of June is still more than 50% of December. I can see this by referencing the bottom quartile's numbers. June's bottom quartile is 73 degrees making the temperature at or greater than 73 degrees 75% of the time. The mean is 75 degrees.  December has a lower quartile of 69 degrees, and a mean of 71 degrees. June therefore has a hotter lower quartile than December, so 75% of the time June will be at or above 73 degrees, where as December will only be at or above 73 degrees maybe 30/40% of the month. This bodes well for June, but does not bode well for December.
4. The standard deviation supports our belief in June being the superior month. June has a lower standard deviation than December, meaning there is less likely to be a large variance in the temperature in June, where as its slightly more likely to have variance in December. 3.26 in June vs. 3.75 in December.
5. Therefore from the data, and from personal experience, we can conclude that June would have better weather more frequently than December would.

#### High Level Summary
* My conclusion is that June is the "superior" month during the year when compared to December. 
* The weather is warmer in June more frequently and more consitenly than it is in December as noted in the analysis points above. The frequency of temperature recordings is greatest around 75 degrees in June, and around 71 in December. We can also see from the descriptive stats that there is a greater chance of having a cold day in December, which would basically foreit all sales for that day. June does not have a good chance of that happening with the lowest low recorded as 64 with December's lowest low being 56.
* June is a good month to be open for Business, but December is risky.


#### 2 additional queries I would run to analyze more data for the analysis
    1. A query to analyze the precipitation data by date and by station.
    2. A query to analyze the distribution of the data by station, because location even on a small island could play a large role in this.

#### What would help complete this analysis?
* We need to know a little more about the data, when throughout the dat were these temperatures recorded? Is it the average of the whole day? Were there other factors that could have significantly contributed to the average that should be considered outliers? Current events like a hurricane?
* I would like to have criteria in analyzing, but because we have no context, we can only make an informed assumption at this point.
* I would want to see data for January and February to compare, if the reason for the analysis was "trying to compare the peak of summer to the pit of winter". Those to me would seem to be the 2 coldest months that I would want data on to determine if we could be open at all those 2 months. June is also not the hottest month in many places, with July or August taking that award.
* I would also want to see the precipitation data for the dates and also the time of day. We know that temperature follows the basic patter of peaking in the afternoon and bottoming out after midnight in most places around the world. Precipitation in my environment is seemingly random, but I do know that in certain climates around the world it also extremely consistent. Regardless of its assumed distribution, it could be a very helpful addition to this analysis.

___________________________________________________
##### Resources used in Analysis
<img width="527" alt="Screen Shot 2022-02-18 at 1 47 39 PM" src="https://user-images.githubusercontent.com/95602006/154751889-90b1bbde-e5d4-448f-9539-7271bed1512c.png"> <img width="167" alt="Screen Shot 2022-02-18 at 12 51 52 PM" src="https://user-images.githubusercontent.com/95602006/154751300-c84050f6-8359-4643-ac2f-a2a499cc33c6.png">

<img width="503" alt="Screen Shot 2022-02-18 at 1 50 16 PM" src="https://user-images.githubusercontent.com/95602006/154751948-3fca9e9c-ca7a-4a24-8883-4804fa21ac78.png"> <img width="163" alt="Screen Shot 2022-02-18 at 12 52 01 PM" src="https://user-images.githubusercontent.com/95602006/154751320-b648f302-37a6-4d33-b64d-c9cd2b65d12a.png">
