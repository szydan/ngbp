ngbp - AngularJS Project Boilerplate
==========================================
## Installation

To install the project template, run the following commands:

```
$ npm install
````

````
$ bower install
````


## Usage:
#### In Development
For rapid development and prototyping:
```
$ grunt watch
```
then, open your browser on `http://localhost:9000/`. 

To make a full project build:
```
$ grunt
```
This will create a folder `./build`. Note: This does not run the karma unit tests by default.

#### In Production
To compile the project for production:
```
$ grunt production
```
This will create a folder `./production`. This includes javascript, html and CSS minification and runs the Karma unit tests.

## Run npm Serve with CORS disabled:
```
$ serve --port 9000 --cors 
```

Copyright &copy [Antonio Aguilar](http://www.antonio-aguilar.com), 2015.
