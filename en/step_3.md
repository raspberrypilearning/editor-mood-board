<h2 class="c-project-heading--task">Apply your colour theme</h2>

--- task ---
Choose a theme stylesheet and apply colour classes so the page picks up your mood board palette.
--- /task ---

--- task ---
Edit the theme files and classes in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 25, 28, 30, 40
---
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />

    <!-- Title shown in web browsers -->
    <title>Travel inspiration 🐅</title>

    <!-- Import fonts from Google -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Bungee+Shade&family=Codystar:wght@300&family=Creepster&family=Eater&family=Faster+One&family=Finger+Paint&family=Flavors&family=Freckle+Face&family=Fredericka+the+Great&family=Gorditas&family=Hanalei+Fill&family=Lobster&family=Luckiest+Guy&family=Miltonian&family=Monoton&family=Ranchers&family=Rubik+Moonrocks&family=Shrikhand&family=Spirax&family=Titan+One&Bebas+Neue&Cairo&display=swap"
      rel="stylesheet"
    />

    <!-- Include CSS style file -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="animation.css" rel="stylesheet" type="text/css" />
    <link href="land-animals.css" rel="stylesheet" type="text/css" /> <!-- Loads one of the starter colour themes -->
  </head>

  <body class="tertiary"> <!-- Applies your chosen background and text colours -->
    <!-- The page header code goes here -->
    <header class="border-bottom secondary"> <!-- Gives the header a themed panel colour -->
      <h1>Travel Inspiration</h1>
    </header>

    <!-- The main content for the web page goes between the main tags -->
    <main>
      <section>
        <p>Lorem ipsum dolor sit amet.</p>
      </section>
    </main>

    <!-- Footer code goes here -->
    <footer class="border-top secondary"> <!-- Matches the footer colours to the header -->
      <p>Colours of India</p>
    </footer>
  </body>
</html>
--- /code ---

</div>
--- /task ---

--- task ---
**Test:** Run the project and check that the page background, header, and footer use your chosen theme colours.
--- /task ---
