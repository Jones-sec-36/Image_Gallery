# Ex.08 Design of Interactive Image Gallery

## Date:17.12.2024

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>image Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        Masters Gallery
    </header>

    <div class="gallery-container">
        <!-- Replace with valid static paths to your images -->
        <img src="images (3).jpeg" alt="Amethyst">
        <img src="download (2).jpeg" alt="Crystal">
        <img src="download.jpeg" alt="Emerald">
        <img src="images (1).jpeg" alt="Opal">
        <img src="images (2).jpeg" alt="Pink Quartz">
        <img src="images.jpeg" alt="Ruby">
    </div>

    <footer>
        &copy; 2024 Masters Gallery
    </footer>

</body>
</html>
```
style.css

```
/* Apply box-sizing for consistent padding/margin */
*,
*::before,
*::after {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
    background-color: black; /* Background color */
    color: gold; /* Text color */
    font-family: 'Cursive', Arial, sans-serif; /* Cursive font fallback */
    text-align: center;
}

header {
    font-size: 48px; /* Large font size */
    font-weight: bold; /* Bold text */
    margin: 20px 0;
}

.gallery-container {
    display: flex;
    overflow-x: auto; /* Enable horizontal scrolling */
    gap: 40px; /* Space between images */
    padding: 20px;
    scroll-behavior: smooth; /* Smooth scrolling */
}

.gallery-container img {
    height: 150px; /* Fixed height for images */
    width: auto; /* Maintain aspect ratio */
    border-radius: 8px;
}

footer {
    text-align: center;
    padding: 10px 0;
    color: gold;
    background-color: #222;
}
```

## OUTPUT
![alt text](<Screenshot 2024-12-17 135315.png>)

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
