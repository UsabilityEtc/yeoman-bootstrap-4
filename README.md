# yeoman-bootstrap-4

A starter Bootstrap 4 website created with the [Yeoman Bootstrap 4 generator](https://github.com/bassjobsen/generator-bootstrap4).

## Getting Started

After cloning `yeoman-bootstrap-4`, run `npm install` and `bower install` to download the website's dependencies.

## Preview

Run `grunt serve` to view the website in a browser with the usual live reloading of changes.

## Building

Run `grunt build` to produce the `dist` folder that contains the combined and minified website files.

## Font Awesome

The `app/index.html` file contains a CDN link to the [Font Awesome](http://fontawesome.io) stylesheet to work around the issue of Font Awesome not being copied into the `dist` folder after running `grunt build` or `grunt serve:dist`.
