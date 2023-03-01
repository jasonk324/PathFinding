# PathFinding Project

## Motivation
During a road trip with friends, we noticed large areas of open green land on the GPS map and small towns scattered throughout the map, marked as a different color. We enjoyed the experience of traveling through these small towns and thought of making it a deliberate part of our trip. This project is an attempt to achieve that goal more intentionally.

While Google Maps API could be used for this purpose, I was interested in image reduction and learning more about image sampling. Therefore, I decided to work on this project as an opportunity to explore that interest.

## Inspiration
This project was also inspired by  [Pathfinding Visualizer Tutorial (software engineering project)]{https://www.youtube.com/watch?v=msttfIHHkak&t=650s}

## Some Notes/Requirements to self
1. Make the path finding algorithm visualization part
2. Make it so that the resolution of the grid is adjustable using a slider
3. Make an on/off switch so that you can pick if you want to make stops at the smaller locations or not
4. Add a file drop input field to the UI so that you can drop in a file. 
5. Add another on/off switch so that you can enable or disable the drop field so that people can draw their own maps if they want.
6. Design it a bit nicely (add a title bar and some borders)
7. Prepare python code to be able to down sample an image
8. Make the python code simplify all colors to 4 colors, start location, end location and if the space is not a road then make it a wall
9. If the setting is selected then you need to add a pin for additional stop locations along the way in areas with populations 
10. Set up flask backend to make the python code intereact with the front-end