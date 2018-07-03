# Parcel Starter

> A starter template for Parcel, ECMAScript(latest), sass and postcss.

## Table of Contents

* [Features](#features)
* [Installation](#installation)
* [Getting Started](#getting-started)
* [List of Npm tasks](#list-of-npm-tasks)

## Features
This starter also features a number of great software (in the words of their creators):

* [Parcel](https://parceljs.org/) - blazing fast, zero configuration web application bundler.
* [EditorConfig](http://editorconfig.org/) - a config file for maintaining  consistent coding styles.

### JavaScript

* [Babel](http://babeljs.io/) - a JavaScript compiler for es5 to es6/7.
* [ESLint](http://eslint.org/) - the pluggable linting utility for JavaScript and JSX (with preconfigured ruleset by [Google](https://github.com/google/eslint-config-google).

### StyleSheet

* [Sass](http://sass-lang.com/) - CSS with superpowers.
* [PostCSS](https://github.com/postcss/postcss) - a tool for transforming styles with JS plugins.
* [Autoprefixer](https://github.com/postcss/autoprefixer) - adding vendor prefixes by the rules of [Can I Use](http://caniuse.com/).
* [Stylelint](http://stylelint.io/) - a mighty, modern CSS linter (with preconfigured ruleset by [Hugo Giraudel](https://sass-guidelin.es/)).

### Git Hooks manager

* [husky](https://github.com/typicode/husky)
* [lint-staged](https://github.com/okonet/lint-staged)

## Installation

### Node version manager

Install [NVM](https://github.com/creationix/nvm). And use the latest version of NodeJS.

```bash
nvm install node
nvm use node
```

### Install Sass

Go to [sass-lang.com/install](http://sass-lang.com/install) for installation in command line.

```bash
gem install sass
```

Before install sass, you should [install Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [install Gem](https://rubygems.org/pages/download).

## Getting started

1. Clone this Boilerplate

   ```bash
   git clone https://github.com/thecreation/parcel-starter.git <PROJECT_NAME>
   cd <PROJECT_NAME>
   ```

2. Install Dependencies

   ```bash
   npm install
   ```

3. Build the project

   ```bash
   npm run build
   ```

4. Stay up-to-date

   ```bash
   git remote add upstream https://github.com/thecreation/parcel-starter.git
   git pull upstream master
   ```

## List of Npm tasks

To run separate task type in command line `npm run [task_name]`.

Task name          | Description
:------------------|:----------------------------------
`start`            | run the app in develpment.
`build`            | build the app for production to the `dist` folder.
`clean`            | remove `dist` folder.

## License

The code is available under the [MIT](https://github.com/thecreation/parcel-starter/blob/master/LICENSE) license.
