# Contributing to Kumiko

## Initial Steps:

1. Fork this repository and clone it to your local machine
2. Make sure you have `yarn` installed. If you don't, run `npm install -g yarn`
3. Install all packages with the `yarn` command in the project root.

## Development:

Kumiko is written in [Sass](https://sass-lang.com/) and should be run in a browser environment. We highly recommend you use [VSCode](https://code.visualstudio.com/) as your IDE when developing.

### Yarn Scripts

- `dev` - This script builds the codebase and watches for changes into a distribution bundle.
- `build` - This script builds the codebase into a minified distribution bundle.
- `cleanup` - This script uses [Prettier](https://prettier.io/) to format the codebase.
- `release` - This script runs the aformentioned scripts and publishes the project on NPM

### Iterating

You can create a `test.html` file at root to test changes in realtime. We recommend using `live-server` to hot-reload the webpage on change, and edit as necessary.

Below is a sample for a Kumiko starter:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="./dist/kumiko.min.css" />
  </head>
  <body>
    <!-- Your code here -->
  </body>
</html>
```

## Next Steps + Useful Info:

- We are using Yarn as our package manager, please do not commit your `package-lock.json` files from NPM
- Make sure you are upto date by doing `git pull` here and there.
- Submit a <a href="https://github.com/melindachang/kumiko/pulls">pull request</a>!
