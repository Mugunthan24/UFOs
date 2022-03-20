# UFOs
 JavaScript, Bootstrap, and UFOs

## Overview of Project
A website was created using HTML and JavaScript. On the website there is a table with information on various UFO sitings that were reported in January of 2010. Users can filter this table to find what they are looking for.

## Results

Unfiltered Table
![image_name](https://github.com/Mugunthan24/UFOs/blob/main/static/images/Unfiltered%20Table.png)

Filtered Table - Country
![image_name](https://github.com/Mugunthan24/UFOs/blob/main/static/images/Filtered%20Table%20-%20Country.png)

Filtered Table - Country and Date
![image_name](https://github.com/Mugunthan24/UFOs/blob/main/static/images/Filtered%20Table%20-%20Country%20and%20Date.png)

A user of the webpage may be interested in viewing reported UFO sitings in their city or country. By default, when the webpage first loads, the table is unfiltered and contains many entries. If a user is from Canada, and is interested in seeing the reported siting in his/her country then they can enter "ca" in the Country filter and see the UFO sitings reported in Canada. Additionally, with the use of multiple filters, they may want to also filter for a specific day in addition to filtering for Canada. Incorporating the ability to filter multiple columns in the table, greatly empowers the user.

## Summary
In the subsequent sections below, we will be discussing the drawbacks and potential recommendations for further developement.

### Drawbacks
One drawback to the new design of the website is that there is no error handling. For example, if in the Date filter someone were to enter a city name by accident beleiving it to be the City filter, the results in the table would be blank, leading them to potentially believe that there were no UFO sitings for that city in the table.

### Recommendations
The first recommendation would be to include error handling. Using the example explained in the previous section if a user were to enter a city name in the Date filter beleiving it to be the City Filter, they would be lead to believe that there were no UFO sitings for that city in the table when there potentially was. With error handling, the user would be notified that their entry in the Date filter was invalid because it was not a date. If error handling was incorporated into all the filters, then the users would be able to know if they entered something invalid improving the user experience.

The second recommendation would be to have the values in the City, State, County, and Shape columns be written in proper case. This will make the table and site look much more professional.

Lastly, it would be beneficial for the user if some of the filters were dropdowns. If the City, State, and Country filters were dropdowns that adapt and update their options based on previous selections. Some users may not know exactly how to spell a cities name so having the dropdown option would be useful. Additionally, if the dropdown options for a field update based on a previous dropdown selection, then this would significantly enhance the user experience. For example, if in the Country filter Canada was selected, then the City and State columns should update to only have cities, and states (provinces and territories) in Canada. 

In addition to the City, State, and Country filters being dropdowns, a dropdown calendar can be added to the Date field. Users may enter a date in the wrong format and having a dropdown calendar option for this field will combat this problem.