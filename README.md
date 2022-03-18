# UFO Analysis
Analysis of UFO sightings displayed on webpage searchable by 5 characteristics: Date, Location City, Location State, Location Country, Shape, and duration!

## Purpose
####
The purpose of this assignment is to create a dynamic webpage using Javascript to insert it into html, and then displaying our data on the web. We have learned how to build a table that neatly displays the UFO data we are working with. Filters have also been added which allow users to refine their search based on their use case. The table is then visually displayed by the html on the webpage. We also use bootstap, html and css to format the page, and enable dynamic content, which allows users to enter in new filters to update their search. The end product is a visually appealing and interactive UFO sighting search!

## Analysis and Results
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


## Summary
#### 1 drawback
1. The biggest drawback i've found is that the data set is not that extensive and the data within is strange. It's easy enough to get a preview by scrolling down on the table when the page auto loads. But because there are only like 100+ sightings, the ability to search is greatly limited because if you searched a random day, it has to be in 2010 and a sighting only happens on an average of every 3rd day.

#### 2 Recommendations to further develop this application
1. The application only can accept one argument in each filter at a time. While this application was developed to be able to search that way, it is sufficient for someone wanting to segment their data in such a way. But if someone else wanted to use the application and wanted to segment their data differently, ie: filtering for multiple states at a time because they could want to return all results for sightings on the west coast. This would be an extremely beneficial development.  
2. To build off of the development suggestion in my first example, the date filter field needs to be improved. The ability to only search for one day at a time is tricky considering it will not return many results. There are only like 100+ sightings in this dataset which means that only every 3rd day would have a sighting on average, making your ability to search specific days for results tricky.

#### High Level Summary
* My conclusion is that this application is excellent in the very simple way it delivers table results. The lack of functionality makes it easier to understand how to use. The use case for this would seem few and far between because of its lack of functionality, but is still an excellent start to displaying data in a table on a webpage!
