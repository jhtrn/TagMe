# TagMe

**Project 2 - CPSC 473 Front-End Development course** <br />
A web game where players can guess the hashtags associated with each gif. <br />
Developed by Yashdeep Kajal, Luigi Sanchez, Justine Tran, Leigh Salvador, Grace Derderian.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation/Configuration Documentation

**Clone** or **download** the repo
* `cd into folder`
* `npm install`
* `bower install`
* `ember install ember-countdown`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

## Issues

* In **play.js under routes** code, we had to split the imgURL to get tags, separated by '-' <br />
This is because the tenor api purposely returns the tag list as a null array. <br />
We emailed tenor and they said that they can't return the tags. <br />
They said that the tags are related to how they implement their search algorithm. <br />
Since we didn't want to quit on this idea, we fixed it with this parsing solution instead. <br />
* Sometimes, when a gif display text in a different language, the tag result will return undefined. <br />


## User Documentation

### Tutorial

Click on **Tutorial** in navigation bar to get instructions on how to play the game.

### How to play

Click on **Play** in navigation bar to play the game.

### Rules
1. There will be 3 rounds total <br />

2. Each round will be 1 minute long <br />

3. Enter your guess of what hashtags are associated with the gif <br />

4. Your correct and incorrect guesses will be displayed on the sidebars <br />

5. Score will be updated for each correct guess <br />

6. At the end of the 3rd round, you will get to see how you ranked on the scoreboard <br />

### Scoreboard

Click on **Scoreboard** in navigation bar to view scores of all the players ranked highest to lowest.

### Review

Click on **Review Us** in navigation bar to leave a review of the game. <br />

Reviews will be displayed on **Reviews** section in navigation bar.

## Credits
Gifs were generated from [`tenor API`](https://tenor.com/gifapi/documentation) <br />
Image on home page was used under the **Creative Commons Zero (CC0) license** from [`PEXELS`](https://www.pexels.com)
