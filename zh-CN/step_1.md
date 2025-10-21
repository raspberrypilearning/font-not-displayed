当你想要使用新的 Google 字体时，你需要确保你拥有：

- 将 Google 字体中的 `<link>` 添加到你网页的 `<head>` 部分
- 更新 `default.css` 中的字体变量或用于颜色和字体调色板的样式表

此示例添加了“Bangers”字体并将其用于页眉和标题，但不用于正文：

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
