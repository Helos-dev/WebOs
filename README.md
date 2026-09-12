# HelosOS

HelosOS is a small web OS that runs in the browser.

I made this project to try and make a simple operating system looking website using only HTML, CSS and JavaScript.

It is not a real operating system, but it tries to give you a small desktop with some basic apps.

## Features

* Desktop
* Clock
* Movable windows
* About app
* Notes app
* Calculator
* Desktop icons
* Dark/futuristic interface

## Apps

### About

The About window gives some basic information about HelosOS.

You can move the window by dragging the top part and close it with the `x` button.

### Notes

The Notes app has some example notes.

You can click a note from the left side and see the content on the right.

The notes are currently saved inside the JavaScript code, so they are not saved when you close the page.

### Calculator

A simple calculator for basic operations.

It supports:

* Addition
* Subtraction
* Multiplication
* Division
* Decimal numbers

Nothing too special, just a small calculator inside the OS.

## How it works

HelosOS is made with normal web technologies:

* HTML
* CSS
* JavaScript

There are no big frameworks used for the desktop.

The windows are just HTML elements which are moved using JavaScript.

When you click an icon, the related window opens. Clicking it again closes the window.

## Project structure

```text
HelosOS/
│
├── index.html
├── home.html
│
├── img/
│   ├── ic1.svg
│   ├── ic2.svg
│   └── ic3.svg
│
└── README.md
```

## Running HelosOS

You can just download the project and open the HTML file with a browser.

You can also use something like VS Code Live Server if you prefer running it from a local server.

For example:

```bash
git clone https://github.com/Helos-dev/WebOs.git
```

Then open the project and start `index.html`.

## Why I made it

The main reason was just to experiment with HTML, CSS and JavaScript.

I wanted to see if I could make a webpage that feels a bit like a real desktop without using a framework or making things too complicated.

There is still a lot that can be improved, but thats also part of the project.

## Future

Some things I might add in the future:

* File manager
* More apps
* Settings
* Better notes
* Terminal
* Music player
* Themes
* More customization
* Better mobile support

I don't know yet which ones I will actually add.

## Note

HelosOS is not a real OS.

It is a web project that looks and behaves a little bit like an operating system. It does not control the computer or manage files and hardware like Windows or Linux.

## Author

Made by **Helos**.

Just a small project made for experimenting with web development.
