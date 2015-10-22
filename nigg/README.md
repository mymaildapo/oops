###### Semantic Web and Linked Data - Exercise 5
# Diamond API
In this exercise we will build a HTTP API for keeping stock of our diamonds.

## Exercises
1. In diamond.js, write code to create a sqlite database, with a single table that has the folloiwng fields (Explanations for all fields except id are available in the file prices-of-diamonds.html.
id should be a auto-incrementing primary key.):
  - id
  - carat
  - cut
  - color
  - clarity
  - depth
  - table
  - price
  - x
  - y
  - z

1. Write a function to load the contents of prices-of-diamonds into the database.

1. Add four methods to the express app in diamond.js to:
  - GET a diamond by its id.
  - POST new values for a diamond by its id.
  - PUT a new diamond at a given id.
  - DELETE a diamond by its id.

1. Test the use of the API using curl.

## Advanced exercises
1. Create a single HTML file to interact with the API using AJAX calls.

## Note
- See the sqlite3 npm page [here](https://www.npmjs.com/package/sqlite3) for an example of using a sqlite database in node.

- See the node-sqlite3 GitHub page [here](https://github.com/mapbox/node-sqlite3) for more information on using sqlite in node.

- See the Express documentation [here](http://expressjs.com/starter/basic-routing.html) for example of using GET, POST, PUT and DELETE.

- See [this blog post](http://blogs.plexibus.com/2009/01/15/rest-esting-with-curl/) for example of using Curl to test an API.
