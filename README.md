## Envoy Code Test

#Master Branch
Contains Slider with commented out optional Hero

#Hero Branch
Contains optional Hero that would replace Slider feature

///

[Bourbon] is a library of [Sass] mixins and functions that are designed to make
you a more efficient style sheet author.

[Neat] is a fluid grid framework with the aim of being easy enough to
use out of the box and flexible enough to customize down the road.

  [Bourbon]: http://bourbon.io/
  [Neat]: https://neat.bourbon.io/
  [Sass]: http://sass-lang.com

## Installation

1. Clone the repository, and open a shell terminal within the project's root
   directory.

1. After [installing Node.js and NPM], install the gulp via the following.

   ```
   npm install --global gulp-cli
   ```

1. Install the project packages.

   ```
   npm install
   ```

1. Run the default `gulp` command which will complie the stylesheets, with
   Bourbon and Neat inclded as well as creating a local server at
   [`http://localhost:8000`](http://localhost:8000). Gulp will continue to watch
   the `/stylesheets` to monitor for any changes.

   ```
   gulp
   ```


[installing Node.js and NPM]: https://docs.npmjs.com/getting-started/installing-node/

## License

`gulp-bourbon-neat-example` is copyright © 2012 [thoughtbot, inc.][thoughtbot]

It is free software, and may be redistributed under the terms specified in the
[license].

[![thoughtbot][thoughtbot-logo]][thoughtbot]

  [license]: LICENSE.md
  [thoughtbot]: https://thoughtbot.com?utm_source=github
  [thoughtbot-logo]: http://presskit.thoughtbot.com/images/thoughtbot-logo-for-readmes.svg
