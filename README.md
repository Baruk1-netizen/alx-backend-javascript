# Project Setup

## Install NodeJS 12.11.x

To install NodeJS 12.11.x, follow these steps:

1. Download the setup script and run it using `curl`, `bash`, and `apt`.
2. Verify the installation by checking the versions of `nodejs` and `npm`.

## Install Jest, Babel, and ESLint

In your project directory, install Jest, Babel, and ESLint by using the supplied `package.json` and running `npm install`.

## Configuration Files

Add the following configuration files to your project directory:

### `package.json`

<details>
<summary>Click to show/hide file contents</summary>

This file includes scripts for linting, development, testing, and full testing, as well as the necessary development dependencies.

</details>

### `babel.config.js`

<details>
<summary>Click to show/hide file contents</summary>

This file configures Babel to use the preset for the current Node.js version.

</details>

### `.eslintrc.js`

<details>
<summary>Click to show/hide file contents</summary>

This file configures ESLint with settings for browser, ES6, and Jest environments, extends Airbnb and Jest configurations, and includes custom rules.

</details>

## Final Steps

Don’t forget to run `npm install` from the terminal in your project folder to install all necessary project dependencies..