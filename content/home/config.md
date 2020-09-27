---
# An instance of the Blank widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: blank

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 125

title: Site Configuration
subtitle:

design:
  columns: "1"
  background:
    image: NUPurpleswatch7.png
    image_darken: 0.0
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ["20px", "0", "20px", "0"]
---

<p>my.egregious.website is fully configurable using the options below.</p>

<p>Choose the website quality level to best suit your needs:</p>
<form action="/action_page.php">
  <input type="radio" id="Excellent" name="quality" value="Excellent">
  <label for="Excellent">Excellent</label><br>
  <input type="radio" id="Good" name="quality" value="Good">
  <label for="Good">Good</label><br>
  <input type="radio" id="Just OK" name="quality" value="Just Barely OK">
  <label for="Just Barely OK">OK</label><br><br>
</form>

<p>Set your level of personal attractiveness:</p>

<form action="/action_page.php">
  <input type="radio" id="Attractive" name="attractive" value="Attractive">
  <label for="Attractive">Attractive</label><br>
</form>
