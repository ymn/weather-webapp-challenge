# Weather-Web-App Challenge

The purpose of this challenge is to show that your basic Javascript and general programming knowledge are sufficient enough for our intern program and that you are ready to spend time to research, learn and implement. We would like to see that you are motivated to become a part of our team and start the learning process with us. Since we do care about the time and effort you spend to show us your motivation, all participants will be rewarded with 500 Turkish Lira if the task is completed with all requirements even if you do not get to join our team at the end.

**Task:** Implement a basic weather web app using Javascript, Ajax, CSS and HTML. (See Mockups Here)

[![Watch Video](https://gitlab.vpn1.com/onur/weather-webapp-assignment/raw/master/mockups/nail.png)](https://www.youtube.com/watch?v=JxrJB10kuj4)

### The Weather app should have following features:
- Ability to add unlimited cities by their name to a list, this list can be kept in a simple array or object. Example cities: Miami, London, Berlin, Frankfurt, Istanbul, Ankara
- When user enters the name of the city and it cannot be found, show an error that the city can not be found
- Ability to remove the city from list
- Ability to search and shortlist the list of the added cities by matching term using search box

### Implementation
You will be using the Rest-API of https://openweathermap.org/ to the get the weather data
for a city the user enters. You will be using the “Current weather data”. This API is able to query current weather by different properties like ZIP, Coordinate or Name of the city. You will be using the Name of the city as the query property.

Please read following pages to get an idea how openweathermap API works:

##### **[How to get started with OpenWeatherMap?](https://openweathermap.org/appid)**
##### **[How to use the current weather data API?](https://openweathermap.org/current)**
--
Example query could look like this:

https://samples.openweathermap.org/data/2.5/weather?q=London,uk&appid=b6907d289e10d714a6e88b30761fae22

You will need to replace the app ID by your registered app id (API Key) and the query by the city the user enters in the input field.

- When user enters a city name to the input field “Add new City” and clicks on Add, the app will do a Ajax request with the name of the city to openweathermap API and get the data.
- You will display the data just like shown in the mockups
- The user can delete a added city by click on the trash can (you can use any icon you want here or a basic X)

### Development
- You are free to use common frameworks like jQuery if that makes your task easier or just use plain javascript if you like.
- You must to use Flexbox for layout
- You must use the BEM Method for CSS
- For Ajax you can use jQuery.getJSON() or plain javascript XHR.

### Result
Upload your complete project to your Github Account and send us the link

### What’s next?
- We will evaluate your results and compare it with other candidates results. (Every successful submission will receive 500 TRY compensation regardless of whether you join our team or not).
- 1 or more candidates will have the chance to join our team after this final challenge.


### What will you do as a javascript developer in learning phase?
- You will join our team and will be working remotely for now
- You will learn to use frameworks/technologies such as React, NodeJs, Gulp and Webpack.
- We will provide you with online courses (https://www.udemy.com/), small projects and assist you with learning these technologies.
- You will have weekly and monthly targets provided by us.
- We will expect 8h of online availability (Monday - Friday)
- You will be earning 2000 Turkish lira/monthly while in the learning phase
- When your learning phase is finished you are able to implement a project on your own your monthly wage will be >5000 Turkish lira + insurance (This can be negotiated)
- It is totally up to you how fast you finish this process!
- You will join our team as a fully capable Javascript Developer and implement exciting projects with us.
