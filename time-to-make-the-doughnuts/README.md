# 8.4 It's Time to Make the Donuts

https://www.youtube.com/watch?v=petqFm94osQ

-------------------

## Batch Maker, Batch Maker, make me a batch!

### Overview

A local baker has approached Carolina Code School with an application idea, and it's up to you to bring her idea to life!

### Problem

The baker needs to be able to scale recipes up and down depending on the yield or the availability of a certain ingredient. She currently uses an extremely complex Excel document, and it's a real pain.

### Who would use this app?

Bakers. Bakers currently use excel or calculators to manually adjust recipes based on the needs of that day or available ingredients. This is time consuming, tedious, and has a high risk of error. This app removes the pitfalls of the current system.

## Objectives

After completing this assignment, you should be able to:

* Demonstrate understanding of React.js Components
* Demonstrate understanding of Django
* Demonstrate understanding of Django Rest Framework

## Details

### Instructions

 - [ ] Review the wireframes
 - [ ] Configure an API app with Django Rest Framework
 - [ ] Build user signup and login
 - [ ] Build a Batch Maker app with React that will allow users to manage their recipes

### Requirements

* No ESLint warnings or errors
* Use Bootstrap to achieve default styles
* Use React for the UI
* Use Django Rest Framework to build api endpoints
* Enforce that users are logged in to see their data using Django auth and Django Rest Framework

## I'm a Full Stack Developer Mode

- [ ] Create an `AdjustRecipe` component that takes a recipe object as a prop. You don't need to start with HTTP requests, you may use static data

![](images/adjusted.png)

- [ ] Create a `App`, `RecipesList`, and `RecipeForm` component to add CRUD functionality
- [ ] Create links to allow the user to switch between the different components - the Bootstrap nav bar is useful for this sort of thing
- [ ] Build a signup form
- [ ] Build a login form
- [ ] Connect your signup form and login forms to Django users
- [ ] Connect your `RecipeForm`, `RecipesList`, and any other components to Django Rest Framework
- [ ] Add an option to change the unit of measurement per ingredient (ounces or pounds)
- [ ] Add the ability to specify the yield number and yield name (scones, loaves, cookies, etc)
- [ ] Bakers should be able to enter their own ingredients

- [ ] Add a “Notes” section for bakers to enter in notes about the recipe (bake time, instructions, etc)
- [ ] When creating an ingredient, give the bake the ability to provide brand or type of that ingredient; bakers should also enter be able to enter in the price of that ingredient to calculate overall cost
- [ ] On the batch screen, add an option to change the type of measurement by weight (imperial or metric)
- [ ] When a recipe is created, a baker should be able to specify the type of measurement (grams or cups) of the recipe

- [ ] Turn Batch Maker into a social site! Allow bakers to share their recipes with others.
- [ ] Implement remaining features shown in the wireframes

## Wireframes

### Home

![](images/1-home.jpg)

### New Recipe 1

![](images/2.1-new-recipe.jpg)

### New Recipe 2

![](images/2.2-new-recipe.jpg)

### Recipe Preview

![](images/3.1-recipe-preview.jpg)
