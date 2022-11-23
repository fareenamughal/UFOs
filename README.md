
# UFOs Analysis using JavaScript, HTML and Bootstrap 
[Module 12]
___

## Overview of Project 
___

Dana's webpage and dynamic table aims to provide an interactive analysis for users that would provide them with information about UFO sightings based on the criteria they input. In the previous practice exercise we used one selection criteria to filter the data. In this project we will add multiple filter criteria, thereby allowing users to see only what they are interested in. To be specific, in addition to the date filter, city, state, country and shape will also be used to filter throught the UFO sighting database.


### Link to access the webpage: 
---

        file:///Users/fareenamughal/Desktop/BOOTCAMP%2020220822/UFOs/index.html

___

### Resources 
___

  1. JavaScript, HTML, Boostrap, Visual Stiudo Code
  2. Bootstrap CSS Library
  3. Data source: https://github.com/fareenamughal/UFOs/blob/9da6ba778849718ece1e79797163a836a7bb9b02/static/js/app.js    
  4. Challenge starter code: https://github.com/fareenamughal/UFOs/blob/9da6ba778849718ece1e79797163a836a7bb9b02/static/js/ufo_starterCode.js
  5. Image source: https://github.com/fareenamughal/UFOs/blob/4176d01ef404aadb2b1f1f1f8ad9ce5aa09955e9/static/images/nasa.jpg
  6. HTML file creating the webpage: https://github.com/fareenamughal/UFOs/blob/9da6ba778849718ece1e79797163a836a7bb9b02/index.html

___

### Results
___


The webpage is divided into two sections:
  - The static section of the webpage
  - The dynamic section of the webpage

  1. The static section of the webpage contains information - text, images, data etc that does not change. 
Users cannot make changes to this section. The webpage developer or owner would be able to change this section via the Bootstrap CSS library which would formt according to the selected CSS library, image file based on the preferred image and text based on the specific text that for the website.
  
      ![Static](https://github.com/fareenamughal/UFOs/blob/main/static/images/Static%20section%20of%20webpage.png)
  
  2. The dynamic section of the webpage contains information which changes as per user selection. 
  In this case the dynamic section contains the various filters which refer to columns in the data table. A user can search the data based on the following criteria:
  ---Date - denotes the date that the user would like to drill down thier search for
  ---City - this is to select the specific city of interest
  ---State - enables a user to select the one specific state
  ---Country - this data contains information for only one country, US. If the data contained information about more countries then users would be able to select a specific country and observe results for the selected counrty 
  ---shape - this enables the users to select the type of shape for instance triangle - of the UFO sightings.
      
      ![Dynamic](https://github.com/fareenamughal/UFOs/blob/main/static/images/Dynamic%20section%20of%20the%20webpage.png)

     To use the webpage the user would need to select the specific information they require by inputting the details in the text box under the search section.
      ![Search](https://github.com/fareenamughal/UFOs/blob/e115b7613efde2006998951b5dadeede41e3c32a/static/images/Search%20tab.png)


For instance a user may input a specific date to filter the data to only reflect information about that specific date e.g. 1/10/2010.
They could also search for specific a city e.g. benton, or state e.g. ca or country e.g. us or shape e.g. round. This selection would be done by typing in the specific criteria in text boxes on the left hand column. One selection or a combination of criteria can be used and by inputting and clicking enter on the keyboard the data will be filtered out to reflect only items selected.

___

### Summary
___

A drawdown of this design is that the selection criteria or search does not allow for a range of items to be selected. For instance a user cannot select the data for one or more months or one or more weeks. 

One recommendation would be to code the webpage so as to allow the search engine to select a range as this would be helpful. A user could also just want to filter data for only two cities or 5 cities for that matter in addition to the date or specific month or months.
![Date](https://github.com/fareenamughal/UFOs/blob/49684aec0893a599e84e22b1f6d9f655beee855d/static/images/Date.png)
As per the image above it is clear that a user cannot select a specific month. When January is selected the search result does not generate any data which is incorrect as the verified by other images in this report.


Another recommendation would be to allow the search or filter function to allow for upper and lower casses as opposed to just lower case. 
![city-case](https://github.com/fareenamughal/UFOs/blob/83b62daa9e95f6eaa4fb7c7e307820b639fde9ab/static/images/city-case.png)
As per this image, it is clear when inputting the same city information by using an upper case the search doesn't generate any results whilst we know for certian if the same is input in lower case there is data that is filtered out. 



