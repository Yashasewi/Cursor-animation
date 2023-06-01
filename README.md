# Animation README

## Overview

This repository contains an HTML and CSS code for creating a simple animation with a moving circle and text. The animation responds to user interactions by changing the size of the circle and updating its position based on the user's mouse movements.


## Table of Contents

- [Overview](#overview)
- [Demo](#demo)
- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Themes](#themes)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [License](#license)

## Demo

You can view a live demo of the animation [here](https://yashasewi.github.io/Cursor-animation/).


## Themes

<i>You have multiple themes to choose from by pressing the right and left arrow keys.</i>

## Prerequisites

To run this animation, you need a web browser that supports HTML5 and CSS3.

## Getting Started

1. Clone this repository or download the HTML and CSS files.
2. Open the `index.html` file in your preferred web browser.

## Usage

The animation consists of a circle and text displayed on a black background. The circle responds to user interactions as follows:

- When the mouse hovers over the circle, it increases in size.
- When the mouse leaves the circle, it returns to its original size.
- The position of the circle is updated based on the user's mouse movements.

## How It Works

The animation is achieved using JavaScript and CSS. Here's a breakdown of how it works:

1. The HTML structure contains a `div` element with the class `content`, which represents the main content area.
2. Inside the `content` element, there is another `div` element with the classes `d-flex`, `circle`, and `text`. The `circle` class represents the circle element, and the `text` class represents the text content.
3. The CSS styles in the `style.css` file define the appearance and behavior of the animation. It sets the initial styles for the circle, text, and overall layout.
4. In the JavaScript code, a clone of the `content` element is created and assigned to the `content` variable. This clone is given the class `d-absolute`, which positions it absolutely on the page.
5. The text and background colors for the cloned element are set using CSS custom properties.
6. The cloned element is appended to the body of the page, creating a duplicate of the original content element.
7. Event listeners are added to the child elements of the original content element. When the mouse hovers over the circle, the size of the cloned element increases. When the mouse leaves the circle, the size of the cloned element returns to its original size.
8. An event listener is added to the window to update the position of the cloned element based on the user's mouse movements. The position is calculated relative to the window's dimensions and set using CSS custom properties.

## Customization

You can customize the appearance of the animation by modifying the CSS styles in the `style.css` file. Here are some variables you can adjust:

- `--text-color`: Change the color of the text.
- `--background-color`: Change the background color.
- `--size`: Adjust the initial size of the circle.

## Dependencies

The animation relies on the following external resources:

- [Google Fonts](https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&display=swap): The Poppins font is used for the text.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore and modify the code to suit your needs. Enjoy the animation!
