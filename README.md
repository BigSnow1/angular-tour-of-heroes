# angular-tour-of-heroes

[![Build Status](https://travis-ci.org/BigSnow1/angular-tour-of-heroes.svg?branch=master)](https://travis-ci.org/BigSnow1/angular-tour-of-heroes)

## Introduction

This is my practice of the tutorial of angular named angular-tour-of-heroes.
You can see how it works below.

Here's a visual idea of where this tutorial leads, beginning with the "Dashboard" view and the most heroic heroes:

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/heroes-dashboard-1.png)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/heroes-dashboard-1.png)

You can click the two links above the dashboard ("Dashboard" and "Heroes") to navigate between this Dashboard view and a Heroes view.

If you click the dashboard hero "Magneta," the router opens a "Hero Details" view where you can change the hero's name.

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/hero-details-1.png)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/hero-details-1.png)

Clicking the "Back" button returns you to the Dashboard. Links at the top take you to either of the main views. If you click "Heroes," the app displays the "Heroes" master list view.

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/heroes-list-2.png)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/heroes-list-2.png)

When you click a different hero name, the read-only mini detail beneath the list reflects the new choice.

You can click the "View Details" button to drill into the editable details of the selected hero.

The following diagram captures all of the navigation options.

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/nav-diagram.png)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/nav-diagram.png)

Here's the app in action:

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/toh-anim.gif)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/toh-anim.gif)


## How to use


If you want to clone and run this repository,you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

```bash
#Clone this repository
git clone https://github.com/BigSnow1/angular-tour-of-heroes.git
#Go into the repository
cd angular-tour-of-heroes
#Install dependencies and run the app
npm install && npm start

