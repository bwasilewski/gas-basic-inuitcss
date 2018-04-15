# Build Starter with Inuit CSS

This is a "fork" of [Build Starter](https://github.com/bwasilewski/build-starter) which replaces Bootstrap with [Inuit CSS](https://github.com/inuitcss/inuitcss).

## Features

- :fireworks: SASS compilation/minification and sourcemaps
- :fire: HTML templating with Nunjucks
- :sparkler: Browserify for frontend dependencies
- :boom: JavaScript linting, minification and sourcemaps
- :star: Live reloading and device mirroring with BrowserSync


## Getting started

To get started, run the following commands (libjpeg and libpng needed for image processing):

```
$ git clone https://github.com/bwasilewski/build-starter.git
$ cd build-starter
$ yarn install
$ brew install libjpeg libpng
$ gulp
```

That's it!

## Deployment

Currently, there are no gulp tasks configured to address the task of deployment to a production environment. Currently, the easiest way to deploy these projects is via [Surge.sh][109e8be1] or [Github Pages][e3ed3e6e]. Visit their respective sites for instructions on how they should be used.

  [e3ed3e6e]: https://pages.github.com/ "Github Pages"



  [109e8be1]: http://surge.sh "Surge"
