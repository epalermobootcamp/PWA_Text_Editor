# PWA_Text_Editor

## Technologies

![Technologies](https://img.shields.io/badge/-Git-F05032?logo=Git&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-Babel-F9DC3E?logo=Babel&logoColor=white)
![Technologies](https://img.shields.io/badge/Webpack-8DD6F9?logo=Webpack&logoColor=white)
![Technologies](https://img.shields.io/badge/Heroku-430098?logo=Heroku&logoColor=white)

## Description

J.A.T.E is a Progressive Web Application (PWA) that runs in the browser, offline and can be installed locally to your machine. This application features a number of data persistence techniques, insuring the application runs regardless of browser supported function. J.A.T.E uses an IndexedDB database and the idb package. This application is deployed to Heroku, to access it in production continue reading the documentation!

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation

This application is deployed to [Heroku](https://intense-anchorage-21775-f2f6006d01b7.herokuapp.com/).

To run J.A.T.E locally:

    1. Pull down and/or branch this repository
    2. Run npm i to install all dependencies
    3. Invoke application with npm run start

## Screenshot

![App interface](./client/dist/assets/images/image%201.png)

![App manifest](./client/dist/assets/images/image%202.png)

## Heroku Link

A link to the [Heroku](https://intense-anchorage-21775-f2f6006d01b7.herokuapp.com):

```
https://intense-anchorage-21775-f2f6006d01b7.herokuapp.com

```

## Link

A link to the [code](https://github.com/epalermobootcamp/PWA_Text_Editor):

```
https://github.com/epalermobootcamp/PWA_Text_Editor
```

## Questions

If you have any questions about the repo, open an issue or contact me directly at [enrico.palermo@ymail.com](mailto:enrico.palermo@ymail.com).

![Avatar](https://avatars.githubusercontent.com/u/141057897?v=4&s=100)

Check out my other projects at [epalermobootcamp](https://github.com/epalermobootcamp)
