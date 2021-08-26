# Kitchen Genie 

Live version of [kitchen-genie](https://kitchen-genie.co.uk) is up and running!

For the final two weeks of Sigma Labs training, trainees were assigned to various group projects. The I chose to be assigned to was the Kitchen Genie ('recipe team' back then) project. Our team of four consisted of Tawab Rahmani, Keano Robinson, Rafiul Ansari and myself. 

Our goal for this project was to build a tool that home cooks can use to combat household food waste. Since​, by weight, UK households throw away 4.4 million tonnes of edible food each year; and 24% of people do not know what was in their fridge when they shop (Wrap Study - 2020). So it was clear to us that we wanted to build an application that helped people come up with recipes from the ingredients they already have at home. 

[Supercook](https://www.supercook.com/#/recipes) was also a main inspiration behind this project, however, we thought we could do so much better upon tear down. 


## How does Kitchen Genie work?

![kitchen-genie demo](https://github.com/CZ32/kitchen-genie/blob/readme/frontend/public/Kitchen%20Genie.gif)

#### Page Diagram 

- HOME
    - SEARCH RESULTS
    |  -- RECIPE
    - FAVOURITES (Logged in experience)
    |  -- RECIPE 
    - ABOUT US
    |
    - FAQ

#### Description 

The kitchen-genie website has both a logged in and logged out experience. In the logged in experience, users from the home page can insert ingredients into the search bar. When searched, Kitchen Genie will fetch data from the Spoonacular API and populate recipes on a Search results page. From here, the user (logged in) can favourite recipes by clicking the heart icon on recipe cards or can click a card to navigate to the recipe page. On the Recipe page, the application will fetch recipe data from the Spoonacular API and populate that information in an clean and consistent manner. The user can view recipe description, preparation and what ingredients they do/don't have (if coming from search results). Again, the user can favourite the recipe (if logged in) and can make comments on the recipe (if logged in). If the logged in user clicks on the favourites page, the page will populate all the recipes the users has favourited in the past

## Key Features 

1. Login/Signup page.
2. Search bar: Allows users to insert the ingredients they have in a stylistic and legible format. Searches Spoonacular API by these ingredients.
3. Recipe results page: Displays all the recipes with relevant ingredients. 
4. Recipe page: From the recipe result page, user can click a recipe and the recipe ingredients is populated on the page in a consistent, appealing manner. 
5. Comments: If user is logged in, user has the ability to comment on recipes. 
6. Favourites: From recipe page, or results page, user can favourite recipe and it populates it on the users favourites page.
7. Random recipe generator: User can click a button to get a random recipe from the spoonacular api. 

# How did we conduct our work. 

# My specific roles within the team

# Software Architecture

# How we set up our database

# Deployment 

# Extra: What if we had more time?
1. Use client-side cookies to save the ingredients the user has during a session, so recipes ingredients can be compared even if the user has not come from the search results page. 

