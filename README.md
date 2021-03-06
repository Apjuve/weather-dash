# Welcome to my Weather Dash

#### This is a web application designed using HTML, CSS, JS, Bootstrap, and the Open Weather Map API allowing users to search for the weather in a specific city, and see the current weather and a the 5 day forecast.

## Link to Deployed Site

[Weather Dash] (https://apjuve.github.io/weather-dash/)

## Table of Contents
  * [Motivation](#motivation)
  * [Technologies](#technologies)
  * [Functionality](#functionality)
  * [File Architecture](#file-architecture)
  * [Usage](#usage)

## Motivation

![Weather-Dash](https://user-images.githubusercontent.com/95586383/163905604-5fe8b4da-3119-4bd3-8d38-fbb8a3932f97.gif)


A simple weather app that allows users to input a city and see the current and future weather. 
The app uses the Open Weather Map API to get the weather information, and it is rendered on the page using JavaScript. 
The app also allows users to see their previous searches by rendering them in a list below the search bar. When a user clicks on a previous search, they are taken back to the weather information for that city. Users can also click to clear the search history!


#### Technologies
* HTML
* CSS 
* JavaScript
* Bootstrap
* Open Weather Map API



## Functionality



#### The demo shows the main functions of the Weather Dashboard:
* Users search for weather by typing in the name of a city.
* The app makes a call to the open weather API and returns the current weather in the searched city, and a 5 day forecast.  
* Searches are saved in local storage and displayed on the page under the search bar. 
* When a user clicks on a previous search, they given the accurate weather for that city.


## File Architecture

```
├── README.md
├── assets
│   ├── images
│   │   └── hanging-plant.jpg
│   ├── scripts
│   │   └── script.js
│   └── styles
│       └── style.css
└── index.html
```

## Usage
* Find the current weather of a chosen city. 
* Use this to help understand how to make API calls.

## Future Development
* Use geolocation to show the weather information for the users current location upon page load. 







