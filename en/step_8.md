<h2 class="c-project-heading--task">Improve spacing in your layout</h2>

--- task ---
Adjust your CSS spacing rules so the rows feel cleaner and easier to read.
--- /task ---

--- task ---
Edit `style.css` to add gaps and tighten item sizes in wrapped rows.

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 153
line_highlights: 162, 178, 179, 194
---
.wrap {
  /* Make content wrap over multiple rows */
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
  gap: 1rem 1rem; /* Adds visible space between wrapped items */
}

/* For creating fancy boxes */

.dashed-border {
  border: 0.25rem dashed var(--detail2);
}

.solid-border {
  border: 0.25rem solid var(--detail2);
}

/* Styles for the div tags that are inside a .wrap class */

.wrap > div {
  width: 12rem; /* Narrows each tile so three items fit comfortably */
  padding: 0rem; /* Removes extra internal spacing around emoji blocks */
}

/* Styles for the img tags that are inside a .wrap class */

.wrap > img {
  width: 14rem;
  display: block;
}

/* Styles for the p tags that are inside a .wrap class */

.wrap > p,
.wrap > span {
  width: 14rem;
  display: block;
  padding: 0rem; /* Keeps text and span blocks aligned with image spacing */
}
--- /code ---

</div>
--- /task ---

--- task ---
**Test:** Refresh your webpage and check that the rows have clearer spacing with less crowding between items.
--- /task ---
