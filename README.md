# fitness-tracker
![License Badge](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

This is a NodeJS based project using a MongoDB that allows a user to add track their exercise for fitness use.


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Credits](#credits)


## Installation

Download, clone, or fork the repo and run an `npm install` command in the folder directory. This will install the dependencies needed for NodeJS to run the application as listed in `package.json`. This will also seed 

 * [`express`](https://www.npmjs.com/package/express) allows the application to utilize express.
 * [`mongoose`](https://www.npmjs.com/package/mongoose) allows for use of object templates with MongoDB.
 * [`morgan`](https://www.npmjs.com/package/morgan) is an HTTP request middleware logger for nodeJS that allows for easier logging.

To start the application, run `npm start` on the command line.



## Usage

To start the application, run `npm start` on the command line or [visit the deployed version on Heroku](https://workout-fitness-app-1.herokuapp.com/).

<p align="center">
    <img alt="Main landing page" src="">
</p>
From the main page, you can choose to start a new workout or continue an existing workout. Alternatively, you can also select to go to the Dashboard in the upper left. Selecting the "Fitness Tracker" will take you bac to this main page.


There are 2 types of exercises: Cardio and Resistance.
<p align="center">
    <img alt="Types of exercises" src="">
</p>

With Resistance selected, you are required to fill in the exercise name, weight, sets, reps, and duration in minutes.
<p align="center">
    <img alt="Resistance Example" src="">
</p>

With Cardio selected, you are required to fill in the exercise name, distance in miles, and duration in minutes.
<p align="center">
    <img alt="Types of exercises" src="">
</p>

On the Dashboard page, you can view the history of workouts completed. Hovering over the data will display more information.
<p align="center">
    <img alt="Exercise Dashboard" src="">
</p>


## License

Licensed under the [MIT](LICENSE.txt) license.


## Credits

The package `express` for NodeJS can be found [here](https://www.npmjs.com/package/express).

The package `mongoose` for NodeJS can be found [here](https://www.npmjs.com/package/mongoose).

The package `morgan` for NodeJS can be found [here](https://www.npmjs.com/package/morgan).
