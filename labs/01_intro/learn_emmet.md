# Learn Some Emmet

While you'll mainly be writing JavaScript, being able to efficiently write HTML when you need to is always going to come in handy, especially for these labs, where you'll need to create a bunch of repetitive HTML.

1. Make sure Emmet is working in VS Code.
2. Go find a cheat sheet that you like for Emmet and save it, then paste the 5 commands you anticipate using the most, below.

    ```text
    Paste the five top commands here:

Command: nav>ul>li

<nav>
  <ul>
    <li></li>
  </ul>
</nav>

Command: section>p+p+p

<section>
  <p></p>
  <p></p>
  <p></p>
</section>

Command: section>header>h1^footer

<section>
  <header>
    <h1></h1>
  </header>
  <footer></footer>
</section>

Command: section>(header>nav>ul>li)+footer>p

<section>
  <header>
    <nav>
      <ul>
        <li></li>
      </ul>
    </nav>
  </header>
  <footer>
    <p></p>
  </footer>
</section>

Command: ul.menu>li.menu__item+li#id_item+li.menu__item#id_2

<ul class="menu">
  <li class="menu__item"></li>
  <li id="id_item"></li>
  <li class="menu__item" id="id_2"></li>
</ul>
    
    ```

3. Create a basic web page with Emmet, it should contain the basic HTML boilerplate, a `main` container with three `section` elements, each containing a header element and a few `div` elements. Write the necessary commands for that below.

    ```text
    Write the commands here:

To create basic html page
Command: !
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Document</title>
</head>
<body>
    
</body>
</html>

To create main container and three section elements
Command: div#main>(section+section+section)
<div id=main>
    <section></section>
    <section></section>
    <section></section>
</div>

To create headers and div elements in each section
Command: header+div+div 

<header></header>
<div></div>
<div></div>

    ```
