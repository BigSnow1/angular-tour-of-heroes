# angular-tour-of-heroes

[![Build Status](https://travis-ci.org/BigSnow1/angular-tour-of-heroes.svg?branch=master)](https://travis-ci.org/BigSnow1/angular-tour-of-heroes)

angular studying

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


6. Services
7. Routing
8. HTTP
FUNDAMENTALS
TECHNIQUES
API
stable (v5.2.7)
Tutorial: Tour of Heroes
The Tour of Heroes tutorial covers the fundamentals of Angular.
In this tutorial you will build an app that helps a staffing agency manage its stable of heroes.

This basic app has many of the features you'd expect to find in a data-driven application. It acquires and displays a list of heroes, edits a selected hero's detail, and navigates among different views of heroic data.

By the end of the tutorial you will be able to do the following:

Use built-in Angular directives to show and hide elements and display lists of hero data.
Create Angular components to display hero details and show an array of heroes.
Use one-way data binding for read-only data.
Add editable fields to update a model with two-way data binding.
Bind component methods to user events, like keystrokes and clicks.
Enable users to select a hero from a master list and edit that hero in the details view.
Format data with pipes.
Create a shared service to assemble the heroes.
Use routing to navigate among different views and their components.
You'll learn enough Angular to get started and gain confidence that Angular can do whatever you need it to do.

After completing all tutorial steps, the final app will look like this live example / download example.

What you'll build
Here's a visual idea of where this tutorial leads, beginning with the "Dashboard" view and the most heroic heroes:

Output of heroes dashboard
You can click the two links above the dashboard ("Dashboard" and "Heroes") to navigate between this Dashboard view and a Heroes view.

If you click the dashboard hero "Magneta," the router opens a "Hero Details" view where you can change the hero's name.

Details of hero in app
Clicking the "Back" button returns you to the Dashboard. Links at the top take you to either of the main views. If you click "Heroes," the app displays the "Heroes" master list view.

Output of heroes list app
When you click a different hero name, the read-only mini detail beneath the list reflects the new choice.

You can click the "View Details" button to drill into the editable details of the selected hero.

The following diagram captures all of the navigation options.

Here's the app in action:

[![Image text](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/toh-anim.gif)](https://github.com/BigSnow1/angular-tour-of-heroes/blob/master/img-storage/toh-anim.gif)


