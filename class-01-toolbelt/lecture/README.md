class-01 lecture
================

# hello-alert
**hello-alert/index.html**
``` html   
<!DOCTYPE html>
<html>
  <head>
    <title>Hello Alert</title>
  </head>
  <body>
    <h1>Hello Alert!!!!!</h1>
    <script src="app.js" type="text/javascript"></script>
  </body>
</html>
```   

**hello-alert/app.js**
``` javascript   
// print to the developer console to makesure javascript is working!
console.log('hello world from javascript');

// use javascript to display information to the user with an alert!
alert('hello user I am javascript!');

// get user input from a user and store it in a variable named favoriteNumber
var favoriteNumber = prompt('what is your favorite numeber?');

// use javascript to display thier input
alert('your favorite number is ' + favoriteNumber);

// get true/false input from a user
var slugsRule = confirm('are wizzards bettter than slugs?');

// use javascript to display thier input
alert('wizzards are better than slugs: ' + slugsRule);
```   

