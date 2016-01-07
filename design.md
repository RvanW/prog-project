# Design Document
## MVP
The Minimal Viable Product is an app which displays a list of popular recipes, in a simple fashion.<br>
This could be achieved by an (open) recipe API, a filled database on my private webserver. I'm also looking at the possibilities of Parse.com since I will have to deploy some sort of account creation if I want users to add recipes publicly. <br>
<br>
I want to add a social aspect to the app, where users may rate and comment. However this is not my priority since time is short. <br>
Therefore I will focus on retrieving and displaying recipes (the MVP) before working on accounts and social aspects.


## Sketch
This sketch contains most of the activities I want to create, apart from a login/signup form.
![](doc/technical-sketch.png)

## API
I'm trying to find an open recipe API and populate the recipe list.. <br>
- http://food2fork.com/about/api

## Data
For the MVP I will atleast need to get the api working. If I want users to be able to add their own recipes publicly, I need to set up my own database. I will need the following tables:
- Recipes
  - titel
  - image
  - description
  - (rating)
  - (ingredients)

- Users (might be handled by Parse.com)
  - username / email ?
  - password

- Comments
  - fromUser
  - onRecipe
  - message
