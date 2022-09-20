# 19-Progressive-Web-Applications-PWA-Text-Editor

## Description:

A text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria.
Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.
The application will also function offline.

## User Setup: // need to udpate!

To use this at home, in your terminal run the following commands to invoke the application:
`npm i` to install packages,
then `npm run start` starts the live server.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Screenshots:

![image](./assets/images/)

## Links:

- GitHub: https://github.com/NessJade96/19-Progressive-Web-Applications-PWA-Text-Editor
- Heroku:

## planning notes:

1. Go through the criteria

- add the npm stripts
- bundle the files using webpack
  -this should generate HTML file, servicer worker, and a manifest file
- functionality working when using es6 js (spread etc)
- IndexedDB to be immediately created when the app is opened
- Auto saving / updating content
- data to be saved into the indexedDB so it can be retrieved if app closed and offline.
- installable app
- register a service worker to run on app startup using workbox
- service worker to have preset static assets pre cashed when loading relative pages
- ensure it deloys to heroku properly - test it offline!

## Commit notes:

1. Copy starter code for folder setup, and created readme.md.

2. Wrote some planning notes, added the db get and update methods in the src/js/database.js file. Added in the click handler functions to the client/install.js. Added in workbox plugins for a service worker and manifest files, and added in css loaders and babel to webpack into the client/webpack.config.js. Moved the gitignore outside of the client and into the root folder. Wrote the npm scripts into the package.json

3. updated the manifest in the sclient webpack.config.

Thank you :)
By Vanessa
