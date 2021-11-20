# A Modern Sass Site Boilerplate

This is a Sass boilerplate designed to get you up and running as quickly as possible. It is organized using the 7-1 folder structure popularized by [Hugo Giraudel](https://github.com/HugoGiraudel/sass-boilerplate). This boilerplate is meant as a general starting point for building your Sass-based site. Feel free to remove any content you don't want and update the things you do!

## Included

- Mixins & placeholders with common styles which you likely use all the time
- Variables for colours, UI, and breakpoints
- Easy to use utility class generator
- Useful collection of CSS resets to keep styles consistent

## Usage

This boilerplate assumes a few things:

- You are using [Visual Studio Code](https://code.visualstudio.com/) and are using the [Live-Sass Compiler](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass) extension
- By default, the stylesheet linked in the `index.html` file is `app.min.css` in the `scss` folder (please change as per your setup, and change your settings in VS Code for Sass Compiler to include a minified file)
- Breakpoint variables are used with `max-width`, so this is a desktop first approach (rearrange content as you shrink down). I've grown to prefer this approach as with things like `flex` and `grid`, creating a responsive layout has never been easier. Feel free to switch to `min-width` for a mobile first approach if you like.

## JavaScript

- As of September 19, 2020, I no longer include a package.json file. Some very useful (and most commonly used) packages to include are:
- [ESLint](https://github.com/eslint/eslint), [Babel](https://github.com/babel/babel), [Webpack](https://github.com/webpack/webpack), & [Jest](https://github.com/facebook/jest)

## .gitignore

- Also included is a pre-configured .gitignore file which uses the suggested template by GitHub themselves, specifically their [Node](https://github.com/github/gitignore/blob/master/Node.gitignore) template. To see the full collection, go [here](https://github.com/github/gitignore).
