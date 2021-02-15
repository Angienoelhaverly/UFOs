# UFOs

## Project Overview
JavaScript is a well-established coding language designed to improve webpages by enhancing the user experience. Javascript enhances websites by providing front-end functionality, customization, dashboards (such as maps or graphs), and allows for user input to create dynamic web pages. Javascript enables websites to be visually appealing and interactive. 

In this repository, we will use Javascript to create a table that organizes UFO data that is stored as a JavaScript array, or list. This table will have the ability to filter data based on certain criteria and will be created using JavaScript as the primary coding language.

### Coding Goals
* Build and deploy JavaScript functions, including built-in functions.
* Convert JavaScript functions to arrow functions.
* Build and deploy forEach (JavaScript for loop).
* Create, populate, and dynamically filter a table using JavaScript and HTML (convert a Javascript array into an HTML Table)

### Project Deliverables
* Deliverable 1: Filter UFO sightings on multiple criteria
* Deliverable 2: A written report on the UFO analysis (README.md)

## Results
The webpage created is a fairly user-friendly display of ufo sighting data with a filter table that allows users to easily filter on various criteria such as date, city, state, and shape of the UFO sighting. The displayed results are dynamically filtered as you update the form field entries. There is no needed Submit or Refresh button as the tables update in real time. Filter selection can be broad such as only selecting a country like the United States, or can be as narrow as specifying the date, choosing one city in one state and focusing on one type of shape such as "light". 

![filters](https://user-images.githubusercontent.com/73972332/107899363-e949c900-6ef2-11eb-9e0f-a0602c608d68.png)

## Summary
Our current webpage has one main advantage in that users can search upon multiple criteria at one time and there is no submit button needed. However, there are also some drawbacks. 

*Drawbacks*
* The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly. For example, if the user entered a city as "Ventura" instead of "ventura", the city would not return in the filtered data. 
* The user may not know exactly what period the data is from, so the user might type in dates that we don't have data for. For the date filter, the user should be able to click through a calendar. 
* Without knowing exactly what the existing options are for the Shape field, it's hard to effectively search using that filter. 

*Recommendations for further development:*
* A drop down menu for the shape option as it would be hard for users to guess this on their own. This would be more user friendly as a drop down option than a user input of text. 
* Also the text in the Comments section needs to be cleaned up as there are strange encoding artifacts that show up. These should be eliminated to make reading the comments more user-friendly. 
