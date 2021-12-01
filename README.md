# UFOs
## Overview

A web application has been developped to filter data that contains sightings of UFOs all over the United States. This excercise has been performed using Javascript to perform the analysis and HTML along with Bootstrap3 to build the website and visualize the filtering.



## Results

To use the webpage the user only has to write in the boxes whatever criteria they require. Once they do that "event listeners" programmed within javascript will take the information within the box using D3 and filter the tables based on what is written. An example is shown in the following progression of images.


![No filters](/screen_shots/nof.png)

On the image above no filters are applied, so all of the data is displayed.


![One filter](/screen_shots/1f.png)

On the second image one filter has been applied: the state of Florida, written as "fl". Doing this we can observe every row that contains info from Florida, and since no other filter is applied the information displayed is not limited by any other column.

![Two filters](/screen_shots/2f.png)

Finally, a second filter is applied in the field "Shape". The page now displays rows based on both filters but still won't restrict the rest of the columns.



## Summary

Two recommendations for further development: One is to experiment with other event listeners, using buttons or drop-down lists could be a welcome feature for certain users. A second one is the modification of the overall design; the positioting of the text boxes is very akward in relation to the rest of the page, and the color schemes along with the styling could be more professional.
