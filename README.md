# Budget Tracker
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[Deployed on Heroku](https://mysterious-anchorage-52189.herokuapp.com/)

## Description:  
A Progressive Web Application (PWA) demonstrating the use of the Chrome Browser and IndexedDB API to store transactions entered by the user when the browser is offline and "synced" when the browser comes back online. 

    
## Table of Contents:
* [Installation](#installation-instructions)
* [Usage](#usage)
* [Routes](/routes.md)
* [Tests](#tests)
* [Questions](#questions)
* [License](#license-info)

## Installation Instructions
This application is designed to run locally using [Robo 3t](https://www.robomongo.org) or another MongoDB management tool. 

Run `npm i` to install [npm](https://www.npmjs.com/) dependencies. 

## Usage

Users can "install" this application for a native-like experience:

![](https://github.com/jessicablank/budget-tracker/blob/master/public/pictures/Demonstration.gif)

Mobile Display:

![](https://github.com/jessicablank/budget-tracker/blob/master/public/pictures/homepage-with-data.PNG)


## Tests
* Transactions can be entered while the browser is online or offline. 
* Both the table and the graph are updated accordingly when the user clicks "Add Funds" or "Subtract Funds"
* When the user clicks "Clear Table", all data in the collection is deleted and the application accepts new data. 

## Questions
You can reach the author, Jessica Blankemeier,  via [github](http://github.com/jessicablank) and [email](mailto:jessicablankemeier@gmail.com)
![GitHub](https://img.shields.io/github/followers/jessicablank?label=follow&style=social)

## License
Copyright 2020 - present Jessica Blankemeier.
This project is licensed under the terms of the MIT license. 
More information is available at [opensource.org/licenses](https://opensource.org/licenses/MIT)
