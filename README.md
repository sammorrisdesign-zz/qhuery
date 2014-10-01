Qhuery
=======

A stupid sass experiment with colours. It generates 36000 media queries that change the body's background colour. There's no real point to it, but you've gotten this far so you must be curious. You're probably looking for [`queries.scss`](scss/queries.scss) or [`queries.css`](queries.css).

## Demo

Visit the [live site](http://www.qhuery.com) (Warning, might kill your browser). Here's a gif preview just in case.

![Preview](preview.gif)

## Requirements

- Ruby 1.9.2
- [Node](nodejs.org) with the latest version of Node Package Manager
- [Grunt](http://gruntjs.com/)

## Usage

For the first time use `npm install` to get dependencies and then run `grunt` to watch the sass.

This doesn't include the actual queries generated from `queries.scss` as this can take up to 40 minutes to compile. As a result the page loads in two stylesheets `queries.css`, which comes with the repo already compiled, and `style.css`, which features any extra page styling.
