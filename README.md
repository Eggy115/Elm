# Elm
Elm is a functional programming language used for building web applications. Here's an example of a "Hello, World!" program in Elm:

Install Elm on your machine by following the instructions on the Elm website.

Create a new file named "Main.elm" and add the following code:

```elm
module Main exposing (..)

import Html exposing (text)

main =
    text "Hello, World!"
This program defines a module named "Main" that imports the text function from the Html module. The main function creates a text node containing the "Hello, World!" message.
```

Compile the Elm program by running the following command in your terminal:

```css
elm make Main.elm --output=main.js
```

This command will generate a JavaScript file named "main.js" that contains the compiled Elm code.

Create a new HTML file named "index.html" and add the following code:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
    <script src="main.js"></script>
</head>
<body>
</body>
</html>
```

This file imports the compiled Elm code from the "main.js" file and includes it in the HTML page.

Open the "index.html" file in a web browser to see the "Hello, World!" message displayed on the page.

When this program is compiled and run in a web browser, it will display the "Hello, World!" message on the page.
