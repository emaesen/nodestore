# Node Store Application with Backbone.js, Twitter Bootstrap, Node.js, Express, and MongoDB #

"Node Store" is a CRUD application built with with Backbone.js, Twitter Bootstrap, Node.js, Express, and MongoDB.


## Installation ##

1. Clone this repo
2. cd into the repo directory:
```
$ cd nodestore
```

### To run the application on your own Heroku account:###

3. Install the [Heroku Toolbelt](http://toolbelt.heroku.com)
4. [Sign up](http://heroku.com/signup) for a Heroku account
5. Login to Heroku from the `heroku` CLI:
```
    $ heroku login
```
6. Create a new app on Heroku:
```
    $ heroku create
```
7. Add the [MongoLab Heroku (sandbox) Add-on](http://addons.heroku.com/mongolab)
```
    $ heroku addons:add mongolab:sandbox
```
8. Upload the app to Heroku:
```
    $ git push heroku master
```
9. Open the app in your browser:
```
    $ heroku open
```

### To run the application locally:###
3. Install [MongoDB](http://docs.mongodb.org/manual/installation/)
4. Start MongoDB
```
    $ mongod
```
5. Install all dependencies
```
    $ [sudo] npm install
```
6. Start the web server (in a different command tab)
```
    $ node server
```
