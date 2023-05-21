![alt text](bitcamp-android/Screenshot 2023-05-21 at 4.12.11 PM.png)


# What's Cookin? - Synopsis

This is a mobile application that displays the daily updated menu (Breakfast, Lunch, Dinner) for the current 3 UMD dining halls around campus (South diner, The Diner, and 251 North). Each diner traditionally has its own daily menu which varies from diner to diner. Users may filter to their diner of preference and see a live update of the menu. Furthermore, the functionality that we wanted to highlight is its versatility in being able to filter diner menu options for people with dietary restrictions. We found that many times (from personal experience) the trip made to the dining hall was not worth it as the limited selection of food items available to our diets was not worth the trip. Thus, we aimed to tackle the challenge of being able to keep terps connected and updated in a compact and reliable way as to what food was available to them. And what better way to do this than a mobile app.


## How it is built?

We used flutter to build the mobile front end of the application. Then, we used the Cockroach Database supported by Google Cloud to store meal data that was taken from the UMD dining menu website. Then we queried the database with SQL from within the app and displayed it. The app also provides filters to specify which types of food one is seeking.

## Motivation

We were inspired to attempt to tackle this problem as it was something we wish existed within UMD. The technology we wanted to use was inspired by a workshop that Vaibhav and Navid had the honor of hosting during bitcamp, “Introduction to flutter.” After the workshop they held we all were interested and curious to bring our newfound knowledge of flutter to life. Aiming to create a tangible project that we saw could be an assist during our time here at UMD.

With that said this is a very personal project to us. Vaibhav, being a vegetarian, Alex having a seafood allergy, and myself being gluten-free, having the luxury to eat whatever wherever is not an option. So, we set out to try and solve something that would impact us and presumably others with food restrictions/diets.

### Official Link
https://devpost.com/software/what-s-cookin

### Replit
https://replit.com/@vladodio/MenuScraper#main.py

### Stack

<ul>
  <li>beautiful-soup</li>
  <li>cockroachdb</li>
  <li>dart</li>
  <li>flutter</li>
  <li>google-cloud</li>
  <li>json</li>
  <li>python</li>
  <li>requests</li>
  <li>sql</li>
</ul>

### Contributors

<ul>
  <li>pistachionet</li>
  <li>VaibhavSanjay</li>
  <li>nathanb9</li>
  <li>vladodio</li>
  
</ul>



