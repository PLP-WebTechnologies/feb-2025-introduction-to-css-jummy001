# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

**my Assignment link**
https://codepen.io/jummy001/pen/xbxowBO
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header id="main-header">
    <h1 class="title">Welcome to My Webpage</h1>
  </header>

  <section class="content">
    <p class="intro">From lattes to pastries, Africa Coffee has something for everyone in Ifako/Ijaye! Explore our menu and discover your new favorite coffee or treat. We're your go-to spot for a delicious experience</p>
    <img src="https://static.vecteezy.com/system/resources/thumbnails/025/282/026/small/stock-of-mix-a-cup-coffee-latte-more-motive-top-view-foodgraphy-generative-ai-photo.jpg" alt="Sample Image" class="featured-image" />
  </section>

  <footer id="page-footer">
    <p>© 2025 My Webpage</p>
  </footer>
</body>
</html>
/* Apply a different font and base styles */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: black;
  color: black;
  margin: 0;
  padding: 0;
}

/* ID selector for header */
#main-header {
  background-color: purple;
  color: black;
  padding: 30px;
  text-align: center;
}

/* Class selector for titles */
.title {
  margin: 0;
  font-size: 2em;
}

/* Class selector for section content */
.content {
  padding: 30px;
  margin: 20px;
  background-color: pink;
  border: 2px solid #ddd;
  border-radius: 8px;
}

/* Another class for paragraph */
.intro {
  font-size: 1.1em;
  line-height: 1.6;
  margin-bottom: 20px;
}

/* Style an image */
.featured-image {
  width: 100%;
  max-width: 300px;
  border: 4px solid #007acc;
  padding: 5px;
  border-radius: 10px;
}

/* Footer styling using an ID */
#page-footer {
  background-color: #eee;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
  font-size: 0.9em;
  color: #555;
}

