# Maple - A Basic Sass Site Boilerplate
Maple is a basic Sass site/file/folder structure designed to get you up and running as quickly as possible. It is organized using the 7-1 folder structure popularized by [Hugo Giraudel](https://github.com/HugoGiraudel/sass-boilerplate). This site structure is meant as a general starting point for building your Sass based site. Feel free to remove any content you don't want need and update the things you do!

It includes:
- 11 mixins covering the basics
- 200+ variables to help you get started customizing your site
- A massive media query manager
- Border box reset
- Responsive images reset
- Anchor tags and list reset (no underline and no bullets)
- Custom text selection highlight (can be removed if not desired)
- Responsive text sizes for optimal readability and size on all screen sizes
- Normalize CSS & Skeleton CSS are included if you wish to use them (NOTE: these are NOT imported by default)

## Usage / Notes
This site structure assumes a few things:
- You are using Visual Studio Code and are using the Live-Sass Compiler extension
- By default, the stylesheet linked in the index.html file is main.scss in the sass folder (please change as per your setup)
- You are building your site with a mobile-first approach (this media query manager uses min-width)

### Media Query Manager (MQM)
This manager assumes a mobile first approach. Some things to note about using this structure:
- Styles by default are done for min-width 360px (small mobile). This makes it much easier to scale up from there.
- We use ems instead of pixels for screen width, in case the user has changed their default browser font settings.
- As explained in the Sass file, the default browser font-size is 16px. So, we take the width of the screen we are styling for and divide it by 16, which gives us our em value
    - For example: tab-land (1024px) / 16px = 64em, and so on
- Included in the html selector as well are some basic font-size increases, to hopefully save you time as the screen size gets bigger. There will, of course, needed to be more specific styling done, but this was done to hopefully save a bit of time by covering the whole site at once
- The MQM by default has settings for up to and including 4k resolution

### Mixins
Added are some mixins for:
- Clearfix
- Centering an absolute positioned element both horizontally and vertically
- Responsive Images reset
- Default font stylings for the body element
- Custom text selection based on the set primary-color
- Border box reset for the * and html selectors
- Hiding text/elements while making it readable for screen readers
- Character limit on paragraphs designed for maximum clarity & readability
- Horizontally and vertically center your flexbox container

### Variables
Included variables are:
- Basic black & white colors
- 15 shades of grey, providing a nice variety of options
- Primary, secondary, tertiary, and quaternary colors (all set to white by default - don't forget to change!)
- Flat UI Colors from the default palette by [Flat UI Colors](https://flatuicolors.com/palette/defo). Also included are light and dark version of each colors
- Border-radius (small amounts, intended for nice round corners on an element)
- Text decoration (no underline on links included by default)
- List style reset (no bullets included by default)
- Line-height
- Font-family
- Wrapper sizes (width)
- Centering a block element with 'margin: 0 auto;'
- Font weights (naming styles based off Google Fonts)
- Default font sizes for the html selector
- General rem sizes (can be used for anything, font, margin, padding, etc., and in any direction)
- Transitions (including a default, and quick-slow timings - can be modified to your liking)
- 20+ cubic bezier timing functions from [easings.net](https://easings.net/en).
- Multiple box shadow settings, ranging from extra-light to heavy

## Also included
- Folders for CSS, Images, JavaScript, HTML Pages, & Video
- Included are two cute pictures of a puppy and kitty. Can't leave that folder empty!

This will be updated over time, once I learn more web development skills and techniques! I hope this helps you with your projects!

## UPDATE: August 11, 2019: ESLint and Prettier Added!
ESLint and Prettier added! Simply run `npm install` to get the necessary packages. Included in the 'js' folder is a quick line of code. After running `npm install`, you should get some warnings from ESLint/Prettier.