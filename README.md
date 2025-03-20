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





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <style>
        /* General body styling */
        body {
            font-family: Century Gothic, sans-serif;
            background-color: blue;
            color: black;
            margin: 27px;
            padding: 31px;
        }

        /* Styling the header */
        .header {
            text-align: left;
            background-color: black;
            color: white;
            padding: 23px;
            border-radius: 15px;
        }

        /* Paragraph styling */
        .description {
            font-size: 19px;
            line-height: 1.4;
            margin-bottom: 19px;
        }

        /* Image styling */
        #styled-image {
            width: 240px;
            border: 5px solid;
            padding: 15px;
            display: block;
            margin: 23px auto;
            border-radius: 9px;
        }

        /* Footer styling */
        .footer {
            text-align: right;
            margin-top: 27px;
            padding: 10px;
            background-color: green;
            color: white;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Tonny Onwonga Website</h1>
    </header>

    <section>
        <p class="description">Tonny Onwonga Styling has been applied</p>
        <img id="styled-image"C:\Users\Tonny.Onwonga\Pictures" alt="Tonny Profile Picture">
    </section>

    <footer class="footer">
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
</html>

