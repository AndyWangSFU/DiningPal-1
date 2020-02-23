# DiningPal: A Sense of Belonging for Your Dining Experience

# Background

## Mission Statement of Our Design
Nowadays, it is very common for people to dine by themselves due to the fast-paced urban life. We may have got used to it, or more likely just ignored the existence of loneliness in our hearts. To solve such kind of unpleasant experience and let every lonely diner have a sense of belonging, we designed our application, DiningPal.


# Introduction

DiningPal is an online web application allowing multiple users to make plans of dining together. After sign-up/login, users can propose their favorite restaurant(s) (with ranks) and find friends (or strangers), who also prefer similar restaurant during that specific time to have dinner together. 

The features of this application will include locating users,positioning/ranking/auto-recommend restaurants, with future implementations including chat rooms, usersfilter system, map navigation, coupon search, weather condition check and so on. Though this application can be used to arrange other places of collective activities, such as gym, theaters, shopping malls etc., it is primarily designed to help people find diner mates in an easy and comfortable way.


# Usage

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/ZiyiAn/DiningPal.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)

# Course Background
This is a group project for CMPT276 (Introduction to Software Engineering) in Summer 2019 at Simon Fraser University. The instructor is [Bobby Chan](https://www.sfu.ca/computing/people/faculty/bobbychan1.html). For more information on the course description, you can refer to [here](https://www.sfu.ca/students/calendar/2019/summer/courses/cmpt/276.html). 

## Presented Together By:
Ziyi An 301371687,
George He 301315033,
Bowen Wang 301267523,
Zihan Wang 301329429,
Chen Zhao 301308092
# My Contribution:
Basically I was responsible for three tasks:
1. Build the chatroom using socket.io service and MongoDB.
2. Build the "food digger" functionality using Zomato API and Google Map API. 
3. The main writer of our final documentation and leader of 15-min presentation.

I also joined the design and creation of the main user interface (HTML/CSS/JavaScript edit). 
