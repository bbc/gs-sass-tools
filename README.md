<h1 align="center">Grandstand Sass Tools</h1>
<p align="center">
    A collection of common Sass variables, functions and mixins.<br />
    Forms part of <a href="http://bbc.github.io/bbc-grandstand" target="_blank"><b>BBC Grandstand</b></a>
</p>

## What is this?

Grandstand Sass Tools is a collection of common Sass variables, functions and mixins.

This library is built and maintained by the BBC Sport team and used by the [Grandstand Framework](http://bbc.github.io/bbc-grandstand/) and various components on BBC Sport website and within the BBC Live product.

## Installation

Grandstand Sass Tools can be installed using NPM:

### Install using NPM

```bash
$ npm install --save git@github.com:bbc/gs-sass-tools.git
```

```sass
// your-app/main.scss
@import 'node_modules/gs-sass-tools/sass-tools';
```

## GEL Foundations

Grandstand Sass Tools is built on top of the GEL Foundations of:

- [GEL Sass Tools](https://github.com/bbc/gel-sass-tools)
- [GEL Typography](https://github.com/bbc/gel-typography)
- [GEL Grid](https://github.com/bbc/gel-grid)

These three libraries are automatically included as part of this library and all of there functionality is available.

For specific details on any of these libraries please refer to their individual README files.

## Settings

Settings are collections of globally available variables which can be used in your apps Sass.

### Global Variables
The global variables are primarily formed of the [GEL Sass Tools](https://github.com/bbc/gel-sass-tools).

### Colour Palettes
A number of products colour palettes are available as Sass variables:

- [Generic Colours](https://github.com/bbc/gs-sass-tools/blob/master/settings/_generic-colours.scss)
- [Sport](https://github.com/bbc/gs-sass-tools/blob/master/settings/_sport-colours.scss)
- [News](https://github.com/bbc/gs-sass-tools/blob/master/settings/_news-colours.scss)
- [MyBBC](https://github.com/bbc/gs-sass-tools/blob/master/settings/_mybbc-colours.scss)

## Tools

A number of Sass Mixins & Functions are available:

- [Clearfix](https://github.com/bbc/gs-sass-tools/blob/master/tools/_clearfix.scss) - A simple `clearfix` available as a mixin
- [Visibility](https://github.com/bbc/gs-sass-tools/blob/master/tools/_visability.scss) - A mixin hide content visually, but have it available for screen readers.
- [Flexbox](https://github.com/bbc/gs-sass-tools/blob/master/tools/_flexbox.scss) - A collection of `flexbox` mixins
- [Theme](https://github.com/bbc/gs-sass-tools/blob/master/tools/_theme.scss) - A mixin to output styles scoped in a theming class

## Why Grandstand?!?

This framework is named after [Grandstand](https://www.youtube.com/watch?v=HLHMxFGqhIs), a British television sport programme. Broadcast between 1958 and 2007, it was one of the BBC's longest running sports shows, alongside BBC Sports Personality of the Year.
