# Ruffle Example

This repository provides an example/demo of how to use Ruffle on your own website to emulate Flash content. Ruffle is an open-source Flash Player emulator that allows you to continue running Flash content in modern browsers.

Video Explanation: https://www.youtube.com/watch?v=TJXMGNxex24&t=81s

Stack Overflow Question: https://stackoverflow.com/questions/65465492/how-to-embed-ruffle-flash-player-emulator-into-html-file/65693128#65693128

## Prerequisites

Before getting started, make sure you have the following:

- A basic understanding of HTML, CSS, and JavaScript
- A text editor or integrated development environment (IDE) to modify the code
- A web server to host your website (you can use localhost for development purposes)

## Getting Started

To use Ruffle on your own website, follow these steps:

1. Clone or download this repository to your local machine.

```bash
git clone https://github.com/maddox05/ruffle-example.git
```
2. Open the index.html file in a text editor or IDE of your choice.
3. Locate the following section in the game HTML file:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="title" content="Ruffle Example">
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta name="language" content="English">
  <title>Ruffle Example</title>
  <script src="main.js"></script> 
  <noscript>Your browser doesn't have JavaScript enabled. Please enable JavaScript or switch to a browser that
    supports it.</noscript>
</head>
<body>
<div id='ruffle' class="gameloc"></div>
<script src='https://maddox05.github.io/ruffle-example/ruffle/index.js'></script> <!-- Theses files should be local -->
<script id = "gabe">swfobject.embedSWF("https://maddox05.github.io/ruffle-example/1on1soccer.swf", 'ruffle', 800, 600);</script> <!-- Theses files should be local -->
</body>
</html>

```
4. Replace "path/to/your/flash.swf" with the path to your own Flash content. Make sure the Flash file (SWF) is located in the specified path.
5. Save the changes to the index.html file.
6. Start a web server and navigate to the local website in your browser.
7. You should now see your Flash content rendered using Ruffle.

## Customization
Feel free to modify the HTML, CSS, and JavaScript code to suit your needs. You can change the layout, add more Flash content, or integrate Ruffle in different parts of your website.

## Compatibility
Ruffle is designed to work in modern browsers that lack built-in Flash support, such as Google Chrome, Mozilla Firefox, Microsoft Edge, and Safari. It is compatible with a wide range of Flash content, including animations, games, and interactive applications.

## Resources
For more information about Ruffle and its features, refer to the official Ruffle GitHub repository.

## License
This example website is licensed under the **MIT** License. Feel free to use, modify, and distribute it according to the terms of the license.


