# Food Whiz

## Description
Food Whiz is an application which allows users to search for Fast food Restaurants near their location via Google maps. They are able to comment (with pictures) and review a selected Restuarant. They can sort Restaurants by rating, distance, type and opening & closing hours. You also have an option to create an account, which allows you to save favorite restaurants, set your preferred food categories, and get recommendations based on them.

### Small Walkthrough 
Step 1: A user may search and select a restaurant 

![1](https://user-images.githubusercontent.com/22204759/52250742-41db3a00-28c7-11e9-94ce-0ca216aa12fc.PNG)

Step 2: Choosing a Restaurant will display its information. Each Restaurant has a commenting section where users can write written reviews and such

![2](https://user-images.githubusercontent.com/22204759/52250852-c8901700-28c7-11e9-8fcf-b9b824c24d51.PNG)


## Key Features 
* Implementing an organized, clean and resposive UI
* Disqus API works as intended (Commenting)
* Intergrate Google Maps API to do the following
  * Display the map from google maps
  * Get your location from the browser
  * Search for restaurants near your location
  * Search for restaurants near an address or POI
* Extract information about a Restaurant via Google Maps Places API
  * Address 
  * Phone Number 
  * Opening and Closing hours
  * Website
  * Ratings

## Additional Features (in the works)
* Create/Edit an account for the web application with:
  * Name 
  * Picture (Default included)
  * Address
* Listing Restaurants near a User's address
* Commenting on Restaurants if selected
* Web Security
  * Implement HTTPS to prevent eavesdropping and spoofing attacks
  * Secure the cookies to prevent mixed-content attacks
* Sorting Restaurants by rating, distance, type and opening & closing hours
* Filter restaurants by category
* Upvoting and Downvoting a Restaurant (1 star rating - 5 star rating)


## Technology
* Bootstrap and W3
  * CSS layout
* NodeJS
* Google Maps API 
  * Search Everywhere feature
* Disqus API
  * Commenting

### Note: Currently not hosted. In order to view locally, choose the clone or download option at the top right and download as zip. Extract the contents and navigate to app/frontend/index.html. Some features may not be working due to backend configurations.
