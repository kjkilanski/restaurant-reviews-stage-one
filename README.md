# Project Overview: Stage 1

The **Restaurant Reviews** projects, incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, a static design that lacks accessibility is converted to be responsive on different sized displays and accessible for screen reader use. A basic service worker is also added in order to begin the process of creating a seamless offline experience for users.

## Project Scenario

Code for a restaurant reviews website was provided. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. The goal was to update the code to resolve these issues while still maintaining the included functionality.

## Instructions for Viewing Locally

1. In the project folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this. You don't need to know Python and for most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`

## Dependencies

1. This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/).

## Responsive Design

The game has been styled to play on both desktop computers and phones with a screen size of 320px and above. The game has been tested in Google Chrome and Firefox for these devices:

1. Nexus 5
2. Galaxy S5
3. Pixel 2
4. Pixel 2XL
5. iPhone 5/SE
6. iPhone 6/7/8
7. iPhone 6/7/8 Plus
8. iPad
9. iPad Pro

## Resources

There were several resources I used to complete this project. The most notable and helpful were the following:

1. MDN: https://developer.mozilla.org/
2. Service Worker: https://developers.google.com/web/fundamentals/primers/service-workers/
3. ARIA: https://www.w3.org/TR/wai-aria-1.1/#aria-hidden
4. ARIA: https://www.w3.org/TR/wai-aria-practices
3. w3schools: https://www.w3schools.com
4. CSS-Tricks: https://css-tricks.com/


