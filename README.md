# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

## How to download

+ We can download the scratch project from the udacity provided links.
+ The scratch code is downloaded using this link:<https://github.com/udacity/mws+restaurant+stage+1>
+ We must extract the downloaded scratch project.

## My map box key or token

+  I am used the map in the project using this link : `pk.eyJ1IjoiY2hhaXRhbnlhY2hpbm5pMTIzIiwiYSI6ImNqd3U5a3lxcDE1MjU0NHA1Y3hjbDR2dGkifQ.XajK4xFe_minj7jbGdpgPQ`.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

## My Project Overall Summary

+  In this project there are two html pages `index.html` and `Restaurant.html`.
+  In index page when we click on view details button it will goes to restaurant.html page there is a relation exists between these two html pages.
+  Mapbox is used to display the total map. The mapbox link was placed at the map-container.
+   service Worker is used to display the total project in offline mode.
+   For the usage of service worker we have to create the js file that js file scope is total project can access.
+   tabIndex is used to work the tab button when we press the tab button in keyboard it will selects all the buttons in the page.  
+   using media queries we can implement the project in mobile view and tablet view.

## Conclusion

+   By done this project we can improve our skills in usage of developer tools
+   process to done this project is very large
+   simple tasks takes more time to solve
+   by done this project we can know that many event listeners and about tabIndex
+   when working with this project we can know about server status and server running in command prompt
