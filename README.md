<p align="center">
  <img src="http://i.imgur.com/cRTWaNW.png" width="100%" />
</p>

# Unsplash Wallpapers
A simple menubar app for Mac, Windows and Linux that brings stunning wallpapers from Unsplash right to your desktop.

This project is an unofficial cross-platform version of [Unsplash Wallpapers](https://unsplash.com/wallpaper#mac-app) official application for Mac with more features.


## Demo

#### Mac:
<img src="http://i.imgur.com/aGjfvmE.gif" width="500px" />


#### Other platforms demo: <a href="http://i.imgur.com/5FAB6d8.gif" target="_blank">Windows</a> | <a href="http://i.imgur.com/lBDtKrc.gif" target="_blank">Linux</a>


## This project implemented by the following technologies:
* [Electron](https://github.com/electron)
* [React](https://github.com/facebook/react)
* [Redux](https://github.com/reduxjs/redux)
* [redux-saga](https://github.com/redux-saga/redux-saga)
* [styled-components](https://github.com/styled-components/styled-components)
* [axios](https://github.com/axios/axios)
* [wallpaper](https://github.com/sindresorhus/wallpaper)
* [electron-json-storage](https://github.com/electron-userland/electron-json-storage)
* [immutable-js](https://github.com/immutable-js/immutable-js)
* [Flow](https://github.com/facebook/flow)
* [ESLint](https://github.com/eslint/eslint)


## Features:
* Automatic update capability (On The Fly)
* Work on any popular operating systems like Mac, Windows, and Linux.
* Get high quality wallpapers from [Unsplash](https://unsplash.com).
* Save history of set wallpapers.
* Automatic set wallpapers daily or weekly (optional).
* Run at startup system (optional).
* Dark mode (optional or auto by Mojave appearance on Mac).
* Download directly every wallpaper.
* Link to photographer profile on [Unsplash website](https://unsplash.com).


## Let's run:

#### Clone the project:
```bash
$ git clone https://github.com/soroushchehresa/unsplash-wallpapers.git unsplash-wallpapers
```

#### Starting Development:

First, place your [Unsplash access key](https://unsplash.com/developers) in the `.env`:
```sh
UNSPLASH_ACCESS_KEY=your_access_key
```

Then, run one of the following commands:
```bash
$ yarn && yarn dev

# OR

$ npm i && npm run dev
```


#### Packaging for Production:

First, change `package.json => build => publish => owner` to your GitHub username.

Second, place following variables in the `.env`:
* `UNSPLASH_ACCESS_KEY` - Your [Unsplash access key](https://unsplash.com/developers)
* `GH_TOKEN` - Your GitHub token to publish the release
* `CSC_LINK` - Path or link to your Apple Mac developer certificates (just for packaging on Mac)
* `CSC_KEY_PASSWORD` - Your Apple Mac developer certificate password (just for packaging on Mac)

Then, run one of the following commands:
```bash
$ yarn && yarn package

# OR

$ npm i && npm run package
```
