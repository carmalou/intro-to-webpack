<!DOCTYPE html>
<html>
  <head>
    <title>Intro to webpack</title>
    <meta charset="utf-8">
    <style>
      @import url(https://fonts.googleapis.com/css?family=Yanone+Kaffeesatz);
      @import url(https://fonts.googleapis.com/css?family=Droid+Serif:400,700,400italic);
      @import url(https://fonts.googleapis.com/css?family=Ubuntu+Mono:400,700,400italic);
      body { font-family: 'Droid Serif'; }
      h1, h2, h3 {
        font-family: 'Yanone Kaffeesatz';
        font-weight: normal;
      }
      a {
        color: #a07cc0;
      }
      li {
        font-size: 24pt;
      }
      .remark-code, .remark-inline-code { font-family: 'Ubuntu Mono'; }
      .inverse {
        background: #000;
        color: #fff;
      }
      .remark-slide-content {
        background-size: contain;
        background-position: center;
        background-repeat: no-repeat;
      }
      .stripe {
        height: 5px;
        width: 100%;
        background-color: indigo;
        border-top: 1px solid rebeccapurple;
        border-bottom: 1px solid rebeccapurple;
        position: absolute;
        margin-top: 125px;
        left: 0;
        right: 0;
      }
      .remark-slide-right {
          bottom: 12px;
          position: absolute;
          left: 20px;
      }
      img {
        max-width: 100%;
        height: auto;
      }
      .carmalou {
          color: #CCBADC;
      }
      .no-margin-bottom h3 {
        margin-bottom: 0;
      }
      .javascript {
        line-height: 1.5;
      }
    </style>
  </head>
  <body>
    <textarea id="source">

class: center, middle, inverse

# Intro to [webpack](https://webpack.js.org/)
---
class: center, middle, inverse

# Intro to [webpack](https://webpack.js.org/)
---
class: center, middle, inverse

# What even is webpack?
---
class: center, middle, inverse

# What even is webpack?

webpack is a module bundler.
---
class: center, middle, inverse

# What even is webpack?

webpack is a module bundler.

Essentially it makes this work in the browser: 

```
var bootstrap = require('bootstrap');
---
class: center, middle, inverse

# webpack is the de facto standard module bundler across the web
---
class: left, middle, inverse

### It is used by:

- [AngularCLI](https://cli.angular.io/)
---
class: left, middle, inverse

### It is used by:

- [AngularCLI](https://cli.angular.io/)
- [VueCLI](https://cli.vuejs.org/)
---
class: left, middle, inverse

### It is used by:

- [AngularCLI](https://cli.angular.io/)
- [VueCLI](https://cli.vuejs.org/)
---
class: left, middle, inverse

### It is used by:

- [AngularCLI](https://cli.angular.io/)
- [VueCLI](https://cli.vuejs.org/)
- [Create React App](https://facebook.github.io/create-react-app/)
---
class: left, middle, inverse

### It is used by:

- [AngularCLI](https://cli.angular.io/)
- [VueCLI](https://cli.vuejs.org/)
- [Create React App](https://facebook.github.io/create-react-app/)
- Basically any scaffold you find
---


</textarea>
<script src="./scripts/remark-latest.min.js"></script>

</body>
</html>