# Ionic Vue Slide

* App to display an image on a simple Ionic card, using [Vue](https://vuejs.org/) with Ionic from [Ionic/vue v0.0.4](https://www.npmjs.com/package/@ionic/vue) & [@ionic/core](https://www.npmjs.com/package/@ionic/core) npm modules
* From tutorial: [Paul Halliday: Youtube video: Ionic 4 - Angular, React and Vue.js](https://www.youtube.com/watch?v=eQTNqtVeTgE)

## Table of contents

* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

* Solution to error message `export ‘ICON_PATHS’ was not found in ionicons/icons` is to edit the file `node_modules/@ionic/vue/dist/ionic-vue.esm.js` and search for `ICON_PATHS`. Comment out both lines - this solves the problem by making sure `ICON_PATHS` is not found
* Vue app created using Vue CLI then ionic dependencies added

## Screenshots

![screen print](./img/slide.png)

## Technologies

* [Ionic/vue v0.0.4](https://www.npmjs.com/package/@ionic/vue)
* [@ionic/core](https://www.npmjs.com/package/@ionic/core) npm ionic components module
* [Vue v2.6.11](https://vuejs.org/)

## Setup

* Load dependencies using `npm i`
* To start the server on _http://localhost:8080/_ type: 'npm run serve'

## Code Examples

* N/A

## Features

* N/A

## Status & To-do list

* Status: working.
* To-do: add functionality

## Inspiration

* [Paul Halliday: Youtube video: Ionic 4 - Angular, React and Vue.js](https://www.youtube.com/watch?v=eQTNqtVeTgE).

## Contact

Repo created by [ABateman](https://www.andrewbateman.org) - feel free to contact me!
