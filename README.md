# UFOs - UFO Sightings with JavaScript

# Overview of Project: 
On this module we explore Javascript to build a dynamic webpage that will accept user inputs and visually adjust to reflect the entries and interaction. Dynamic webpage were built by inserting JavaScript into an HTML page. On this module we also apply  our knowledge on CSS and Bootstrap and explore Chrome Devtools to test our codes.

### Resources:
  - JavaScript
  - CSS
  - HTML
  - Bootstrap
  - Chrome Devtools


# Results: 
To  provide a more in-depth analysis of UFO sightings and to  allow users to filter for multiple criteria at the same time, as a deliverable requirement for  client,  we were asked in addition to the data file, to add more table filters for the city, state, country, and shape as shown on the image screenshot below as default webpage. Each table element uses  the same id as object properties in the data.js file. The event listener is modified to detect changes to each filter  by creating functions that saves the element, value and data that was changed  and a table filter that will retun any data that matches the filter value. As a result, the webpage should update according to user inputs.

## Webpage default page 
![UFO webpage_screenshot](https://user-images.githubusercontent.com/92903447/150466807-fef9a560-baad-4ffc-ba58-af8c3b3213e4.png)

## Webpage result when "formation" for shape  is entered on filter box as a sample
![Filter screenshot  for shape formation](https://user-images.githubusercontent.com/92903447/150466837-53a20a7f-2319-42da-a3f9-7f16db0428ee.png)

## Webpage result when "nm" for state  is entered on filter box as a sample
![Filter screenshot by state](https://user-images.githubusercontent.com/92903447/150466925-00d293e4-e87b-470c-bcd7-26ce7dd82812.png)

## Webpage result when "el cajon" for state  and "light" for shape  is entered on filter box as a sample
![Filter screenshot for city and shape](https://user-images.githubusercontent.com/92903447/150470991-75f10044-b3e8-426e-9ae1-3e8874782124.png)

# Summary: 
## Drawback:
  1. When entering filter as an example for the "state" filter box, data requires a user input in lower case and no space at the end and should enter like how it was displayed and defaulted as a view data on the page.  Ex. filter will not return for "El cajon", "el cajon "search, but "el cajon". 

## Result using upper case sample
![Upper case Screenshot ](https://user-images.githubusercontent.com/92903447/150471015-eef89d18-8ca8-4fd6-a07e-6fec4a54044a.png)
## Result using lower case sample
![lower case Screenshot](https://user-images.githubusercontent.com/92903447/150471119-99194aee-240f-4c4b-803d-9a7a75524dc5.png)

## Recommendations: 
  1. I would suggest  to use a drop down selection for user to use so they don't have to guess how data filter should be entered.
  2. or allow the  user to input data for lower and upper cases and and trim to catch spaces.
