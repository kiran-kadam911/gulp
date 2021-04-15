# Gulp
Modular gulp tasks for compiling, linting & image optimization.

## Pre-requisites
Before starting, ensure that you are using at least the latest LTS release of
Node.js, once Node.js has been installed, we recommend to run

To install the required packages use
```
npm install
```

## Working on CSS
  - The project uses [PostCSS](https://postcss.org/) for managing variables and
provide the needed browser support.
  - With extension `.css` we can use SCSS/Post-CSS syntax or features.
  - Included RTL feature which convert LTR CSS to RTL for directional css.
  - Included CleanCSS & Auto-prefixer.

## Working on Javascript
The project uses [ES6](https://es6.io/) for managing javascript with the `Drupal.behaviors` code standard.

## Linting JS and CSS
Linting Javascript and CSS files along with fix Linting Errors & formatting.

## Images
The images designated for your custom theme can be placed in the `images/` folder. We have gulp task to optimized images.
