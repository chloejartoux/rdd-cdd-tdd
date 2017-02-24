# cli-weather

##Introduction

Cli-weather puts the weather of the destination you choose in your console.

##Prerequisite

###Installation of Node.js

https://openclassrooms.com/courses/des-applications-ultra-rapides-avec-node-js/installer-node-js

Download Node.js https://nodejs.org/en/ here

###package required

Usually, you should have a package.json named weather-cli but if you don't have it, here are the dependencies you need.

###dependencies
1.meow  v~3.7.0
2.chalk v~1.1.1
3.update-notifier v2.1.0
4.request v~2.79.0
5.lodash" v~4.17.0
6.yql v~1.0.2

###devDependencies

1.chai v3.5.0
2.coveralls v2.11.16
3.eslint v3.15.0
4.istanbul v0.4.5
5.mocha v3.2.0
6.mocha-lcov-reporter v1.2.0

##how to use cli.js?

You have to indicate the city, the country and if you want the temperature in
Celcius or in Fahrenheit.(C stands for Celcius and F stands for Fahrenheit)

node cli.js [City] [Country] [C or F]

Example: node cli.js Paris France C
Paris; France
Condition: Mostly Cloudy
Temperature: 9C
