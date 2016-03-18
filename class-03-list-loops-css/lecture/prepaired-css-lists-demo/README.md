# prepaired css and list demo
**index.html**
``` html   
<!DOCTYPE html>
<html>
  <head>
    <title>lists and css</title>
    <link rel="stylesheet" type="text/css" href="style.css"></link>
  </head>
  <body>
    <header>
      <h1> lists and css</h1>
      <p>we are going to learn so many fun things today</p>
    </header>
    <section id="ordered-list">
      <h1>un ordered list</h1>
      <ul>
        <li>javascript</li>
        <li>Chrome Browser</li>
        <li>atom</li>
        <li>git</li>
        <li>git</li>
      </ul>
    </section>
    <section id="unordered-list">
      <h1> ordered list</h1>
      <ol>
        <li>first</li>
        <li>second</li>
        <li>third</li>
        <li>fourth</li>
      </ol>
    </section>
  </body>
</html>
```   

**style.css**
``` css   
body {
  background-color: #e2bd78;
}

header {
  background-color: #78e2d4;
}

h1 {
  font-size: 0.5em;
  color: #fafafa;
}

header p {
  text-decoration: line-through;
}

li {
  font-size: 1em;
}

#ordered-list {
  background-color: #fff;
}
```   

