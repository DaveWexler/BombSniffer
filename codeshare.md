Duplication of a lot of functions between director and actor. A query to return the person is the same, 
regardless of whether it's actor or director. getMovies() and some of the other methods have very small 
differences in the API url request, but it would be easy enough to interpolate.

There could maybe be something like a person class, that handles both directors and actors, since there
are few differences between how they're done, and a lot of repetition. Some of the information at the bottom
could also be in the models rather than in the controller.

The appendData function could probably be separated into two functions, one to create the necessary information
for how much money the movies made, and another separate one to handle the rendering.

Some of the things in the app.js file could probably be moved to other locations, like to the movie controller
file.
