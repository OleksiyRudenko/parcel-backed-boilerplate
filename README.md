# ParcelJS and push-dir backed boilerplate

[![MIT Licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)

Develop and publish simple Vanilla JS web apps
with the least overheads.

Whenever you do not need any sophisticated
app building tools and feel ES5/ES6 Vanilla JS
and pure CSS sufficient you will benefit from
using this boilerplate. Just start coding right off.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [What's included](#whats-included)
- [Installation](#installation)
- [Workflow](#workflow)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
_TOC generated with [DocToc](https://github.com/thlorenz/doctoc)_

## What's included

* [ParcelJS](https://parceljs.org/)
  is a zero configuration web app bundler that supports
  [HMR](https://parceljs.org/hmr.html)
* [push-dir](https://www.npmjs.com/package/push-dir)
  is a tool to push built app to GitHub pages
* [shx](https://www.npmjs.com/package/shx)
  to run one-off shell commands in npm package scripts
  working well under *nix and MS Windows environments
  (dev dependency)
* [normalize.css](https://necolas.github.io/normalize.css/)
  to reset styles making browsers render all elements more
  consistently and in line with modern standards
  (imported from `./src/index.js`)
* [default-beauty.css](https://github.com/OleksiyRudenko/default-beauty.css)
  to make default styles a bit more beautiful than offered
  by browsers
  (imported from `./src/index.js`)
* `./src/index.html` with HTML5 compliant minimal content
  and inclusion of fonts to replace default plus
  [Font Awesome](https://fontawesome.com/) to have nice icons
* `./src/index.css` and `./src/index.js` to start coding with

Feel free getting rid of anything from the list above.

## Installation

Install **ParcelJS** and **push-dir** globally:

`yarn global add parcel-bundler && yarn global add push-dir`

Install required dependencies:

`yarn install`

## Workflow

1. Run `yarn start` to launch development server
   with HMR support.
1. Enjoy development benefiting from HMR
1.

