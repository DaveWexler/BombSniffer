### Bombsniffer
Nice job!
Suggestions:
+ app.js - If you're importing jQuery, probably use it throughout for consistency
+ YouTube code should probably be in its own controller and broken into smaller functions
+ Suggest using handlebars to render the template in actorsController. Also `appendData()` should be broken up into smaller functions
+ Ajax calls in actorsController should be moved into an adapter
+ Overall, make smaller methods that do only a single thing
