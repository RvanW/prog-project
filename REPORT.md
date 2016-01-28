# Cookbook

## Description
Cookbook is an app that is all about food, combined with a social platform. Anyone with this app can view the recipes that the community has uploaded publicly.
To make use of storing favorites and rating other recipes, users must create an account. With a (free) account users may add their own recipes to Cookbook, which in their turn can be rated and stored as favorite. This app is mainly focused on this social aspect of adding and rating public recipes. Future releases will include a commenting feature, and extended account options.

## Features

- Database with recipes from the community at your disposal
- Create an account to..
  - Store favorites online
  - Rate recipes
  - Add your own recipes
    - Upload a photo, add a description and/or ingredients.
    - Make them public, or keep them private.

## Technical design

The goal of this project building an online platform where users may upload recipes and rate others. To achieve this in the first place I will require some sort of registration and log in. Parse.com makes this very easy and has saved me a lot of time on this aspect.<br>
To thoroughly explain the different parts of my code I have drawn a sketch of how the different screens work.<br>
All screen titles can be found as Java files in my project, translating what the code is supposed to do. <br>
To make this work I have used one Activity, which holds the navigation drawer and handles the fragment transitions. <br>
![sketch](doc/tech-sketch.png)
