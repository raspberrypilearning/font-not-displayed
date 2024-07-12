Si tu souhaites utiliser une nouvelle police Google, tu dois avoir effectué ces actions :

- Ajouter le contenu '<link>' de Google Fonts à la section '<head>' de ta page web
- Mettre à jour les variables de police dans 'default.css' ou dans la feuille de style que tu utilises pour ta palette de couleurs et de polices

Cet exemple ajoute la police 'Bangers' et l'utilise pour les en-têtes et les titres, mais pas pour le corps :

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<!-- Import fonts from Google -->

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">

\--- /code ---

## --- code ---

language: CSS
filename: default.css
line_numbers: false
--------------------------------------------------------

\--body-font: 1.1rem Verdana, sans-serif;
\--header-font: lighter 3rem 'Bangers', cursive;
\--title-font: lighter 2rem 'Bangers', cursive;

\--- /code ---
