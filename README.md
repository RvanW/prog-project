# Programmeer project UvA
This app is mainly, and combines it with social aspects. <br>
With this app, users can view public recipes from this "social food network" anytime. <br>
If they wish to take part of the network themselves, they may chose to sign up for an account. <br>
This way users are allowed to upload their own recipes, take a photo, and add a description. <br>
If users decide to make their recipe public, it can be rated by others. This affects how high up in the public gallery this recipe ends up. <br>
I hope to inspire people to eat new things with this app, and entertain themselves while browsing and rating.

# Features

- Database with recipes from the community at your disposal
- Create an account to..
  - Store favorites online
  - Rate recipes
  - Add your own recipes
    - Upload a photo, add a description and/or ingredients.
    - Make them public, or keep them private.
  
# Sketches
![sketch](doc/technical-sketch.png)

# Data, Parts & API's
After some discussion with the teacher I have decided to NOT focus on implementing a recipe API. Instead I will focus on the part that makes my app unique, which is the social feature in combination with a food platform. Therefore I shall first take care of logging in an signing up users, then adding and displaying recipes. I will also try to get the comments feature working before I look into the possibilities of connecting my app to an existing recipe API.
<br><br>
As for my database I will at least require these tables:<br>
- User
  - Id
  - Username
  - Password

- Recipe
  - Id
  - Title
  - Description
  - Ingredients
  - Image

- Favorite
  - Id
  - UserId
  - RecipeId

- Rating
  - Id
  - RecipeId
  - UserId
  - Rating
  
  
# Potential problems

Building a social platform might be time consuming, I must focus on the most important features first. After some feedback I've decided to focus on the social aspect of users being able to add recipes publicly. Also implementing a rating system with proper rules might be a potential hazard, can only be done if the rest is finished. Connecting the different parts later might be tricky.

# Similair apps
There are a lot of food rating apps, design wise I think youTube app is a great example of the UI i intend to build.
![](https://r3.whistleout.com.au/public/images/articles/2013/08/YouTube-for-Android-Screenshot.png)

Feature-wise I think the Albert Heijn app (Appie) comes pretty close. I think the main difference between this app and mine is the social aspect and being community based.

