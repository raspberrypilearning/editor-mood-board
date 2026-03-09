<h2 class="c-project-heading--task">Add depth with shadows</h2>

--- task ---
Enhance your photo strip by adding a shadow effect that makes each image stand out.
--- /task ---

--- task ---
Add the `shadow` class to each photo in your middle row.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 40
line_highlights: 41,42,43
---
<section class="wrap page"> <!-- Middle row for photos -->
  <img class="photo shadow" src="IMG_2884.PNG"> <!-- Adds drop shadow for stronger depth -->
  <img class="photo shadow" src="IMG_2875.PNG"> <!-- Adds drop shadow for stronger depth -->
  <img class="photo shadow" src="IMG_2868.PNG"> <!-- Adds drop shadow for stronger depth -->
</section>
--- /code ---

</div>
--- /task ---

--- task ---
**Test:** Run your project and confirm each image in the middle row has a visible shadow.
--- /task ---
