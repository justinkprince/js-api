# Clean up

This branch is all about making the developer experience better.

By default, the express-generator library adds support for views (something a rest API doesn't need) so we remove the view files and where they are used.

Secondly, having to restart the server every time we change some code is a bit of a headache so let's add nodemon to watch for file changes and restart automatically.
