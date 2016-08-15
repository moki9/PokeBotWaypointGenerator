# PokemonGo Bot Route Point Generator
This project was created out of need to generate a list of waypoints for use with the [PokemonGo-Bot](https://github.com/PokemonGoF/PokemonGo-Bot) and other bots.

## Installation
Installation is a cinch. Download `poke_waypoints.html` and open in your favorite browser. After opening you will be presented with the following:

![empty_screenshot](https://github.com/brandonhon/PokeBotWaypointGenerator/blob/master/empty_screenshot.png)

## Use
Using the route generator is as easy as clicking on map. The map can be zoomed in/out and dragged to the location of your choice.

To setup a route for your bot first move and center the map over your location or the location you would like to use. Now select the starting point for your route. A marker will be placed at the selected point on the map and labeled with the letter '**A**'. Subsequent points will be labeled with the next letter in the alphabet to show  direction of the route from start to finish.

For those using **PokemonGo-Bot** by changing the `"path_mode": "loop"` to `"path_mode": "linear"` your bot will follow the path **A - Z** and then in reverse **Z - A**. This will make your bot behave in a more human like manner.

Below is a sample screenshot of the generator in action:
![demo_screenshot](https://github.com/brandonhon/PokeBotWaypointGenerator/blob/master/demo_screenshot.png)