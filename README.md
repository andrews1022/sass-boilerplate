# Maple - A Basic Sass Site Boilerplate
Maple is a basic Sass site/file/folder structure designed to get you up and running as quickly as possible. It is organized using the 7-1 folder structure popularized by [Hugo Giraudel](https://github.com/HugoGiraudel/sass-boilerplate). This site structure is meant as a general starting point for building your Sass based site. Feel free to remove any content you don't want need and update the things you do!

It includes:
+ 3 helpful mixins to get you started 
+ A few simple placeholder stylings for basic stylings (flex, grid, absolute centering, etc.)
+ Variables for color, UI, and breakpoints
+ Easy to use functions to use for colors & sizing
+ Border box reset
+ Responsive images reset
+ Anchor tags and list reset (no underline and no bullets)

## Usage / Notes
This site structure assumes a few things:
+ You are using Visual Studio Code and are using the Live-Sass Compiler extension
+ By default, the stylesheet linked in the index.html file is main.scss in the sass folder (please change as per your setup)
+ UPDATED: Now includes a main.min.css file (chang your settings in VS Code for Sass Compiler to include minified file)
+ You are building your site with a mobile-first approach (breakpoint variables use min-width - this framework assumes you are starting at 320px wide for small mobile then going up from there)

## Variables
Included variables are:
+ Basic black & white colors
Primary, secondary, tertiary, and quaternary colors (all set to white by default - don't forget to change!)
+ Simple UI based variables for nice subtle styling
+ Variables for breakpoints at numerous widths. **NOTE** Use interpolation to activate.

## Also included
+ Folders for Fonts, Images, JavaScript, HTML pages, and Videos

## Included JavaScript Utilities
_(Run `npm install`)_
+ ESLint & Prettier 
+ Jest

_(Local file included)_
+ HTML5 Shiv 
+ Respond
+ Selectivizr
