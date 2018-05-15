# [Base Animations](http://getbase.org)

Base animations is designed in a way where you can add it on top of the Base CSS framework or to your own custom project.

[![Travis Build Status][travis-img]][travis] [![David Dependencies Status][david-img]][david]

[travis-img]:   https://img.shields.io/travis/getbase/animations.svg?branch=master
[david-img]:    https://img.shields.io/david/dev/getbase/animations.svg?branch=master&label=dependencies
[travis]:       https://travis-ci.org/getbase/animations
[david]:        https://david-dm.org/getbase/animations?type=dev

* * *

## Table of contents

* [Overview](#overview)
* [Installation](#installation)
* [Documentation](#documentation)
* [Demo](#demo)
* [Support](#support)
* [Authors](#authors)
* [License](#license)

* * *

## Overview

Base Animations is a very thin layer which includes animations for fading in content.

* * *

## Installation

If you have an existing project and would like to include the Base animations module, run the following command:

```bash
npm install --save @getbase/animations
```

Once you have the animations module installed, you can include it in your CSS/LESS/SCSS file with one of the following ways:

#### CSS Import:
  ```css
  import url("https://cdn.rawgit.com/getbase/animations/master/css/index.css");
  ```

#### SCSS Import:

  ```scss
  /* Import Base Animations */
  @import "node_modules/@getbase/animations/scss/index";
  /* Your Other Styles */
  @import "main"
  ```


#### LESS Import:

  ```css
  /* Import Base Animations */
  @import "node_modules/@getbase/animations/scss/index";
  /* Your Other Styles */
  @import "main"
  ```

* * *

## Documentation

Base Animations includes styles for fading in content.

#### Animations (Applies to SCSS/LESS)

| Class | Purpose | Example | Outcome |
| ------------ | ------- | ------- | ------- |
| `.fade-in` | Apply a `.fade-in` | `<div class="fade-in">Element fades in</div>` | Applies a fade in to a `div` element |
| `.fade-in-up` | Apply a `.fade-in-up` | `<div class="fade-in-up">Element fades in from bottom to top</div>` | Applies a fade in from bottom to top for a `div` element |
| `.fade-in-down` | Apply a `.fade-in-down` | `<div class="fade-in-down">Element fades in from top to bottom</div>` | Applies a fade in from top to bottom for a `div` element |
| `.fade-in-left` | Apply a `.fade-in-left` | `<div class="fade-in-left">Element fades in from right to left</div>` | Applies a fade in from right to left for a `div` element |
| `.fade-in-right` | Apply a `.fade-in-right` | `<div class="fade-in-right">Element fades in from left to right</div>` | Applies a fade in from left to right for a `div` element |


* * *

## Demo

[View page example](https://cdn.rawgit.com/getbase/animations/master/index.html) with the animations stylesheet applied.

* * *

## Support

* IE10+ and all other modern browsers.
* Please specify browsers you need to support in `package.json` according to [browserslist docs](https://github.com/ai/browserslist#queries).

* * *

## Authors

#### Matthew Hartman

* [https://twitter.com/matthewhartmans](https://twitter.com/matthewhartmans)
* [https://github.com/matthewhartman](https://github.com/matthewhartman)

* * *

## License

Code released under the [MIT Open Source](https://opensource.org/licenses/MIT) license.
