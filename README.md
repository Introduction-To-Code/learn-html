# Learn HTML

**HTML** is an easy language to learn and once you learn it you can make really cool things! **HTML** is used purely for websites. 👍

# The boilerplate of HTML

Always start with
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
</body>
</html>
```
That code is known as **boilerplate code**!
Let's cover this by explaining everything in the **boilerplate code**.
`<!DOCTYPE html>` tells the browser what type of HTML file it is, if it's not added the browser will automatically add it, because it's a needed line of code.
`<html>` is the entire file code wrapped around in it, it tells the browser that it is *html* code.
`<head>` is where you store the tab, meta and file linking information. Like linking your **CSS** file, changing the tab name, or using `meta` tags.
`<meta>` is the information for the website.
`<title>` is the tab name!
`<body>` is your canvas, where you place your **HTML** file contents.

# The basics of HTML

We talked about boilerplate code but what about the basics of HTML?
Let's learn about creating text, buttons, links and more!

### Creating text
Create a *header* with one of the following element tags:
* `<h1>`
* `<h2>`
* `<h3>`
* `<h4>`
* `<h5>`
* `<h6>`

You can also create text with `<p>` or `<span>`. To use all of these element tags for creating text you need then like this:
```html
<example>CONTENTS<example>
```
and replace `example` with the element tag name that you want to use.

### Creating buttons
To create a button use `<button>` like this:
```html
<button>Click Me</button>
```
Once you do this you'll have a basic button that says "Click Me". You can replace the *Click Me* with whatever text you want.

### Creating links
To create a link use `<a>` like this:
```html
<a href="#">I'm a link</a>
```
but now we're dealing with an ***attribute***! The ***attribute*** in question is `href`!
`href`'s value is `#`, you need to replace `#` with a *URL/link*. You can replace it with a social media link, etc. Any link you want!

# Linking CSS and JavaScript
In order to use **CSS** you need to *link* it in your `<head>` element. Using
```html
<link rel="stylesheet" href="style.css"
```
Replace `style.css` with your **CSS** file.

In order to use **JavaScript** you need to *link* it as well!
To call **JavaScript** *functions* in your buttons use the attribute `onclick` like this: 
```html
<button onclick="function()">Click me to execute a function</button>
```
Replace `function()` with your **JavaScript** *function name*.
To link your **JavaScript** put `<script src="script.js"></script>` below your button like this:
```html
<button onclick="function()">Click me to execute a function</button>
<script src="script.js"></script>
```

# Using images and videos
To use an image use `<img src="myimage.png">`, but replace `myimage.png` with your image (including file extension).
To use a video use `<video src="myvideo.mp4"></video>`, but replace `myvideo.mp4` with your image (including file extension).

# You're done!
You have learned so much about **HTML**!
You have learned the following topics:
* Boilerplate code
* The basics of HTML (creating text, links and buttons)
* How to link CSS and JavaScript
* Using images and videos
