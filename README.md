# Animation Download Button Design

This repository contains code for an animated download button designed using HTML, CSS, and JavaScript. The button is created to facilitate the download of an animation displayed on the screen.

## Button Features
- **Background Image:** Utilizes a globe image from Google's Earth API.
- **Foreground Image:** A gradient that fades from black to the button's color, enhancing visual appeal.
- **Interaction:** The button triggers an on-click JavaScript function to initiate the download of the animation.

## Preview
![image](https://github.com/usmaniqbal-developer/Animation-Download-Button/assets/157515706/725a80d0-494e-4f09-bb7d-f03719c3d714)

## How to Use
1. Clone this repository to your local machine.
2. Open the `index.html` file in your browser.
3. Click the download button to initiate the animation download.

## Code Snippet

### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Animation Download Button</title>
</head>
<body>
<div class="container">

    <a href="" class="button">
        <ul>
            <li>&#68;ownload</li>
            <li>&#68;ownloading</li>
            <li>Open File</li>
        </ul>
        <div>
            <svg viewBox="0 0 24 24"></svg>
        </div>
    </a>

    <a href="" class="button dark-single">
        <div>
            <svg viewBox="0 0 24 24"></svg>
        </div>
    </a>

    <div></div>

    <a href="" class="button white-single">
        <div>
            <svg viewBox="0 0 24 24"></svg>
        </div>
    </a>

    <a href="" class="button dark">
        <ul>
            <li>&#68;ownload</li>
            <li>&#68;ownloading</li>
            <li>Open File</li>
        </ul>
        <div>
            <svg viewBox="0 0 24 24"></svg>
        </div>
    </a>

</div>

<!-- HTML Coding Part -->

    

<a class="dribbble" href="https://dribbble.com/shots/7299868-Download-Buttons" target="_blank">
    <img src="https://cdn.dribbble.com/assets/dribbble-ball-mark-2bd45f09c2fb58dbbfb44766d5d1d07c5a12972d602ef8b32204d28fa3dda554.svg" alt="">
</a>

  <script src='https://s3-us-west-2.amazonaws.com/s.cdpn.io/16327/gsap-latest-beta.min.js'></script><script  src="./script.js"></script>

</body>
</html>

