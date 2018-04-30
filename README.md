# Weather Application

## Background/Context

* This project is a weather application that fetches data from a public weather api, based on the location (city and country).

* This application was created to gain a better understanding of fetching data, using functions/methods to manipulate the data, and then display the specific data desired to the screen.

* Another goal of this application is to further understand the idea of creating reusable components that can be exported/imported to other files. Each component will have its own logic, can be reused in other areas of the project, and controls its own rendering. These reusable components make apps easier to develop and maintain.

* I have written classes and functions for each component to gain a better understanding of the different features offered, such as the way props are used in each scenario.

* Technology used: HTML, CSS, ReactJS

## Instructions

* This project was bootstrapped with Create React App.

* Npm start is used to run the application. This should take you to http://localhost:3000/.

* Once you type in a city/country and click the button, data will be displayed for Location, Temperature, Humidity, and Description.

* If there is an error when using npm start, a deployed version of this application can also be used: https://young-bayou-34108.herokuapp.com/

## Errors/Glitches

* The API from openweathermap is not the current daily weather. It is static so in order to make this a live weather app, it would be necessary to find a new API/API Key that offers real-time weather data.

* Deploying App to Heroku: The Node App would fail to build because of having both the yarn-lock and package.json-lock. By removing the lock that was not used to install most dependencies, the app will then successfully deploy.
