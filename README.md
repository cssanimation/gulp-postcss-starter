# Starter for HTML/CSS/JS projects

Includes Gulp to process PostCSS into native CSS, with Browser Sync.

PostCSS plugins include:

* Autoprefixer
* Simple Vars
* Nested CSS

## Setup

Before starting, you'll need [Node](https://nodejs.org/) (which includes NPM).

If using OSX, I'd recommend this guide to [getting set up with Node and NPM](http://www.johnpapa.net/how-to-use-npm-global-without-sudo-on-osx/).

Then install Gulp using `npm install -g gulp`. This installs Gulp globally and is needed later.

Clone this repo to your local computer using this command:

    git clone git@github.com:cssanimation/gulp-postcss-starter.git starter

With the files downloaded, navigate to your `starter` folder on the command line (or Terminal) and run `npm install` to set things up.

If that doesn't work, it may be necessary to use `sudo npm install`.

With this set up, you should now be able to run:

    gulp

This will process any PostCSS styles files and launch a web browser showing the current files. Making changes to the files should result in the page updating automatically.

## Questions

Drop me a line at [hello@cssanimation.rocks](hello@cssanimation.rocks) with any questions or thoughts. Pull requests welcomed!

### License

MIT
