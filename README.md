# Food FindAR
Find nearby restaurants in AR!

## Inspiration
Our inspiration for creating Food FindAR was that we wanted to use Augmented Reality to develop a product that was easy to use and more useful than a typical map app.

## What it does
Food FindAR helps you find nearby restaurants with an Augmented Reality 3D map.

## How we built it
We built Food FindAR using Unity and C# with the Vuforia plugin for Augmented Reality support. We also used the MapBox API for the 3D map and the Esri API for getting nearby restaurants.

## Challenges we ran into
One of the main challenges we ran into was having to change our project idea halfway through the competition. We wanted to make an AR map that showed housing data using Zillow, but we found that Zillow's API had a lot of missing data, so we switched to our project idea and used Esri's API, which easily allowed us to use data about the surrounding area based on a given location.

## Accomplishments that we're proud of
Some of the accomplishments we are proud of include creating the 3D map with detailed buildings and creating map markers with text that always faces you from any angle.

## What we learned
We learned how to use APIs for the first time, as we parsed data received from the JSON data of the Esri API to get the name and address of nearby restaurants.

## What's next for Food FindAR
Our next goal for Food FindAR is to add street navigation, so the fastest path from your current location to the selected restaurant will be highlighted on the map.
