<h2 class="c-project-heading--task">Update your page text</h2>

--- task ---
Change the browser title, page heading, and footer text so they match your mood board idea.
--- /task ---

--- task ---
Edit the text in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 9, 30, 41
---
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />

    <!-- Title shown in web browsers -->
    <title>Travel inspiration 🐅</title> <!-- Sets the text shown in the browser tab -->

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
    <link href="land-animals.css" rel="stylesheet" type="text/css" />
  </head>

  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom secondary">
      <h1>Travel Inspiration</h1> <!-- Shows your mood board title on the page -->
    </header>

    <!-- The main content for the web page goes between the main tags -->
    <main>
      <section>
        <p>Lorem ipsum dolor sit amet.</p>
      </section>
    </main>

    <!-- Footer code goes here -->
    <footer class="border-top secondary">
      <p>Colours of India</p> <!-- Adds a short caption to match the theme -->
    </footer>
  </body>
</html>
--- /code ---

</div>
--- /task ---

--- task ---
**Test:** Run the project and check that the browser tab title, page heading, and footer text have changed.
--- /task ---
