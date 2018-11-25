# ParcelJS and push-dir backed boilerplate

Built using [Parcel backed boilerplate](https://github.com/OleksiyRudenko/parcel-backed-boilerplate)

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
- [Contributions](#contributions)

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

[_^ Up to TOC ^_](#table-of-contents)

## Installation

You do not need to fork this repo unless you want to
[contribute to the project per se](#contributing).

Install **ParcelJS** and **push-dir** globally:

`yarn global add parcel-bundler && yarn global add push-dir`

Install required dependencies:

`yarn install`

On [GitHub](https://github.com/) create a new empty repository.
Do not initialize it with any files. Take a note of `.git` url.

On your machine at a location of your preference run

```
git clone https://github.com/OleksiyRudenko/parcel-backed-boilerplate.git <your-project-name>
cd <your-project-name>
rm -rf .git
git init
git add .
git remote add origin <your-project-repo-url.git>
```

Now you are ready to make your first commit.

Consider removing whatever is not relevant to your project
or changing files as appropriate before making initial commit
and pushing it to your remote.

Files to consider changes to:
 * `README.md` (please keep reference to this project on the top)
 * `CONTRIBUTING.md`
 * `index.html`
   (please, keep links to parcel-backed-boilerplate and default-beauty.css
   somewhere within the file)
 * `index.js`
 * `.github/*`
 * `.gitignore`

[_^ Up to TOC ^_](#table-of-contents)

## Workflow

1. Run `yarn start` to launch development server
   with HMR support.
1. Enjoy development benefiting from HMR
1. Once you ready to publish:
   1. Terminate the development server
   1. `yarn build` to build project
   1. `yarn push-gh-pages` to publish the build on GitHub pages

`yarn build-dev` will build project without any minification,
which may be useful for build debug purposes.

`push-gh-pages` requires git tree to be clean, so
either commit or stash your uncommitted changes.

[_^ Up to TOC ^_](#table-of-contents)

## Contributions

Contributions are welcomed. Please, check
[contribution notes](./CONTRIBUTING.md)

If you like this project and find it helpful,
please, give it a :star: on github.

[_^ Up to TOC ^_](#table-of-contents)
