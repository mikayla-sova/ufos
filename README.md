# ufos

## Project Overview
Using Javascript to add more filters to the UFO Sighting webpage to allow for multiple criteria searched at one time. We learned how to adjust filters and change tables based on those adjustments. Customizations like this allow for the user of the webpage to enter search criteria and interact with data. In addition, HTML, Bootstrap, and CSS knowledge helped design the webpage interface.

## Results 
Creating the webpage resulted in this home page:

![webpage_home](/images/webpage_home.png)

To the left of the screen, we can see the search bars that will allow the webpage user to input the search parameters that they are interested in. In this case, we will use the example of searching by triangles in which we will type "triangle" into the search parameter box.

![filter_shape](/images/filter_shape.png)

In addition, we can also search by city, which is exampled in this next image:

![filter_city](/images/filter_city.png)

These search parameters can be used with just one, such as one city, or multiple at once, such as a city, state, and shape. As we can see, inserting search parameters helps narrow down the data based on whichever parameter was entered. When the site is originally viewed, there is a lot of information one can scroll through. However, after using a search parameter, the table is narrowed down. 

## Summary
One drawback of this design is that the search parameters are case-sensitive and thus must be entered exactly as shown on the table or the function will not work. Here is an example of searching for "Benton" instead of "benton". Remember that in the home page before, "benton" was a data point that was shown. 

![drawback_example](/images/drawback_example.png)

I would recommend that, for further development, it could be helpful to have the search parameters be flexible enough to contain capitalization. Or, for there to be a pop up message for users that will show the way they must insert their parameters before searching, in the event that the user might search for something and get confused as to why there's no data popping up. In addition, I would broaden the amount of data available for this webpage since there's now an efficient tool to sort through large amounts of data. 