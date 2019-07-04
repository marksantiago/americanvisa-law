# [americanvisa.law](https://americanvisa.law/)

Files for the americanvisa.law website.

* The development code is in the [`src/`](src) directory.
* The build process relies on `npm scripts`.

Boilerplate code taken from the following:

* [html5boilerplate.com](https://html5boilerplate.com/),
* [Sass Boilerplate](https://github.com/HugoGiraudel/sass-boilerplate),
* [npm-build-boilerplate](https://github.com/damonbauer/npm-build-boilerplate),
* [Dave Gamache's Skeleton Framework](http://getskeleton.com),
* and [Seth Coelen's Skeleton-Sass version of the Skeleton Framework](https://www.sethcoelen.com/).

## Setup

### 1. Have at least [node](https://nodejs.org/en/) `v6.x.x` installed.

### 2. Clone this repo:

`git clone https://github.com/marksantiago/americanvisa-law.git`

`cd americanvisa-law`

### 3. Install everything in `package.json`:

`npm install`

## Development

Do all development work in the [`src/`](src) directory.

## Tasks

All available tasks can be found in the [`package.json`](package.json) file in the `scripts` object.

### `clean`
  `npm run clean`

  Delete existing compiled code.

### `start`
  `npm run start`

  Start over from scratch. Deletes the `dist` folder, copies `src` to `dist`, and reruns the `build` and `watch` commands.

### `serve`
  `npm run serve`

  Start a new server and watch for any file changes in the `dist` folder.

### `build`
  `npm run build`

  Run all of the `build` commands simultaneously.

### `watch`
  `npm run watch`

  Run the `serve` and `watch` commands simultaneously.
