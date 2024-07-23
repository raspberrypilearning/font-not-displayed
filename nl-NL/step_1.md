Als je een nieuw Google-lettertype wilt gebruiken, moet je ervoor zorgen dat je het volgende gedaan hebt:

- De `<link>` van Google Fonts toegevoegd aan het `<head>` gedeelte van jouw webpagina
- De lettertypevariabelen bijgewerkt in `default.css` of de style sheet die je gebruikt voor jouw kleuren- en lettertypepalet

In dit voorbeeld wordt het lettertype 'Bangers' toegevoegd en gebruikt voor kopteksten en titels, maar niet voor de hoofdtekst:

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<!-- Importeer lettertypen van Google -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">

--- /code ---

--- code ---
---
language: CSS
filename: default.css
line_numbers: false
---

--body-font: 1.1rem Verdana, sans-serif;
--header-font: lighter 3rem 'Bangers', cursive;
--title-font: lighter 2rem 'Bangers', cursive;

--- /code ---
